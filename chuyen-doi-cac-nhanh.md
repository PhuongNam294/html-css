clear: xóa sạch các thông tin đã gõ

git branch: kiểm tra nhánh hiện tại đang ở nhánh nào

git branch -a (git branch --all) : kiểm tra tất cả các nhánh

git branch -c + tên nhánh: tạo một nhánh mới (lấy code hiện tại sang nhánh vừa tạo lệnh) (nhưng nó sẽ không chuyển qua nhánh hiện tại đang dùng trên vscode)

git checkout: để chuyển sang nhánh khác

git checkout -b + tên nhánh: tạo một nhánh mới và chuyển nhánh hiện tại sang nhánh mới luôn

git push -u origin + tên nhánh cần push lên github (git pust --set-upstream + …) thiết lập mối quan hệ giữa nhánh cục bộ (local branch) và nhánh từ xa (remote branch)

git branch -d + tên nhánh : xóa nhánh nhưng không thể xóa nhánh đang tương tước

git branch -D + tên nhánh : nhánh mà đang commit mà chưa push lên thì không xóa được nên phải dùng lệnh này ép nó xóa

git log: xem lịch sử nhật ký

git log --online muốn thấy id và tên comments

git checkout + id :nếu muốn quay trở lại những code trước lúc thay đổi và nếu đang ở nhánh bạn xem mà muốn nó push lên thì dùng lệnh git checkout -b + tên nhánh

Lưu ý: những nhánh mà tạo riêng thì sẽ không bao giờ ảnh hưởng đến nhánh chính và copy ra
