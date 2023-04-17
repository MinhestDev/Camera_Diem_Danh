# Camera_Diem_Danh
***********Các bước cài source và import Database***********

*) Cài đặt XAMPP MySQL:
https://www.apachefriends.org/download.html
  - Sau khi đã cài đặt xong, Mở XAMPP lên
  - Sau khi đã Start thành công Apache và MySQL mở PHPMyAdmin bằng đường dẫn: http://localhost/phpmyadmin/
  - Tạo CSDL
+ Tạo database: face_recognizer
+ Click Chọn file và chọn file .sql trong source code

*) Cài đặt Python (khuyên dùng bản 3.6.5) và Pycharm(Hoặc IDE nào có hỗ trợ Python)

*) Cài đặt các thư viện cần thiết để chạy App
  - Mở thư mục chương trình bằng Pycharm
  - Cài đặt các thư viện sau bằng cách mở Terminal và nhập:
  + pip install + tên thư viện:
  + pip install opencv-contrib-python
	+ pip install mysql.connector
	+ pip install opencv-python
	+ pip install Pillow
	+ pip install numpy
	+ pip install tkcalendar

*) Sau khi đã cài đặt xong Run file login.py để chạy chương trình
	tài khoản:  (liên hệ admin - 0983.103.187)
	pass: (liên hệ admin - 0983.103.187)
  
*) Hướng dẫn sử dụng Phần mềm
- Bạn có thể đăng nhập phần mềm bằng tài khoản admin hoặc tài khoản giáo viên.

+) Admin: cho phép sử dụng tất cả các chức năng của phần mềm.

*) Sinh viên: Thêm, sửa ,xóa thông tin sinh viên,Chụp ảnh sinh viên bằng Webcam.
	Sau khi đã chụp ảnh sinh viên xong.Chọn Training Data để Train model nhận dạng sinh viên.
  
*)Giáo viên: Thêm, sửa ,xóa thông tin giáo viên.

*)Môn học: Quản lý thông tin môn học,Đăng ký môn học cho sinh viên,Thêm môn học cho giảng viên.(Phải thêm môn học cho sinh viên và giảng viên để điểm danh)

*)Buổi học: Thêm,sửa,xóa thông tin buổi học của từng môn học.

*)Xem ảnh:Xem tất cả các ảnh của sinh viên đã chụp trong máy.

*)Nhận dạng: Đối với Admin, cho phép điểm danh tất cả các buổi học trong ngày của tất cả các giáo viên
	Chọn Moonhoc/Id Bài học có trong ngày sau đó chọn Mở Camera để bắt đầu điểm danh:
	Hệ thống sẽ thông báo ra màn hình những sinh viên điểm danh thành công và lưu lên database.
	Những sinh viên chưa có dữ liệu khuôn mặt hoặc không có trong tiết học sẽ thông báo lên màn hình.
	Kiểm tra thời gian vào,ra lớp và so sánh với thời gian bắt đầu/kết thúc của tiết học qua đó lưu trạng thái điểm danh(Đi muộn,vắng,Có mặt) lên DB
  *)Điểm danh: Cho phép xem thông tin tất cả các bản điểm danh đc lưu trữ trên DB
  
*)Thống kê: Thống kê các sinh viên đi muộn, trốn về sớm  hoặc không điểm danh

+)Thầy giáo:Cho phếp sử dụng chức năng: Sinh viên,Thống kê,nhận dạng

*)Nhận dạng: cho phép điểm danh tất cả các buổi học trong ngày mà giảng viên được sắp xếp dạy
