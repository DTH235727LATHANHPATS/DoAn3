# ☕ QuanLyCoffe

## 📌 Giới thiệu
Phần mềm quản lý quán cafe viết bằng WinForms.

## 🚀 Công nghệ
- .NET 8
- Entity Framework Core
- SQL Server

## Buổi 3
- Tạo form Hóa Đơn và Chi Tiết Hóa Đơn

## Các lỗi gặp phải
- Sai kiểu dữ liệu khi code "Gia" là kiểu int nhưng kiểu của entity là decimal
- Trong Datagirdview cột ID bị báo lỗi đã tồn tại khi sửa column trong  Datagirdview
## Cách khắc phục
- Sửa code cho đồng nhất với kiểu dữ liệu Entity, hoặc chạy lại cơ sở dữ liệu 
- sửa tên cột ID thành ColID hoặc tạo lại bảng mới. 
## ⚙️ Cài đặt
```bash
git clone https://github.com/your-username/QuanLyCoffe.git