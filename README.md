# Portfolio Website - Trang Web Giới Thiệu Bản Thân

Một trang web portfolio hiện đại, responsive và đẹp mắt được thiết kế để giới thiệu bản thân với tính năng marketing mạnh mẽ.

## 🌟 Tính năng nổi bật

- **Thiết kế hiện đại**: Giao diện đẹp mắt với gradient và hiệu ứng glassmorphism
- **Responsive**: Tương thích hoàn hảo trên mọi thiết bị
- **Hiệu ứng tương tác**: Animations mượt mà và hấp dẫn
- **Navigation thông minh**: Menu sticky với smooth scrolling
- **Form liên hệ**: Tích hợp validation và thông báo
- **SEO friendly**: Cấu trúc HTML semantic
- **Performance tối ưu**: Tải nhanh và mượt mà

## 🚀 Cách sử dụng

### 1. Tùy chỉnh nội dung

Mở file `index.html` và thay đổi các thông tin sau:

```html
<!-- Thay đổi tên -->
<h1 class="hero-title">
    Xin chào, tôi là <span class="highlight">Tên của bạn</span>
</h1>

<!-- Thay đổi chức danh -->
<p class="hero-subtitle">Chức danh của bạn</p>

<!-- Thay đổi mô tả -->
<p class="hero-description">
    Mô tả về bản thân và chuyên môn
</p>
```

### 2. Cập nhật thông tin cá nhân

- **Ảnh đại diện**: Thay đổi URL ảnh trong `.profile-image img`
- **Thống kê**: Cập nhật số liệu trong `.profile-stats`
- **Kỹ năng**: Điều chỉnh phần trăm trong `.skill-progress`
- **Dự án**: Thêm/sửa các dự án trong `.projects-grid`
- **Thông tin liên hệ**: Cập nhật email, số điện thoại, địa chỉ

### 3. Tùy chỉnh màu sắc

Mở file `styles.css` và thay đổi các biến màu chính:

```css
/* Màu gradient chính */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Màu highlight */
background: linear-gradient(45deg, #ffd700, #ffed4e);
```

### 4. Thêm ảnh dự án

Thay thế các URL ảnh trong phần projects:

```html
<img src="đường_dẫn_ảnh_dự_án" alt="Tên dự án">
```

## 📁 Cấu trúc file

```
web/
├── index.html          # File HTML chính
├── styles.css          # File CSS với styles
├── script.js           # File JavaScript với interactions
└── README.md           # Hướng dẫn sử dụng
```

## 🎨 Tùy chỉnh giao diện

### Thay đổi font chữ

Trong `index.html`, thay đổi Google Fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=Tên_Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Thêm section mới

1. Thêm HTML section trong `index.html`
2. Thêm CSS styles trong `styles.css`
3. Thêm JavaScript interactions trong `script.js`

### Tùy chỉnh animations

Các animations được định nghĩa trong `styles.css`:

```css
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

## 📱 Responsive Design

Website được thiết kế responsive với các breakpoints:

- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🔧 Tính năng JavaScript

- **Mobile Navigation**: Menu hamburger cho mobile
- **Smooth Scrolling**: Cuộn mượt đến các section
- **Scroll Effects**: Navbar thay đổi khi scroll
- **Animations**: Hiệu ứng fade-in cho các elements
- **Form Validation**: Kiểm tra form liên hệ
- **Notifications**: Thông báo khi gửi form
- **Counter Animation**: Đếm số liệu thống kê
- **Parallax Effect**: Hiệu ứng parallax cho hero section

## 🌐 Triển khai

### GitHub Pages

1. Push code lên GitHub repository
2. Vào Settings > Pages
3. Chọn source là main branch
4. Website sẽ có URL: `https://username.github.io/repository-name`

### Netlify

1. Kéo thả thư mục web vào Netlify
2. Hoặc kết nối GitHub repository
3. Website sẽ được deploy tự động

### Vercel

1. Kết nối GitHub repository với Vercel
2. Deploy tự động khi push code
3. Có thể tùy chỉnh domain

## 📧 Liên hệ

Để được hỗ trợ hoặc tùy chỉnh thêm:

- Email: your-email@example.com
- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

## 📄 License

Dự án này được phát hành dưới MIT License. Bạn có thể tự do sử dụng và tùy chỉnh.

---

**Lưu ý**: Đừng quên thay thế tất cả thông tin mẫu bằng thông tin thực của bạn trước khi sử dụng!
