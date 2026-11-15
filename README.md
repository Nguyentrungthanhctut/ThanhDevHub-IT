# 🎓 IT Student Hub — Gemini AI PLUS & MAS Pro Ultimate

**IT Student Hub** là cổng tiện ích dành cho sinh viên Công nghệ Thông tin, tích hợp dịch vụ cung cấp tài khoản **Gemini AI PLUS + 400GB Google Drive** và bộ công cụ kích hoạt bản quyền **Windows & Office (Microsoft Activation Scripts - MAS)** trực quan, hiện đại.

![IT Student Hub Logo](./logo.jpg)

---

## ✨ Tính năng nổi bật

- **Giao diện Glassmorphism & Dark/Light Mode:** Thiết kế kính mờ hiện đại, chuyển đổi linh hoạt giữa chế độ Sáng/Tối và lưu trạng thái vào `localStorage`.
- **Đa ngôn ngữ (VI / EN):** Hỗ trợ chuyển đổi nhanh giữa tiếng Việt và tiếng Anh chỉ với 1 cú nhấp chuột.
- **Widget Thời tiết & Phần cứng thời gian thực:**
  - Tự động nhận diện vị trí qua IP (`ipapi.co`) và cập nhật nhiệt độ, tốc độ gió thực tế (`Open-Meteo API`).
  - Hiển thị hệ điều hành, trình duyệt, độ phân giải màn hình và trạng thái kết nối mạng của thiết bị.
- **Hub Đăng ký Gemini AI PLUS:** Tích hợp đồng hồ đếm ngược ưu đãi, form đăng ký nhanh và bảng cập nhật đơn hàng trực tiếp.
- **Trung tâm Kích hoạt Windows & Office (MAS Pro Ultimate):**
  - Sao chép nhanh các câu lệnh kiểm tra bản quyền (`slmgr /xpr`, `slmgr.vbs /dli`) và lệnh kích hoạt PowerShell / CMD.
  - **Trình tạo Custom Batch Script (`.bat`):** Cho phép chọn loại kích hoạt (HWID / KMS38), xem trước mã nguồn và tải trực tiếp file `.bat` tự động thực thi về máy.

---

## 📂 Cấu trúc thư mục

Đảm bảo file `logo.jpg` nằm cùng thư mục với `index.html` để hiển thị đầy đủ logo và favicon:

```text
IT-Student-Hub/
├── index.html      # Mã nguồn giao diện và logic xử lý chính
├── logo.jpg        # Logo thương hiệu & Favicon của IT Student Hub
└── README.md       # Tài liệu giới thiệu và hướng dẫn dự án
