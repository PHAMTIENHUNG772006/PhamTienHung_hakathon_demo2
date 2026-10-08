# DevOps Hackathon – Đề 002: Quản lý sản phẩm (Shop)[cite: 2]

## 1. Thông tin sinh viên
| Họ và tên | Mã sinh viên | Lớp | Tài khoản Linux | GitHub | Cổng Nginx |
|-----------|--------------|-----|-----------------|--------|------------|
Pham TienHung  424           CNTT2  pthung-k24cntt2  | https://github.com/PHAMTIENHUNG772006/PhamTienHung_hackathon 8080
## 2. Môi trường triển khai
(Hệ điều hành, phiên bản Nginx, Git, nơi chạy: VPS / máy ảo / WSL2)
24.04
phiên bản : 
https://github.com/PHAMTIENHUNG772006/PhamTienHung_hakathon_demo2.git
VPS


## 3. Cấu trúc dự án
(Cây thư mục của repository)

## 4. Cấu hình Nginx
| Tham số trong template | Giá trị đã điền | Giải thích |
listen	80	Cổng mà Nginx lắng nghe kết nối HTTP từ client.
server_name	_ (hoặc IP VPS)	Chỉ định tên miền hoặc IP để nhận diện các request.
root	/var/www/html	Thư mục chứa mã nguồn ứng dụng web trên máy chủ.
auth_basic	"Restricted"	Bật chế độ yêu cầu đăng nhập cơ bản.
