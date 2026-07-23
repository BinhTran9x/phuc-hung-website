# Hướng dẫn tự thay logo và ảnh

## 1. Tải ảnh lên

1. Mở thư mục `assets` trong repository.
2. Chọn **Add file → Upload files**.
3. Kéo ảnh vào và bấm **Commit changes**.
4. Nên đặt tên ảnh không dấu, không có khoảng trắng, ví dụ: `logo-phuc-hung.png`, `banner-bep.jpg`.

## 2. Gắn ảnh vào website

1. Mở tệp `site-config.js`.
2. Bấm biểu tượng bút chì **Edit this file**.
3. Thay đường dẫn nằm giữa hai dấu ngoặc kép, ví dụ:
   - Logo: `logoUrl: "assets/logo-phuc-hung.png"`
   - Ảnh đầu trang: `heroImage: "assets/banner-bep.jpg"`
4. Bấm **Commit changes**.
5. Chờ khoảng 1–2 phút rồi tải lại website bằng Ctrl+F5.

Các ảnh trong `categoryImages` lần lượt là ba ảnh danh mục. Các ảnh trong `productImages` lần lượt tương ứng với Higold, Blum, Garis, Fulco, GANDX và Nisko.
