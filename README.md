# 🌹 Website Chúc Mừng 20/10 - Ngày Phụ Nữ Việt Nam

Một trang web chúc mừng ngày Phụ Nữ Việt Nam 20/10 với hiệu ứng động và âm nhạc nhẹ nhàng.

## 🌐 Truy Cập Website

Website được triển khai tại: **[f0rwomen2010.com](https://f0rwomen2010.com)**

## ✨ Tính Năng

- 🎨 Hiệu ứng vẽ hoa hồng động
- 💌 Thiệp chúc mừng với animation đẹp mắt
- 🎵 Nhạc nền nhẹ nhàng (có thể bật/tắt)
- 💝 Tin nhắn chúc mừng ấm áp
- 📱 Responsive, hiển thị tốt trên mọi thiết bị

## 🚀 Triển Khai Lên GitHub Pages

### Bước 1: Fork hoặc Clone Repository
```bash
git clone https://github.com/Duc-bug/20-10-vui-ve.git
cd 20-10-vui-ve
```

### Bước 2: Cấu Hình GitHub Pages
1. Vào **Settings** của repository
2. Chọn **Pages** ở menu bên trái
3. Trong phần **Source**, chọn branch `main` (hoặc branch chính của bạn)
4. Nhấn **Save**

### Bước 3: Cấu Hình Custom Domain (Tùy Chọn)

#### 3.1. Trong GitHub:
1. Vào **Settings** → **Pages**
2. Trong phần **Custom domain**, nhập tên miền của bạn (ví dụ: `f0rwomen2010.com`)
3. Nhấn **Save**
4. Đợi GitHub kiểm tra DNS (có thể mất vài phút)

#### 3.2. Cấu Hình DNS Tại Nhà Cung Cấp Tên Miền:

Thêm các bản ghi DNS sau:

**Đối với apex domain (f0rwomen2010.com):**
```
Loại: A
Host: @
Giá trị: 185.199.108.153
         185.199.109.153
         185.199.110.153
         185.199.111.153
```

**Đối với subdomain (www.f0rwomen2010.com):**
```
Loại: CNAME
Host: www
Giá trị: duc-bug.github.io
```

**Để hỗ trợ IPv6 (tùy chọn):**
```
Loại: AAAA
Host: @
Giá trị: 2606:50c0:8000::153
         2606:50c0:8001::153
         2606:50c0:8002::153
         2606:50c0:8003::153
```

⏳ **Lưu ý:** DNS có thể mất từ 5 phút đến 24 giờ để cập nhật hoàn toàn.

## 🎵 Tùy Chỉnh Nhạc Nền

Xem hướng dẫn chi tiết trong file: [`music/README.txt`](music/README.txt)

**Tóm tắt:**
1. Tải nhạc về định dạng MP3
2. Đổi tên thành `background.mp3`
3. Copy vào thư mục `music/`
4. Mở `index.html` để test

## 📝 Tùy Chỉnh Nội Dung

### Thay Đổi Tin Nhắn Chúc Mừng

Mở file `index.html` và tìm đến dòng:

```javascript
// Tiêu đề của thư
const textLetterH2 = "Gửi tất cả chị em phụ nữ!";

// Nội dung của thư
const textLetterP = "Nhân ngày Phụ nữ Việt Nam 20/10, chúc tất cả chị em luôn tươi trẻ, xinh đẹp, hạnh phúc và thành công trong cuộc sống. Hãy luôn giữ mãi nụ cười rạng rỡ và tự tin tỏa sáng mỗi ngày nhé!";
```

Thay đổi nội dung theo ý muốn của bạn.

### Thay Đổi Tiêu Đề Trang

Tìm dòng:
```html
<title>women's day</title>
```

Và thay đổi thành tiêu đề bạn muốn.

## 🛠️ Cấu Trúc Thư Mục

```
20-10-vui-ve/
├── CNAME                 # File cấu hình custom domain
├── README.md            # File hướng dẫn này
├── index.html           # Trang web chính
├── image/               # Thư mục chứa hình ảnh
│   ├── heartAnimation.gif
│   ├── mewmew.gif
│   └── ...
└── music/               # Thư mục chứa nhạc nền
    ├── README.txt       # Hướng dẫn thêm nhạc
    └── background.mp3   # File nhạc nền
```

## 🌟 Cách Sử Dụng Website

1. Mở website tại địa chỉ domain
2. Xem animation hoa hồng vẽ tự động
3. Click vào hoa hồng khi thấy chữ "Click me now!"
4. Đọc thiệp chúc mừng với animation đẹp mắt
5. Sử dụng nút nhạc ở góc dưới bên phải để bật/tắt nhạc nền

## 📋 Yêu Cầu Kỹ Thuật

- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Kết nối internet (để tải các thư viện CSS/JS từ CDN)
- JavaScript phải được bật

## 🔧 Thư Viện Sử Dụng

- [Bootstrap Grid](https://getbootstrap.com/) - Layout responsive
- [Animate.css](https://animate.style/) - CSS animations
- [Font Awesome](https://fontawesome.com/) - Icons
- [Anime.js](https://animejs.com/) - JavaScript animation library
- [jQuery](https://jquery.com/) - JavaScript library

## 📱 Tương Thích

Website tương thích với:
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Mobile (iOS Safari, Chrome Mobile)
- ✅ Tablet (iPad, Android tablets)

## 🤝 Đóng Góp

Nếu bạn muốn cải thiện website:
1. Fork repository này
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📄 License

Dự án này được tạo ra để chúc mừng ngày Phụ Nữ Việt Nam 20/10. Bạn có thể tự do sử dụng và tùy chỉnh cho mục đích cá nhân.

## 💖 Lời Cảm Ơn

Cảm ơn tất cả phụ nữ Việt Nam đã luôn kiên cường, tươi đẹp và lan tỏa yêu thương!

---

**Chúc mừng ngày 20/10! 🌹💐🎉**
