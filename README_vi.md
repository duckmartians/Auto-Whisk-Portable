# 🎨 Auto Whisk Generator  [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 
[![Download for Windows](https://img.shields.io/badge/Download%20for%20Windows-%F0%9F%92%BB-blue?style=for-the-badge)](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest) [![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest)

Auto Whisk Generator là công cụ hỗ trợ tự động hóa toàn bộ quy trình tạo ảnh trên Whisk AI (Google Labs).  
Thay vì phải thao tác thủ công từng prompt, công cụ cho phép bạn chạy liên tục và tạo ra hàng ngàn hình ảnh tự động.
<img width="2166" height="1032" alt="image" src="https://github.com/user-attachments/assets/e8532ac4-40ba-4e6b-8fe5-52d823b3e009" />

---

## 🛠️ Cài Đặt Extension "Cookie Exporter"

Để công cụ hoạt động, bạn cần cung cấp Cookie đăng nhập của tài khoản Whisk.  
Cài đặt extension hỗ trợ xuất Cookie:

**Tải Extension:**  
[Cookie Exporter – Chrome Web Store](https://chromewebstore.google.com/detail/fhnmmidekmgocpjdceeffppcodigillk)

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

Cookie JSON sẽ được dùng trong bước tiếp theo.

---

## 🚀 Chạy Tool Auto Whisk

Công cụ đã được đóng gói thành file `.exe`; không cần cài Python.

1. Tải file nén **Auto.Whisk.Generator.v24.11.2025.zip**.  
2. Giải nén.  
3. Mở **Auto Whisk Generator v24.11.2025.exe**.

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

1. Trong mục **Lấy Dữ liệu (Token/Project)**:  
   - Dán Cookie JSON đã sao chép vào ô nhập liệu.   
2. Nhấn **🚀 LẤY DỮ LIỆU MỚI**.  
3. Chờ 10–30 giây để tool xử lý.  

**Thành công:** Hiện trạng thái xanh **“Lấy token thành công!”** kèm thời gian hết hạn token.

---

### 🅱️ Bước B: Cấu Hình Tạo Ảnh

**Tỉ lệ & số lượng ảnh:**  
- Chọn 16:9, 9:16, hoặc 1:1.  
- Chọn số lượng ảnh mỗi prompt (1–4).

**Danh sách prompts:**  
- Nhập mỗi prompt trên một dòng.

**Thư mục lưu:**  
- Mặc định: thư mục `output` cạnh file `.exe`.  
- Có thể đổi bằng nút 📂.

---

### 🅾️ Bước C: Chạy & Theo Dõi

1. Nhấn **CHẠY MỚI (START NEW)**.  
2. Tool sẽ tự gửi prompt, chờ tạo ảnh, và tải ảnh xuống.  
3. Có thể xem tiến độ và ảnh preview ngay trong danh sách.

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
