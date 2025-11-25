# 🎨 Auto Whisk Generator  [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 
[![Download for Windows](https://img.shields.io/badge/Download%20for%20Windows-%F0%9F%92%BB-blue?style=for-the-badge)](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest)

[Cập nhật lúc 13:06 ngày 25/11/2025](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest)

Auto Whisk Generator là công cụ hỗ trợ tự động hóa toàn bộ quy trình tạo ảnh trên Whisk AI (Google Labs).  
Thay vì phải thao tác thủ công từng prompt, công cụ cho phép bạn chạy liên tục và tạo ra hàng ngàn hình ảnh tự động.

---

## 🛠️ Cài Đặt Extension "Cookie Exporter"

Để công cụ hoạt động, bạn cần cung cấp Cookie đăng nhập của tài khoản Whisk.  
Cài đặt extension hỗ trợ xuất Cookie:

**Tải Extension:**  
[Cookie Exporter – Chrome Web Store](https://chromewebstore.google.com/detail/fhnmmidekmgocpjdceeffppcodigillk)
<img width="1130" height="215" alt="image" src="https://github.com/user-attachments/assets/e20c7343-b16f-4dff-a2ef-33f1f2d624e9" />

**Cách cài:**
1. Truy cập liên kết bằng Chrome hoặc Edge.  
2. Chọn **Thêm vào Chrome (Add to Chrome)**.  
3. Biểu tượng con vịt 🦆 xuất hiện trên thanh công cụ (nếu không, mở mục tiện ích để ghim).

---

## 🍪 Lấy Cookie từ Whisk AI

1. Truy cập https://labs.google/fx/tools/whisk  
2. Đăng nhập tài khoản Google.  
3. Nhấn biểu tượng **Cookie Exporter** trên thanh trình duyệt.  
4. Ở phần *Export format*, chọn **JSON**.  
5. Nhấn **Copy** để sao chép Cookie vào clipboard.
<img width="1919" height="502" alt="image" src="https://github.com/user-attachments/assets/865798c4-092f-47b9-b5f3-70823cf3ecbe" />

Cookie JSON sẽ được dùng trong bước tiếp theo.

---

## 🚀 Chạy Tool Auto Whisk

Công cụ đã được đóng gói thành file `.exe`; không cần cài Python.

1. Tải file nén **[Auto.Whisk.Generator.v25.11.2025.zip](https://github.com/duckmartians/Auto-Whisk-Portable/releases/download/v25.11.2025/Auto.Whisk.Generator.v25.11.2025.zip)**.  
2. Giải nén.  
3. Mở **Auto Whisk Generator v25.11.2025.exe**.

## ⚠️ LƯU Ý QUAN TRỌNG: NẾU BỊ WINDOWS DEFENDER CHẶN

Nếu bạn mở tool và bị Windows báo lỗi virus (thường là Trojan:Win32/Wacatac...), xin đừng lo lắng. Đây là BÁO ĐỘNG GIẢ (False Positive).

Tại sao lại bị báo lỗi?
Tool được đóng gói bằng công cụ miễn phí PyInstaller. Vì tôi là lập trình viên cá nhân, không mua "Chứng chỉ số" (Digital Signature - loại giấy phép đắt tiền mà các hãng lớn dùng để chứng minh phần mềm an toàn) cho tool, nên Windows Defender sẽ mặc định chặn vì "thấy người lạ", không xác định được danh tính.

Cam kết an toàn:
1. Tool mã nguồn mở, chỉ thực hiện thao tác tự động trên trình duyệt, tuyệt đối không chứa mã độc.
2. Các phần mềm diệt virus chuyên sâu (như Kaspersky, ESET...) đều xác nhận file này SẠCH.
   
Cách khắc phục:
Để sử dụng, bạn vui lòng Thêm file tool vào danh sách loại trừ (Exclusions) hoặc tắt tạm thời Real-time protection của Windows Defender.

---

## 📖 Hướng Dẫn Sử Dụng Tool

Giao diện gồm 3 bước chính:

---

### 🅰️ Bước A: Lấy Dữ liệu (Token)

1. Trong mục **Cấu hình Tài Khoản**:  
   - Dán Cookie JSON đã sao chép vào ô nhập liệu.   
2. Nhấn **Kiểm tra & Lưu**.  
<img width="395" height="328" alt="image" src="https://github.com/user-attachments/assets/3108028a-0bb2-4f46-8063-14873be8da77" />

**Thành công:** Hiện trạng thái xanh **“Lấy token thành công!”** kèm thời gian hết hạn token.

---

### 🅱️ Bước B: Cấu Hình Tạo Ảnh

**Tỉ lệ & số lượng ảnh:**  
- Chọn 16:9, 9:16, hoặc 1:1.  
- Chọn số lượng ảnh mỗi prompt (1–4).
<img width="391" height="154" alt="image" src="https://github.com/user-attachments/assets/ad4d7632-d262-4f77-b32d-139b424a4b35" />

**Ảnh tham chiếu:**  
- Chọn chủ thể, bối cảnh, phong cách.
- Có thể dùng cùng lúc 3 ảnh chủ thể, 1 ảnh bối cảnh, 1 ảnh phong cách.
<img width="954" height="524" alt="image" src="https://github.com/user-attachments/assets/c1c3564a-10c2-4205-b7c2-24474cfcfa96" />

**Danh sách prompts:**  
- Nhập mỗi prompt trên một dòng.
<img width="370" height="144" alt="image" src="https://github.com/user-attachments/assets/b67fc0a8-38e9-43d5-afda-417b5da89cf1" />

**Thư mục lưu:**  
- Mặc định: thư mục `output` cạnh file `.exe`.  
- Có thể đổi bằng nút 📂.
<img width="370" height="77" alt="image" src="https://github.com/user-attachments/assets/ccf1c54e-5c69-4961-a87a-5084496736af" />

---

### 🅾️ Bước C: Chạy & Theo Dõi

1. Nhấn **CHẠY MỚI (START NEW)**.  
2. Tool sẽ tự gửi prompt, chờ tạo ảnh, và tải ảnh xuống.  
3. Có thể xem tiến độ và ảnh preview ngay trong danh sách.
<img width="387" height="54" alt="image" src="https://github.com/user-attachments/assets/575f5ebe-97b9-4882-b824-761a7ec82e0f" />

---

## 💡 Các Tính Năng Nâng Cao

- **⏯️ Resume/Pause:** Tạm dừng và tiếp tục không mất tiến độ.  
- **🔄 Retry:** Thử lại các ảnh bị lỗi (riêng lẻ hoặc tất cả).  
- **🔍 Viewer:** Nhấn vào thumbnail để xem ảnh lớn.  
- **📂 Quản lý:** Mở thư mục chứa ảnh hoặc xóa ảnh lỗi.  
- **☕ Donate:** Hỗ trợ tác giả qua nút **[☕ Mời tôi ly cà phê](https://duckmartians.info)**.

---

## ⚠️ Lưu Ý Quan Trọng

- **Token hết hạn:** Token Whisk thường sống ~1 ngày. Khi hết hạn, thực hiện lại Bước A.  
- **Bảo mật:** Không chia sẻ Cookie cho bất kỳ ai.

---

Chúc bạn tạo ra những tác phẩm nghệ thuật tuyệt vời! 🎨
