<div align="center">

# 🍏 LumiFinance
**Quản lý thu chi (Personal Finance Tracker)**

📱 *Đồ án Điện toán đám mây* · 💻 *Xây dựng bằng Flutter*

---

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

</div>

---

## 📸 Hình ảnh ứng dụng | Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/10e651c1-bd78-4f7c-a423-37d2c3ef454b" width="240" />
  <img src="https://github.com/user-attachments/assets/ea57101a-f2ae-42c8-8a2e-e9e3587245a4" width="240" />
  <img src="https://github.com/user-attachments/assets/a26745f2-a3e9-48cb-be7c-54d14752b0c8" width="240" />
  <img src="https://github.com/user-attachments/assets/1bc13726-b3a2-4ba2-bb4f-537913414a1a" width="240" />
  <img src="https://github.com/user-attachments/assets/ccc409db-537b-4fae-9c4e-8af7dad6eec0" width="240" />
  <img src="https://github.com/user-attachments/assets/b15861a7-9665-41fa-b81c-86318e8aa313" width="240" />
  <img src="https://github.com/user-attachments/assets/df55dd5b-777c-4e0e-9e97-16843009d86e" width="240" />
  <img src="https://github.com/user-attachments/assets/1ec1614d-6856-40b1-bdc9-0117771ca606" width="240" />
  <img src="https://github.com/user-attachments/assets/17ae945a-5db3-4f70-aa94-949ca3fe1252" width="240" />
  <img src="https://github.com/user-attachments/assets/1fae0c4e-840a-482f-888a-8ad20ac4f430" width="240" />
  <img src="https://github.com/user-attachments/assets/bc920419-db24-413e-89d0-352cdea146a2" width="240" />
</div>

---

## 🌟 Tính năng nổi bật | Key Features

- 🔐 **Xác thực người dùng:** Đăng nhập, đăng ký, quên mật khẩu an toàn với Firebase Auth.
- 👤 **Quản lý hồ sơ:** Tạo, xem và chỉnh sửa thông tin cá nhân mượt mà.
- 💳 **Quản lý tài chính cốt lõi:**
  - **Ví (Wallets):** Quản lý nhiều nguồn tiền, dễ dàng chuyển đổi giữa các ví.
  - **Giao dịch (Transactions):** Ghi chép thu/chi rành mạch, chi tiết.
  - **Danh mục (Categories):** Phân loại đa dạng, trực quan.
  - **Ngân sách (Budgets):** Lên kế hoạch chi tiêu thông minh.
- 📊 **Thống kê & Lịch sử:** Biểu đồ đẹp mắt, theo dõi luồng tiền trực quan.
- 🔔 **Thông báo (Push Notifications):** Luôn cập nhật trạng thái mới nhất qua Firebase Messaging.
- 📄 **Trích xuất PDF:** Xuất báo cáo giao dịch tiện lợi.

---

## 🎨 Ngôn ngữ thiết kế | Apple Design Language

Dự án theo đuổi phong cách **Minimalist & Clean** chuẩn Apple:
- 🌈 **Màu sắc:** Sử dụng tone màu signature: `pureWhite`, `lightGray`, `nearBlack`, `appleBlue`.
- ✍️ **Typography:** Kiểu chữ tinh tế với `displayHero` hầm hố cho tiêu đề và `body` gọn gàng cho nội dung, tối ưu trải nghiệm đọc.
- ✨ **Trải nghiệm:** Chú trọng vào hiệu ứng mượt mà và UI sang trọng.

---

## 🛠 Công nghệ & Thư viện | Tech Stack

| Thành phần | Công nghệ / Packages |
|------------|-----------------------|
| **Core** | Flutter (SDK ^3.11.4), Provider, Dio, Http |
| **Backend/Cloud** | Firebase Auth, Firestore, Firebase Messaging |
| **Tiện ích** | SharedPreferences, JWT Decoder, Intl, Image Picker |
| **UI/UX** | Cupertino Icons, Google Fonts, Flutter Spinkit |
| **File & Export** | Path Provider, Flutter PDFView, HTML to PDF, Share Plus |

---

## 📁 Cấu trúc thư mục | Folder Structure

```text
lib/
├── config/        # API endpoints, môi trường
├── screens/       # Giao diện chính (Home, Wallet, Budget...)
├── services/      # Logic kết nối API & Backend
├── theme/         # Design system (AppleColors, AppleTextStyles)
└── main.dart      # Entry point
```

---

## ⚙️ Cài đặt & Chạy ứng dụng | Setup & Run

1. **Yêu cầu hệ thống:**
   - Flutter SDK đã được cài đặt.
   - Emulator hoặc thiết bị thật (iOS/Android).

2. **Cài đặt thư viện:**
   ```bash
   flutter pub get
   ```

3. **Cấu hình môi trường:**
   - Thêm `google-services.json` (Android) / `GoogleService-Info.plist` (iOS) vào thư mục tương ứng.
   - Tuỳ chỉnh endpoint trong `lib/config/api_constants.dart` (hỗ trợ Local hoặc Render).

4. **Khởi chạy:**
   ```bash
   flutter run
   ```

---

<div align="center">

✨ *“Xây dựng giải pháp tài chính thông minh với trải nghiệm người dùng hoàn hảo.”* ✨

</div>
