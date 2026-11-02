# Bảo tàng số Chủ tịch Hồ Chí Minh – Phường Bình Quới

Website triển lãm lịch sử trực tuyến, giao diện responsive, có không gian triển lãm 3D tương tác, dòng thời gian, bản đồ, thư viện chủ đề, liên kết phim tư liệu, trắc nghiệm và mã QR.

## Các tệp chính
- `index.html`: cấu trúc trang.
- `styles.css`: giao diện máy tính và điện thoại.
- `app.js`: dữ liệu, tương tác 3D, bản đồ, trắc nghiệm, QR.
- `sources.json`: danh mục nguồn tham khảo.

## Bật GitHub Pages
1. Mở **Settings** của repository.
2. Chọn **Pages** ở thanh bên.
3. Trong **Build and deployment**, chọn **Deploy from a branch**.
4. Chọn Branch **main**, Folder **/ (root)**, bấm **Save**.
5. Đợi GitHub triển khai xong rồi mở:
   https://ngovanhai130187-stack.github.io/bao-tang-so-ho-chi-minh/

## Chạy thử
Có thể mở `index.html` trực tiếp trong trình duyệt. Nếu trình duyệt hạn chế tài nguyên CDN, chạy máy chủ tĩnh:
```bash
python -m http.server 8000
```
Sau đó truy cập `http://localhost:8000`.

## Công nghệ
HTML5, CSS3, JavaScript, Three.js, Leaflet, OpenStreetMap và QRCode.js. Các thư viện được tải từ CDN, cần kết nối Internet.

## Lưu ý nội dung và bản quyền
Mô hình 3D trong bản hiện tại là mô hình minh họa, không phải ảnh chân dung hoặc ảnh tư liệu lịch sử gốc. Các thẻ thư viện dẫn tới chủ đề tìm kiếm/nguồn tham khảo, không tự ý sao chép ảnh. Trước khi công bố chính thức, cần kiểm chứng mốc thời gian, địa danh, chú thích; bổ sung ảnh/video được phép sử dụng và ghi rõ tác giả, đơn vị lưu trữ, giấy phép. Nội dung cần được đơn vị chuyên môn rà soát, phê duyệt.

## Nguồn tham khảo khởi đầu
- Bảo tàng Hồ Chí Minh: https://baotanghochiminh.vn/
- Cổng thông tin Hồ Chí Minh – Tiểu sử: https://hochiminh.vn/cuoc-doi-su-nghiep/tieu-su-ho-chi-minh/tieu-su-chu-tich-ho-chi-minh-1890-1969-9
- Biên niên tiểu sử: https://baotanghochiminh.vn/danh-sach-bien-nien-tieu-su/p-369.htm
- Quá trình viết Di chúc: https://hochiminh.vn/hoc-va-lam-theo-bac/di-chuc/qua-trinh-chu-tich-ho-chi-minh-viet-di-chuc-va-viec-cong-bo-di-chuc-cua-nguoi-110
