# AGENTS.md — mbbank-banner-tool

Quy tắc làm việc của dự án banner MBBank (áp dụng cho cả artifact
`c-ng-c-t-o-banner-mbbank` và repo này).

## Nguồn chuẩn

- `Guideline_Banner_App_MBBank_v1.4.md` là nguồn chuẩn — sửa đồ thị/code
  cho khớp với file .md, không bao giờ sửa ngược lại.
- Private dùng Xanh Đen **#0B1C2B**, không bao giờ dùng #5A4B2C
  (giá trị in sai trong PDF gốc).
- `text:action` (CTA) chỉ áp dụng cho Mass và Priority; Private không
  có CTA theo bảng chữ trong guideline.

## Prompt-first

- Mục đích cốt lõi của tool: giúp người không chuyên tạo prompt đầy đủ
  theo guideline để mang sang công cụ tạo ảnh khác, không phải chỉnh
  banner trong canvas.
- Prompt phải ép render chữ đúng nguyên văn (chữ trong ngoặc kép, cỡ chữ,
  safezone theo px), màu chủ đạo HEX chiếm >50%, mô tả logo MB starburst
  (tia mảnh tỏa ra, không phải sao 5 cánh), quy tắc tương phản và
  safezone cho minh hoạ.

## Graphify

- Dùng Graphify / đồ thị xác định (deterministic) để tiết kiệm token
  khi rà soát và cải tiến: tra cứu đồ thị trước, chỉ đọc file khi cần.
- Không dùng LLM để trích xuất hay dựng đồ thị.
- Sau khi thay đổi đồ thị, rebuild cả hai đồ thị và kiểm tra
  broken references = [].

## Lưu trữ phiên bản

- Mỗi snapshot đẩy lên GitHub ghi rõ vòng thay đổi trong CHANGELOG.md.
- Không đẩy file build tạm, audit log hay ảnh test lên repo.
