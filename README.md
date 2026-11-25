# Trang web Đồ án tốt nghiệp Xây dựng & Dân dụng

Trang tĩnh (HTML) chạy được trên GitHub Pages, không cần máy chủ.

## Cấu trúc

- `index.html`: trang chính (nhẹ, khoảng 60KB).
- `assets/gallery/<loai-cong-trinh>/`: ảnh bản vẽ mẫu (`01.webp` là ảnh lớn, `01-thumb.webp` là ảnh nhỏ), đã đóng dấu tên.
- `assets/hero-crane.webp`: ảnh ở phần giới thiệu.
- `assets/og-image.jpg`: ảnh hiện ra khi chia sẻ link lên Zalo/Facebook.

## Đưa lên GitHub Pages

1. Giải nén file zip, tạo repository **Public** trên GitHub.
2. Vào repository, chọn *Add file → Upload files*, kéo thả **cả thư mục `assets`, file `index.html` và `README.md`** rồi bấm *Commit changes*.
3. Vào *Settings → Pages*, chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`, bấm *Save*.

## Hai việc cần làm sau khi có địa chỉ web

1. **Điền địa chỉ trang:** trong `index.html`, tìm `__SITE_URL__` (có 5 chỗ) và thay bằng địa chỉ thật, không có dấu `/` ở cuối.
   Ví dụ `https://ten-tai-khoan.github.io/ten-repo` hoặc `https://tenmien.vn`. Việc này giúp ảnh chia sẻ và Google nhận đúng trang.
2. **Google Analytics:** tìm dòng `window.GA_MEASUREMENT_ID = '';` ở đầu `index.html` và dán mã dạng `G-XXXXXXXXXX` vào giữa hai dấu nháy.

## Link riêng cho từng loại công trình

Thêm `#` và tên loại công trình vào sau địa chỉ trang, hoặc bấm nút *Sao chép link* trong cửa sổ xem mẫu:

- `#cao-tang-10-15`, `#cao-tang-20-30`, `#truong-lien-cap`
- `#nha-cong-vu`, `#truong-mau-giao`, `#nha-thep-cong-nghiep`
