<div align="center">
  <img src="./logo.jpg" alt="ThanhDevHub-IT Logo" width="120" height="120" style="border-radius: 20px; border: 2px solid #3b82f6;" />
  <h1>🪟 MAS Pro Ultimate — ThanhDevHub-IT</h1>
  <p><strong>Hub tiện ích sinh viên IT: Quản lý kịch bản Windows & Office, kiểm tra trạng thái hệ thống và thời tiết thời gian thực</strong></p>

  ![Status](https://img.shields.io/badge/Status-Active-10b981?style=flat-square)
  ![Tech](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20Vanilla%20JS-3b82f6?style=flat-square)
  ![Language](https://img.shields.io/badge/Language-VI%20%7C%20EN-6366f1?style=flat-square)
  ![Author](https://img.shields.io/badge/Author-Nguyễn%20Trung%20Thành-0f172a?style=flat-square)
</div>

---

**ThanhDevHub-IT (MAS Pro Ultimate)** là trang web giao diện hiện đại (Glassmorphism) dành cho sinh viên IT, tích hợp bộ lọc phân loại theo nhu cầu, trình tạo tệp kịch bản tự động (`.bat`) trực tiếp trên trình duyệt cùng các widget theo dõi thông số thiết bị và thời tiết thực tế.

## ✨ Tính Năng Nổi Bật

### 1. 🛠️ Quản Lý Kịch Bản & Kiểm Tra Trạng Thái
- **Thanh kiểm tra bản quyền nhanh:** Sao chép tức thì các lệnh hệ thống (`slmgr /xpr`, `cscript //nologo %windir%\system32\slmgr.vbs /dli`) để kiểm tra thời hạn giấy phép trên máy tính.
- **Bộ lọc thông minh theo danh mục:** Phân loại rõ ràng giữa **Tất cả phương thức**, **Windows**, **Office** và **Tiện ích & Tạo Script**.
- **Trình tạo Custom Batch Script (`.bat`):** Cho phép tùy chọn chế độ cấu hình, xem trước mã nguồn trực tiếp trên giao diện và tải xuống file `.bat` chỉ với 1 click.

### 2. 📊 Widget Thời Gian Thực & Thông Số Phần Cứng
- **Thời tiết & Vị trí (GPS / IP):** Tự động nhận diện vị trí qua IP và cập nhật nhiệt độ, tốc độ gió thực tế bằng Open-Meteo API.
- **Nhận diện môi trường thiết bị:** Tự động phát hiện hệ điều hành, trình duyệt đang sử dụng, độ phân giải màn hình và trạng thái kết nối mạng.
- **Tùy biến giao diện:** Hỗ trợ chuyển đổi mượt mà giữa **Dark Mode / Light Mode** và song ngữ **Tiếng Việt / English** (lưu trạng thái bằng `localStorage`).

---

## 📂 Cấu Trúc Thư Mục

```text
ThanhDevHub-IT/
├── index.html      # Giao diện chính (Tailwind CSS + Vanilla JavaScript)
├── logo.jpg        # Logo thương hiệu & Favicon trang web
└── README.md       # Tài liệu hướng dẫn dự án
