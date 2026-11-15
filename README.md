# 🎓 ThanhDevHub-IT — Cổng Tiện Ích Sinh Viên IT

**ThanhDevHub-IT** là cổng tiện ích web hiện đại dành cho sinh viên Công nghệ Thông tin, tích hợp dịch vụ đăng ký **Gemini AI PLUS + 400GB Google Drive** cùng bộ công cụ hỗ trợ kích hoạt bản quyền **Windows & Office (Microsoft Activation Scripts - MAS)** trực quan, nhanh chóng.

![ThanhDevHub-IT Logo](./logo.jpg)

---

## ✨ Tính năng nổi bật

- **Giao diện Glassmorphism & Dark/Light Mode:** Thiết kế kính mờ hiện đại, chuyển đổi mượt mà giữa chế độ Sáng/Tối và tự động ghi nhớ trạng thái qua `localStorage`.
- **Đa ngôn ngữ (VI / EN):** Chuyển đổi nhanh giữa tiếng Việt và tiếng Anh chỉ với một cú nhấp chuột.
- **Widget Thời tiết & Phần cứng thời gian thực:**
  - Tự động nhận diện vị trí qua IP (`ipapi.co`) và hiển thị nhiệt độ, tốc độ gió thực tế (`Open-Meteo API`).
  - Phân tích và hiển thị hệ điều hành, trình duyệt, độ phân giải màn hình và trạng thái kết nối mạng của thiết bị.
- **Hub Đăng ký Gemini AI PLUS:** Tích hợp đồng hồ đếm ngược ưu đãi, form đăng ký nhanh và bảng cập nhật đơn hàng trực tiếp.
- **Trung tâm Kích hoạt Windows & Office (MAS Pro Ultimate):**
  - Sao chép nhanh các câu lệnh kiểm tra tình trạng bản quyền (`slmgr /xpr`, `slmgr.vbs /dli`) và lệnh PowerShell / CMD.
  - **Trình tạo Custom Batch Script (`.bat`):** Cho phép chọn phương thức kích hoạt (HWID / KMS38), xem trước mã nguồn và tải trực tiếp file `.bat` về máy.

---

## 📂 Cấu trúc thư mục

Đảm bảo file `logo.jpg` nằm cùng cấp với `index.html` để hiển thị đầy đủ logo thương hiệu và favicon trên trình duyệt:

```text
ThanhDevHub-IT/
├── index.html      # Mã nguồn giao diện và logic xử lý chính
├── logo.jpg        # Logo thương hiệu & Favicon của ThanhDev Hub
└── README.md       # Tài liệu giới thiệu và hướng dẫn dự án
