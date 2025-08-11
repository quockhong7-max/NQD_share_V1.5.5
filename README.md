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
- Hơn **50 lệnh quản lý** nhóm.
- Tự động chống:
  - 🛑 Spam
  - 🔗 Liên kết
  - ❌ Từ ngữ xấu
  - 😡 Nội dung tiêu cực

### 🎯 Social Bot
- Hơn **50 lệnh** giải trí:
  - 📺 YouTube
  - 🎵 TikTok
  - 🎶 ZingMP3, NhacCuaTui
  - ...và nhiều hơn nữa.

---

## 🚀 Hướng dẫn sử dụng

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