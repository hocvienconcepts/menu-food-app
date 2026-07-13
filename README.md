# VCS Menu Food App — Menu Operating Tool

Công cụ kiểm soát giá bán và biên lợi nhuận cho menu trên food app, thuộc Học viện Concepts (VCS).

## Nội dung

- `index.html` — ứng dụng web độc lập (single-file HTML/CSS/JS, không cần build), đổi tên từ `11_VCS_Menu_Food_App_Concepts_Brand.html` để Cloudflare Pages nhận làm trang gốc.

## Deploy lên Cloudflare Pages (qua GitHub)

1. Push nội dung thư mục này lên một repo GitHub (nhánh `main`).
2. Vào Cloudflare Pages → **Create a project** → **Connect to Git** → chọn repo.
3. Cấu hình build:
   - Framework preset: **None**
   - Build command: *(để trống)*
   - Build output directory: `/`
4. Deploy. Trang gốc sẽ tự động load `index.html`.

## Dữ liệu

Dữ liệu menu được lưu tại trình duyệt người dùng (localStorage), không gửi lên server nào. Có thể xuất CSV hoặc in/lưu PDF trực tiếp từ giao diện.
