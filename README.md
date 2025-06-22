# WEB QUẢN LÝ TIỆM BÁNH NGỌT- CAKE SHOP
# Sinh viên thực hiện
- **Họ và tên:** Nguyễn Minh Phương  
- **Mã sinh viên:** 23015738  
- **Lớp:** Thiết kế web nâng cao-1-3-24 (COUR01.TH4)
***
# Mô Tả Dự Án
Ứng dụng Laravel giúp quản lý sản phẩm bánh ngọt, danh mục bánh ngọt và ngườ dùng. Hệ thống hỗ trợ đăng nhập, bảo mật, và thao tác CRUD với giao diện đơn giản.Giúp cả quản trị viên và khách hàng dễ dàng sử dụng.

Mục đích:
- Cung cấp công cụ cho quản trị viên để quản lý danh mục và sản phẩm bánh ngọt (CRUD), đồng thời phân quyền để bảo mật.
- Cho phép người dùng cuối đăng ký và đăng nhập an toàn, xem và tương tác với các sản phẩm.
  
## Công nghệ sử dụng
- Laravel 10
- Laravel Breeze (Xác thực)
- MySQL (qua XAMPP)
- Bootstrap

## Chức năng chính
Quản lý Người dùng (User)
- Đăng ký/đăng nhập/reset mật khẩu (Laravel Breeze)

Quản lý Danh mục bánh (Category)
- Thêm mới danh mục bánh ngọt (ví dụ: bánh kem, bánh quy, bánh su kem...)
- Thêm / Sửa / xóa danh mục
- Xem danh sách các danh mục

Quản lý bánh ngọt (CRUD)
- Thêm sản phẩm mới (gắn với một danh mục)
- Sửa / xóa sản phẩm
- Xem danh sách sản phẩm theo danh mục
- Upload hình ảnh, giá bán, mô tả sản phẩm

Bảo mật: XSS, CSRF, Validation, Auth, Authorization
***
# Sơ đồ hệ thống Website
## Sơ đồ chức năng
![image](https://github.com/user-attachments/assets/d0f9b0e1-66ab-4468-b554-25e8a2d23998)
## Sơ đồ thuật toán
Đăng nhập

![Screenshot 2025-06-19 111155](https://github.com/user-attachments/assets/39dc9222-15d0-4b30-a014-df7edbd807e6)

Đăng ký

![Screenshot 2025-06-19 113019](https://github.com/user-attachments/assets/15bae9cb-01a9-427f-a261-cf5362343ffb)

Người dùng truy cập web khi đã đăng nhập

![Screenshot 2025-06-19 115044](https://github.com/user-attachments/assets/20c35c38-4ccf-4c88-8a45-1b988ae175ff)
