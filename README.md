# 🤖 Zalo ChatBot

**Zalo ChatBot** được phát triển bằng **JavaScript** với thư viện **zlbotdqt**.  
Tác giả: **SBT** – [GitHub](https://github.com/itisme)
Mod lại bởi **NQD** – [GitHub](https://github.com/NQD136)

```
                  .----.
      .---------. | == |
      |.-"""""-.| |----|
      ||       || | == |
      ||       || |----|
      |'-.....-'| |::::|
      `"")---(""` |___.|
     /:::::::::::\" _  "
    /:::=======:::\`\`\
    `"""""""""""""`  '-'
```

---

## 📌 Tính năng (v1.5.5)

### 🛠 Quản lý nhóm Zalo tự động
- Tự động bảo vệ nhóm
  - **Chống Spam**
  - **Chặn Liên kết**
  - **Lọc Từ Ngữ Xấu**
  - **Chặn Nội Dung Tiêu Cực**
  - **Chống Gửi Ảnh Nhạy Cảm**
  - **Chống Thu Hồi Tin Nhắn**
  - **Chỉ Được Phép Gửi Tin Nhắn Văn Bản**
  - **Kick Thành Viên**
  - **Chặn Thành Viên**
  - **Tự Động Duyệt Thành Viên**
  - **Tin Nhắn Tag All**

### 🎯 Social Bot
- Hơn **50 lệnh** giải trí:
  - 📺 YouTube
  - 🎵 TikTok
  - 🎶 ZingMP3, NhacCuaTui
  - ...và nhiều hơn nữa.

### 🎮 Tiện ích game

- **Tài xỉu**
- **Chẵn lẻ**
- **Bầu cua**
- **Kéo búa bao**
- **Nông trại**
---

## 🚀 Hướng dẫn sử dụng

**Yêu Cầu Bắt Buộc: Có Bản Nodejs V20**

### 1️⃣ Cấu hình
Mở tệp `config.json` trong thư mục `assets` và thiết lập:

- **Cookie**  
  - Dùng tiện ích **J2TEAM Cookies** để lấy cookie  
    [🔗 Cài đặt](https://chrome.google.com/webstore/detail/j2team-cookies/okpidcojinmlaakglcigllbpcpajaibco)

- **IMEI**  
  - Truy cập **Zalo Web** → Mở **DevTools** → Tab **Console** → chạy:
    ```javascript
    localStorage.getItem('z_uuid');
    ```
  - Hoặc dùng tiện ích **Zalo Cookies**  
    [🔗 Cài đặt](https://chromewebstore.google.com/detail/zalo-cookies/ncieaodaagbiemjpallkhhelkjkbkpmj)

- **UserAgent**  
  - Giữ mặc định hoặc lấy UserAgent mới tại [whatmyuseragent.com](https://whatmyuseragent.com/)

---

### 2️⃣ Chạy Bot
Chạy file:
```bash
run.bat
```

---

### 3️⃣ Thiết lập quyền Admin
- Lấy **UID** tài khoản cần cấp quyền qua bảng điều khiển.
- Thêm vào file:
```
assets/data/list_admin.json
```

---

### 4️⃣ Khởi động lại công cụ
Sau khi cấu hình, hãy **khởi động lại** bot để áp dụng thay đổi.

---

## ❤️ Lời cảm ơn
Cảm ơn bạn đã sử dụng mã nguồn của chúng tôi.  
Hy vọng bạn sẽ thích những tính năng mà **Zalo ChatBot** mang lại!
