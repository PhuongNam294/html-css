- <a> gắn kèm liên kết, email, sđt
- nếu trong href=”” → thì tải lại trang
- nếu trong href=”#” → quay lại trên đầu trang
- target trong thẻ <a> chỉ định cách mở liên kết được nhúng trong thẻ đó

* [ ]         target=”_bank”: mở trong tab mới
* [ ]         target=”_self”: mở trong trang hiện tại nó giống mặc định

- liên kết sdt dùng href=”tel:0338151434”
- liên kết mail đùng href=”mailto:hoangsourthen@gamil.com”

```bash
<a href="mailto:sep@example.com
?cc=dongnghiep@example.com
&bcc=doitac@congty.com
&subject=Bao+cao+tuần+nay
&body=Xin+chao+sep,+day+la+bao+cao+tuần+nay.+Xin+cam+on!">
  Gửi email
</a>

```

? dấu phân cách giữa mailto và phần tham số, các thành phần phía sau phân cách bằng & nếu trong cc có nhiều mail thì dùng dấu phẩy
