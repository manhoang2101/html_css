<h1>Install</h1>
<i>npm install -g sass</i> : cài đặt sass global

<h2>Clone source code về</h2>
<hr />

<h2>cấu trúc thư mục sẽ có 3 phần: </h2>
1. HTML file, file code giao diện
2. Thư mục style : chứa mã nguồn scss
3. Thư mục stylesheets : chứa mã nguồn css đã được build ra từ thư mục style

<br />
<h2>Cách code</h2>
Hiện tại mỗi màn hình sẽ tạo ra 1 file .html, bên trong file .html sẽ import file css từ thư mục stylesheets
(ví dụ about.html, sau đó tạo 1 file ở style -> style/about.scss)

sau đó chạy lệnh: <i>sass --watch style:stylesheets</i>
(lệnh này sẽ theo dõi mọi thay đổi ở thư mục style - code scss ---> mỗi thay đổi thì nó tự động build scss sang css, và file .html sẽ phải reload lại = cách F5 để cập nhật lại css mới nhất)

<hr />

Cách chạy code thì vào thư mục chứa code, rồi click phải file .html -> chọn open with, chọn trình duyệt để mở
