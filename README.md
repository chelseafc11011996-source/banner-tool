# Công cụ tạo Banner MBBank

Webtool giúp nhân viên bộ phận kinh doanh tạo banner app MBBank đúng
Guideline Banner App v1.4 (2025), theo hướng **prompt-first**: người dùng
không chuyên chỉ cần chọn layout → nhập nội dung → copy prompt đầy đủ
(kích thước, màu sắc, safezone, cỡ chữ) sang công cụ tạo ảnh khác
(Gemini / Imagen / Midjourney / Google Flow).

Bản chạy trực tiếp là web artifact trong Muse
(slug `c-ng-c-t-o-banner-mbbank`); repo này lưu trữ phiên bản của mã nguồn
để theo dõi thay đổi theo thời gian.

## Cách dùng

1. Mở `index.html` bằng trình duyệt (file tĩnh, không cần server).
2. **Step 1 — Chọn layout:** phân khúc (Mass / Priority / Private),
   định dạng (16:9, 17:5, Sticky 12:4, popup 3:4, banner nhóm),
   bố cục, màu chủ đạo, phong cách minh hoạ, thư viện 15 mẫu sẵn.
3. **Step 2 — Nội dung:** tiêu đề, mô tả, CTA, nhãn ưu đãi, tải ảnh
   tham chiếu (tối đa 3), chọn phong cách graphic, chọn logo.
4. **Step 3 — Kết quả:** prompt đầy đủ (Anh + Việt) để copy, demo
   layout, bảng kiểm tương phản WCAG, xuất trọn bộ 5 định dạng,
   phiếu duyệt PNG / HTML, lịch sử banner, tự động lưu nháp.

## Nguồn chuẩn

- `Guideline_Banner_App_MBBank_v1.4.md` — toàn bộ guideline v1.4
  chuyển sang Markdown, là nguồn chuẩn của dự án. Lưu ý: màu Xanh Đen
  của Private trong file PDF in sai (R90 G75 B44); giá trị đúng đã
  kiểm chứng bằng lấy mẫu điểm ảnh là **#0B1C2B**.
- `docs/USING_THE_GRAPH.md` (trong thư mục dự án guideline) — cách dùng
  đồ thị Graphify của guideline.

## Lưu trữ phiên bản

Mỗi lần thay đổi lớn trên artifact sẽ được snapshot vào repo này với
một commit có ghi rõ vòng thay đổi trong `CHANGELOG.md`. Xem
`AGENTS.md` để biết quy tắc làm việc của dự án.
