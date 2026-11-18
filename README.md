<div align="center">
  <img src="./logo.jpg" alt="ThanhDevHub-IT Logo" width="120" height="120" style="border-radius: 20px; border: 2px solid #3b82f6;" />
  <h1>🛠️ ThanhDevHub-IT — Windows Diagnostics, License Check & Dev Toolbox</h1>
  <p><strong>Bộ công cụ quản trị Windows, kiểm tra trạng thái bản quyền, đo độ trễ mạng và xử lý dữ liệu nhanh dành cho sinh viên IT</strong></p>

  ![Status](https://img.shields.io/badge/Status-Active-10b981?style=flat-square)
  ![Stack](https://img.shields.io/badge/Stack-Pure%20HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-3b82f6?style=flat-square)
  ![PWA](https://img.shields.io/badge/PWA-Ready-8b5cf6?style=flat-square)
  ![Language](https://img.shields.io/badge/Language-VI%20%7C%20EN-6366f1?style=flat-square)
  ![Author](https://img.shields.io/badge/Author-Nguyễn%20Trung%20Thành-0f172a?style=flat-square)
</div>

---

**ThanhDevHub-IT** là ứng dụng web tiện ích được thiết kế tối giản, tốc độ cao (không phụ thuộc framework nặng), giúp người dùng phổ thông và sinh viên IT kiểm tra trạng thái bản quyền Windows hợp lệ, chẩn đoán phần cứng, đo độ trễ mạng và xử lý dữ liệu lập trình ngay trên trình duyệt.

## ✨ Tính Năng Nổi Bật

### 1. 🪟 Trung Tâm Kiểm Tra & Quản Trị Bản Quyền Windows (`slmgr`)
- **Giải thích chi tiết từng lệnh chuẩn của Microsoft:**
  - `slmgr /xpr`: Kiểm tra nhanh thời hạn bản quyền (xác nhận vĩnh viễn hay có ngày hết hạn).
  - `slmgr /dli`: Xem phiên bản Windows (Home/Pro/Education), kênh phân phối (OEM/Retail/Volume) và 5 ký tự cuối của Product Key.
  - `slmgr /dlv`: Hiển thị thông số kỹ thuật chuyên sâu (`Activation ID`, `Installation ID`, thời gian gia hạn còn lại).
- **Hướng dẫn trực quan 3 bước (`Win + R`):** Giúp người dùng mới thao tác dễ dàng, kèm chức năng xuất tệp **`Kiem_Tra_Ban_Quyen_Windows.bat`** chạy tự động chỉ với 1 click.

### 2. 💻 Chẩn Đoán Hệ Thống & Thời Tiết Thông Minh
- **Thông số phần cứng chuyên sâu:** Tự động nhận diện hệ điều hành, trình duyệt, độ phân giải màn hình, tốc độ kết nối mạng, số luồng CPU (`hardwareConcurrency`), dung lượng RAM ước tính (`deviceMemory`) và phần trăm/trạng thái sạc pin.
- **Thời tiết & Vị trí (Cache 30 phút):** Cập nhật nhiệt độ và tốc độ gió thực tế qua Open-Meteo API, kết hợp bộ nhớ đệm `sessionStorage` 30 phút giúp tải trang tức thì và tránh giới hạn lượt gọi API.

### 3. 🌐 Network Latency / Ping Tester
- Đo độ trễ phản hồi thực tế (ms) từ trình duyệt đến các máy chủ phổ biến:
  - **Google Public DNS** (`dns.google` / `8.8.8.8`)
  - **Cloudflare Edge** (`1.1.1.1`)
  - **GitHub API Server** (`api.github.com`)

### 4. 🧰 Dev Toolbox — Bộ Công Cụ Lập Trình Viên
- **JSON Formatter:** Làm đẹp (Beautify), thu gọn (Minify) và kiểm tra lỗi cú pháp JSON.
- **Base64 Encoder / Decoder:** Mã hóa và giải mã chuỗi Base64 hỗ trợ đầy đủ tiếng Việt (UTF-8).
- **SHA-256 Hash Generator:** Tạo mã băm bảo mật SHA-256 tức thì bằng Web Crypto API chuẩn trình duyệt.
- **Hệ cơ số (Base Converter):** Chuyển đổi qua lại thời gian thực giữa **Decimal (Hệ 10)**, **Binary (Hệ 2)** và **Hexadecimal (Hệ 16)**.

### 5. ⚡ Trải Nghiệm Người Dùng & PWA
- **Command Palette (`Ctrl + K` / `Cmd + K`):** Mở hộp thoại tìm kiếm nhanh bằng phím tắt để tải file kiểm tra bản quyền, mở công cụ, đổi giao diện hoặc ngôn ngữ ngay lập tức.
- **Đa ngôn ngữ 100% & Dark/Light Mode:** Chuyển đổi đồng nhất giữa **Tiếng Việt / English** và giao diện **Tối / Sáng**.
- **Hỗ trợ PWA (Progressive Web App):** Cài đặt trực tiếp lên màn hình chính điện thoại hoặc máy tính và hoạt động ổn định cả khi ngoại tuyến.

---

## 📂 Cấu Trúc Thư Mục

```text
ThanhDevHub-IT/
├── index.html          # Giao diện chính, CSS tối ưu & toàn bộ logic JavaScript
├── logo.jpg            # Logo thương hiệu, Favicon & Icon ứng dụng PWA
├── manifest.json       # Cấu hình định danh ứng dụng web (PWA Manifest)
├── service-worker.js   # Bộ nhớ đệm ngoại tuyến (Offline Caching)
└── README.md           # Tài liệu hướng dẫn dự án
