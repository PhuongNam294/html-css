Bước 1: tạo responsitory (kho lưu trữ) trên github (lưu trữ dự án trên máy chủ git)

Bước 2: tạo một thư mục dự án cá nhân trên máy tính cá nhân

Bước 3: vào vs code chọn git bash

Bước 4: kiểm tra trạng thái của git (bằng lệnh git status)

Bước 5: khởi tạo git init trong thư mục hiện tại (ghi nhớ lại mọi thay đổi)

Bước 6: add thư mục vào staging area chờ commit (git add. → thêm tất cả, git add ten_thu_muc/ → thêm thư mục)

Bước 7; git commit -m "first commit" sau khi commit code đẩy vào local repo và push lên github

- Mỗi commit là một **bản chụp snapshot** của code tại thời điểm đó
- `-m` là message mô tả ngắn gọn (ở đây là “first commit”.)

Bước 8: git branch -M main (Đặt (hoặc đổi) tên nhánh chính thành `main`.)

- Ngày xưa Git mặc định là `master`, giờ đổi sang `main` cho đồng bộ với GitHub.
- `-M` nghĩa là “đổi tên dù nhánh đó đã tồn tại”.

Bước 9: git remote add origin https://github.com/tuhocvn/duan2.git (lệnh này để biết upload đi đâu kết nối máy cá nhân đến github)

- `origin` là **tên gọi tắt** của đường link GitHub

Bước 10: git push -u origin main (đẩy code lên git)

- `origin`: địa chỉ GitHub bạn vừa thêm ở trên.
- `main`: nhánh hiện tại bạn muốn đẩy lên.
- `-u`: giúp Git nhớ cặp này (`origin` ↔ `main`) để sau này chỉ cần gõ:

  ```javascript
  git push
  git pull
  ```
