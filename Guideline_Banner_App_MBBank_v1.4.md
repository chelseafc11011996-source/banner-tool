# Quy chuẩn thiết kế Banner — App MBBank

**Phiên bản:** v1.4 — 2025
**Nguồn:** `Guideline Banner App MBBank - 25042025.pdf` (bản gốc trên Google Drive, 40.520.696 byte, 35 trang, ngày 25/04/2025)
**Link gốc:** https://drive.google.com/file/d/1EetAOwXPr0rIBcUbv5JJhh14EcyGDHM3/view?usp=sharing
**Bản PDF đã tải về:** `Guideline_Banner_App_MBBank_-_25042025.pdf` (cùng thư mục với file này)
**Liên hệ trong guideline:** minhth1@mbbank.com.vn, dattt5@mbbank.com.vn
**Đơn vị soạn:** MB Bank — Ux team

> **Ghi chú về bản chuyển đổi này**
>
> - File `.md` này chuyển toàn bộ nội dung chữ của file PDF gốc sang dạng văn bản có cấu trúc. Nội dung được giữ nguyên ý, chỉ sắp xếp lại thành bảng và danh sách cho dễ tra cứu.
> - Một số trang trong PDF là sơ đồ / hình minh hoạ, không có văn bản trích xuất được. Những chỗ đó được ghi rõ là **“theo sơ đồ trong PDF”** và chỉ ghi lại các nhãn số / chữ đọc được trên sơ đồ, không tự suy diễn thêm.
> - Font trong PDF ghi là **“Avertar STD CY”** — giữ nguyên đúng chính tả trong file gốc (nhiều khả năng là Averta Std CY).
> - Trang 34–35 của PDF là trang trống, không có nội dung.
> - Các mã HEX trong file này là giá trị quy đổi trực tiếp từ bộ RGB ghi trong PDF (ví dụ R20 G30 B210 → `#141ED2`), và đã được đối chiếu bằng cách lấy mẫu màu trực tiếp từ mảng màu trong PDF: Mass Xanh đậm lấy mẫu ra đúng (20, 30, 210); Priority Xanh đen lấy mẫu ra đúng (7, 28, 44); Private Vàng kim loại lấy mẫu ra đúng (146, 119, 73). Ngoại lệ duy nhất là **Xanh Đen của phân khúc Private** — xem ghi chú ngay dưới bảng màu Private.

---

## Mục lục

- [Lời mở đầu](#lời-mở-đầu)
- [I. Banner truyền thông dạng đơn](#i-banner-truyền-thông-dạng-đơn)
  - [1. Vai trò](#1-vai-trò)
  - [2. Cách upload](#2-cách-upload)
  - [3. Tỷ lệ, kích thước tối thiểu](#3-tỷ-lệ-kích-thước-tối-thiểu)
  - [4. Cách sử dụng guideline](#4-cách-sử-dụng-guideline)
  - [5. Vị trí đặt](#5-vị-trí-đặt)
  - [6. Layout](#6-layout)
- [II. Banner truyền thông dạng nhóm](#ii-banner-truyền-thông-dạng-nhóm)
  - [1. Định nghĩa](#1-định-nghĩa)
  - [2. Vai trò](#2-vai-trò-1)
  - [3. Cách upload](#3-cách-upload-1)
  - [4. Tỷ lệ, kích thước, vị trí](#4-tỷ-lệ-kích-thước-vị-trí)
  - [5. Layout](#5-layout-1)
- [III. Banner và hình ảnh quản lý theo từng phân khúc](#iii-banner-và-hình-ảnh-quản-lý-theo-từng-phân-khúc)
  - [Phân khúc Mass](#phân-khúc-mass)
  - [Phân khúc Priority](#phân-khúc-priority)
  - [Phân khúc Private](#phân-khúc-private)
- [Phụ lục A — Checklist nhanh cho bộ phận kinh doanh](#phụ-lục-a--checklist-nhanh-cho-bộ-phận-kinh-doanh)
- [Phụ lục B — Bảng tra nhanh](#phụ-lục-b--bảng-tra-nhanh)
- [Điểm cần đối chiếu lại](#điểm-cần-đối-chiếu-lại)

---

## Lời mở đầu

Mục đích của hướng dẫn là giúp việc thiết kế banner trên App MBBank được tinh gọn mà vẫn truyền đạt đầy đủ nội dung và tính nhận diện của các phân khúc của MB.

Ux team khuyến khích các đối tác đảm bảo các tiêu chí thiết kế được đưa ra, nhằm đem lại sự hài hòa giữa banner với giao diện của App MBBank, mang đến những cảm xúc tích cực cho người dùng.

---

## I. Banner truyền thông dạng đơn

### 1. Vai trò

Banner truyền tải ưu đãi đến từ MB tới các nhóm đối tượng khách hàng, với ưu đãi phù hợp với mục tiêu kinh doanh của MB. Có hai loại: **Banner** và **Popup**.

- **Banner:** được hiển thị trực tiếp trong bố cục của giao diện, được coi như một phần của giao diện.
- **Popup:** được hiển thị đè lên giao diện của app, không can thiệp vào bố cục của giao diện.

Ux team khuyến khích các bên quản lý phân khúc đảm bảo các tiêu chí thiết kế được đưa ra, nhằm đem lại sự hài hòa giữa các banner với giao diện của App MBBank, mang đến những cảm xúc tích cực cho người dùng.

### 2. Cách upload

- **Popup:** lấy từ hệ thống của Insider.
- **Banner:** có thể custom link tuỳ từng luồng, lấy từ hệ thống back của app.

### 3. Tỷ lệ, kích thước tối thiểu

| Tên gọi | Tỷ lệ | Kích thước tối thiểu |
|---|---|---|
| Banner | 16:9 | 933 × 522 px |
| Banner | 16:9 | 1125 × 633 px (Khám phá) |
| Banner | 17:5 | 1700 × 500 px |
| Sticky popup | 12:4 | 1200 × 400 px |
| Half-screen popup | 3:4 | 900 × 1200 px |

### 4. Cách sử dụng guideline

Quy trình 4 bước theo guideline:

1. **Xác định kích thước cần làm**
   - Ưu tiên dùng kích thước tối thiểu.
   - Chọn loại hình banner phù hợp với nhu cầu: **Đơn / Nhóm**.
   - Xem: Tỷ lệ, kích thước tối thiểu và dung lượng.
2. **Xác định vị trí đặt banner**
   - Định vị vị trí và các yếu tố trên app xuất hiện cùng một màn hình với banner.
   - Đảm bảo không bị cắt nội dung hoặc chất lượng quá mờ.
   - Xem: Vị trí đặt.
3. **Xác định style**
   - Xác định tập khách hàng mục tiêu và các yếu tố thiết kế được sử dụng.
   - Đảm bảo hài hoà và phù hợp với môi trường xung quanh.
   - Xem: Graphic — Yếu tố hình ảnh.
4. **Điều chỉnh thông số**
   - Đi theo ngôn ngữ thiết kế phù hợp với từng tập khách hàng.
   - Xem: Text — Nội dung banner.
   - Nếu dùng theo kích thước tối thiểu: đảm bảo các nội dung đọc được và cân đối.
   - Nếu sử dụng kích thước lớn hơn, vui lòng tịnh tiến kích thước và cỡ chữ.
   - Ví dụ trong guideline: dùng kích thước 1600 × 900 (thay vì 933 × 522) cho tỷ lệ 16:9 → cỡ chữ title tối thiểu là **82 px** (thay vì 48 px).

### 5. Vị trí đặt

| Định dạng | Hiển thị | Vị trí |
|---|---|---|
| Banner 16:9 | Một hoặc nhiều banner, tối đa 5 | Trang chủ, Khám phá |
| Banner 17:5 | Một hoặc nhiều banner, tối đa 5 | Thẻ, Ưu đãi, Thanh toán, Vay Online |
| Sticky popup 12:4 | Cố định ở đầu màn hình | Trang chủ |
| Half-screen popup 3:4 | Hiển thị dạng popup trên trang chủ | Trang chủ |

Khoảng cách ghi trên sơ đồ vị trí trong PDF: **24 px** ở các cạnh ngoài của banner 16:9 và 3:4; **12 px** ở cạnh dưới của banner 16:9 trong một số vị trí; banner 17:5 ghi **24 px**.

### 6. Layout

#### Định nghĩa các thành phần

- **Vùng không an toàn:** vùng được đưa ra nhằm đảm bảo các yếu tố thiết kế trong banner được căn gióng với các yếu tố thiết kế có trên App. Khi thiết kế, các yếu tố nội dung hoặc yếu tố đọc **không được chạm vào** vùng này.
- **Yếu tố trang trí:** có thể dưới dạng text hoặc graphic. Bao gồm các thành phần trang trí, có thể xuất hiện hoặc không, nhưng vẫn không làm ảnh hưởng đến nội dung của banner.
- **Text — Nội dung banner (text):** gồm các nội dung truyền tải thông điệp chính của chương trình (chủ đề chiến dịch, khái quát nội dung chi tiết, CTA...) — **không thể bị cắt hoặc che mất** khỏi banner.
- **Graphic — Yếu tố hình ảnh chính (graphic):** gồm hình ảnh (người, vật thể, linh vật) — **không thể bị cắt hoặc che mất** khỏi banner.
- **Logo 1 — Logo MB.**
- **Logo 2 — Logo đối tác:** logo đối tác hoặc công ty cùng tập đoàn. Nếu chương trình không có đối tác ngoài MB, có thể không cần hiện logo.

> \* Ngoài vùng không an toàn, các vùng khác chỉ mang tính mô tả.
>
> Nội dung chạm vào vùng không an toàn là sai. Nội dung không cần fill hết vùng text.

#### Layout — không logo

Các tỷ lệ áp dụng, theo kích thước tối thiểu tương ứng:

- **16:9** — dựa trên 933 × 522
- **17:5** — dựa trên 1700 × 500
- **12:4** — dựa trên 1200 × 400
- **3:4** — dựa trên 900 × 1200

Các dạng bố cục trong sơ đồ: Graphic bên phải, Graphic bên trái, Graphic bên dưới, Graphic bên trên, Đối xứng. Khoảng cách ghi trên sơ đồ: **36 px** (16:9), **62 px** (17:5), **36 px** (12:4), **72 px / 120 px** (3:4).

#### Layout — có logo

Cùng 4 tỷ lệ và kích thước tối thiểu như layout không logo.

- Logo có thể căn trái / giữa tuỳ layout.
- Logo 1 (MB) và Logo 2 (đối tác) đặt cùng một nhóm ở phía trên của banner trong các sơ đồ mẫu.
- Các dạng bố cục trong sơ đồ: Hình bên phải, Hình bên trái, Hình dưới, Hình trên, Đối xứng.

---

## II. Banner truyền thông dạng nhóm

### 1. Định nghĩa

Là 1 banner được chia làm 2 phần hình ảnh hiển thị:

- **Parent (Banner chủ đề):** đại diện cho 1 nhóm ưu đãi, chiến dịch truyền thông. Khi ấn vào, điều hướng khách hàng đến ưu đãi, chiến dịch chung để tiếp tục khám phá thêm.
- **Child (Banner phụ trợ):** nằm bên trong banner chủ đề, chứa ưu đãi riêng liên quan đến banner chủ đề. Khi ấn vào, điều hướng khách hàng đến ưu đãi, chiến dịch cụ thể.

### 2. Vai trò

Banner dạng nhóm được sử dụng để tối ưu hoá không gian và truyền tải nhiều ưu đãi, thông điệp trong 1 không gian hiển thị. Giúp cung cấp thêm thông tin ưu đãi liên quan mà vẫn giữ sự phân cấp rõ ràng, dễ dàng tiếp cận mà không bị lẫn lộn.

### 3. Cách upload

Có thể custom link tuỳ từng luồng, lấy từ hệ thống back của app.

### 4. Tỷ lệ, kích thước, vị trí

- **Tỷ lệ:** 16:9
- **Kích thước tối thiểu:** 933 × 522 px
- **Vị trí:** Trang chủ, Khám phá
- **Hiển thị:** một hoặc nhiều banner, tối đa 5
- **Tỷ lệ hiển thị:** Parent = **2/3**, Child = **1/3** (ghi trong PDF là `= 2/3 a` và `= 1/3 a`).
- Khoảng cách ghi trên sơ đồ: **24 px** ở cạnh ngoài, **12 px** ở cạnh dưới trong một số vị trí.

### 5. Layout

Các định nghĩa về Vùng không an toàn, Yếu tố trang trí, Text, Graphic, Logo 1, Logo 2 áp dụng giống như banner dạng đơn (xem mục I.6). Ngoài ra:

- **Parent:** Banner chủ đề (sử dụng trong banner nhóm).
- **Child:** Banner phụ trợ (sử dụng trong banner nhóm).

#### Lưu ý ghi trong guideline (layout banner nhóm)

- Đảm bảo trên mỗi banner đều có **CTA** và CTA nên nằm phía dưới.
- Tối giản nội dung hiển thị.
- Không có logo, dành không gian hiển thị cho text, hình ảnh, CTA. *(Lưu ý: câu này xuất hiện trong cả hai trang layout nhóm — không logo và có logo — trong PDF gốc; phần layout có logo dùng Logo 3 / Logo 4 cho Parent và Child.)*
- **Corner radius: 16 px.**
- Khoảng cách ghi trên sơ đồ layout nhóm: **52 px** ở các cạnh, **36 px** cho vùng text; nhãn **30 px** xuất hiện cạnh corner radius 16 px trong sơ đồ.

#### Layout nhóm — không logo

Tỷ lệ 16:9, dựa trên 933 × 522. Các dạng bố cục: Graphic bên dưới, Graphic bên trên, Đối xứng — áp dụng riêng cho Parent và cho Child.

#### Layout nhóm — có logo

Tỷ lệ 16:9, dựa trên 933 × 522. Logo 3 / Logo 4 dùng cho Parent và Child. Các dạng bố cục: Graphic bên dưới, Graphic bên trên, Đối xứng — áp dụng riêng cho Parent và cho Child.

---

## III. Banner và hình ảnh quản lý theo từng phân khúc

### Vai trò chung

Banner có vai trò đặc thù tuỳ nhu cầu sử dụng của từng mục đích kinh doanh.

Ux team khuyến khích các bên quản lý phân khúc đảm bảo các tiêu chí thiết kế được đưa ra, nhằm đem lại sự hài hòa giữa các banner với giao diện của App MBBank, mang đến những cảm xúc tích cực cho người dùng.

### Cách upload chung

- Lấy nội dung và hình ảnh từ đầu mối của từng phân khúc.
- Hard code trên app.

---

## Phân khúc Mass

### Text — Nội dung banner

**Font:** Avertar STD CY

| Tên gọi | Note | Độ nặng | Cỡ chữ | Số lượng ký tự |
|---|---|---|---|---|
| Title | — | Bold | 48 px ~ 81 px | Tối đa 40 (cả dấu cách) |
| Description | — | Regular | Tối thiểu 30 px | Tự cân đối với layout và title |
| Action | Có thể có hoặc không | Regular | Tối thiểu 30 px | Tối đa 14 (cả dấu cách) |

**Ví dụ trong guideline:**

- Title: “Tặng e-voucher trị giá 1,500,000 VND”
- Description: “Collection”
- Action: “Khám phá”

### Graphic — Yếu tố hình ảnh: Màu sắc

Bảng màu thừa hưởng và phát triển từ bảng màu thương hiệu của tập đoàn.

Màu xanh MB là màu chính. Để phù hợp với định dạng số, hai màu xanh – đỏ đi kèm với bảng màu phụ: xanh bạc hà, xanh da trời, màu sen tím và hồng tím.

Các sắc độ có thể dùng đi kèm với màu chính nhằm điều chỉnh sự hài hoà cho banner. Ưu tiên sử dụng màu ví dụ ở thước ưu tiên (hình bên cạnh trong PDF).

#### Màu chính

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Xanh đậm | 20 | 30 | 210 | `#141ED2` |

#### Màu bổ trợ

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Xanh da trời | 160 | 210 | 255 | `#A0D2FF` |
| Sen tím | 180 | 165 | 250 | `#B4A5FA` |
| Xanh bạc hà | 155 | 230 | 200 | `#9BE6C8` |
| Hồng tím | 255 | 125 | 205 | `#FF7DCD` |

#### Nguyên tắc sử dụng và phân bổ tỷ lệ màu sắc trên các banner tiêu chuẩn

- Banner gồm **màu chủ đạo** đi kèm với **tông màu phụ trợ**.
- **Màu chủ đạo là màu chiếm > 50% diện tích banner.**
- Các màu được dùng làm màu chủ đạo:
  - Xanh đậm
  - Xanh da trời
  - Sen tím
- Màu **không** được dùng làm màu chủ đạo (chỉ dùng làm phụ trợ):
  - Xanh bạc hà
  - Hồng tím
- Trong trường hợp màu xanh đậm không là màu chủ đạo, ưu tiên dùng xanh đậm làm tông màu phụ trợ.

**Trường hợp dùng đúng:** Xanh MB là chủ đạo; Xanh da trời là chủ đạo; Sen tím là chủ đạo.

**Trường hợp dùng sai:**

- Tỷ lệ màu chiếm ít trên banner (quá nhiều trắng).
- Dùng màu không có trong bảng màu.
- Màu hồng tím là chủ đạo.

#### Nguyên tắc sử dụng và phân bổ màu sắc trên dạng banner nhóm

- Mỗi banner trong banner nhóm cần đảm bảo tuân thủ đúng nguyên tắc của banner tiêu chuẩn.
- Đảm bảo màu sắc chủ đạo giữa các banner trong nhóm có độ tương phản hiển thị tốt, không sử dụng các màu quá đối nghịch nhau trên bánh xe màu.
- Ví dụ gợi ý:
  - Xanh đậm – Xanh da trời
  - Xanh đậm – Sen tím
  - Xanh da trời – Sen tím
- Ví dụ trong PDF (trang 19): Xanh đậm – Xanh da trời; Sen tím – Tím nhạt; Xanh đậm – Xanh da trời.

**Trường hợp dùng sai (banner nhóm):** màu sắc không đủ độ tương phản.

**Ví dụ minh hoạ trong PDF:** “CHI TIÊU GIẢM GIÁ”, “Ưu đãi thẻ”, CTA “XEM NGAY” / “Mở ngay”.

### Graphic — Yếu tố hình ảnh: Hình ảnh người

**Phong cách thiết kế:** Các tín hiệu đồ hoạ kết với hình ảnh người mẫu đã tách nền.

**Phong cách chụp ảnh:**

- **Cảm giác chung:** người mẫu được chụp trong tư thế tự nhiên, thoải mái, tương tác tự tin và thoải mái thể hiện cá tính trước ống kính. Không gò bó, khuôn phép hay mang cảm giác diễn theo kịch bản.
- **Quốc tịch:** người mẫu có nét mặt của người Việt Nam.
- **Độ tuổi:** 20–30.
- **Trang phục:** mặc trang phục đơn giản có trong bảng màu.
- **Ánh sáng:** dùng ánh sáng tự nhiên hay ánh sáng ban ngày để tránh sự tương phản quá mạnh.

**Không dùng:**

- Dùng người quá cách điệu.
- Màu quần áo không có trong bảng màu.
- Tạo dáng không tự nhiên.
- Dùng người mẫu nước ngoài.

### Graphic — Yếu tố hình ảnh: Hình ảnh vật thể

**Phong cách thiết kế:** Các tín hiệu đồ hoạ kết với hình ảnh vật thể đã tách nền.

**Phong cách tạo hình:**

- **Cảm giác chung:** hiện đại, tươi mới và mang tính công nghệ cao.
- **Số lượng:** tuỳ thuộc vào layout, ưu tiên ít hình tránh gây rối.
- **Tông màu:** theo tông màu của bảng màu.
- **Chất liệu:** vật thể chính ưu tiên dùng chất liệu kính. Tránh chất liệu nhựa mang lại hình ảnh thiếu vững vàng và chuyên nghiệp.
- **Tạo hình:** glassmorphism (mô tả cho các dịch vụ, tính chất như an toàn, bảo hiểm...) hoặc vật thể thực tế (thẻ, ô tô, màn hình app...).

**Không dùng:**

- Dùng tạo hình quá phẳng.
- Không dùng màu có trong bảng màu.
- Chất liệu nhựa.
- Dùng nhiều vật thể.

---

## Phân khúc Priority

### Text — Nội dung banner

**Font:** Avertar STD CY | Playfair Display (chỉ dùng cho title)

| Tên gọi | Note | Độ nặng | Cỡ chữ | Số lượng ký tự |
|---|---|---|---|---|
| Title | — | Bold | 48 px ~ 81 px | Tối đa 40 (cả dấu cách) |
| Description | — | Regular | Tối thiểu 30 px | Tự cân đối với layout và title |
| Action | Có thể có hoặc không | Regular | Tối thiểu 30 px | Tối đa 14 (cả dấu cách) |

**Ví dụ trong guideline:**

- Title: “Sản phẩm Vay Online”
- Description: “Trải nghiệm Vay Online hoàn toàn mới trên App MBBank”
- Action: “Khám phá ngay”

### Graphic — Yếu tố hình ảnh: Màu sắc

Bảng màu thừa hưởng và phát triển từ bảng màu thương hiệu của tập đoàn.

Có hai màu chính: màu **xanh đen** là màu chính gợi lên cảm giác tinh tế mạnh mẽ. Màu **xám bạc** gắn liền với vẻ sang trọng, lịch lãm. Ngoài ra có bảng màu bổ trợ: xám bạc, xanh đá, xám đậm, hồng sen.

Các sắc độ có thể dùng đi kèm với màu chính nhằm điều chỉnh sự hài hoà cho banner. Ưu tiên sử dụng màu ví dụ ở thước ưu tiên (hình bên cạnh trong PDF).

#### Màu chính

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Xanh đen | 7 | 28 | 44 | `#071C2C` |

#### Màu bổ trợ

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Xám bạc | 120 | 140 | 153 | `#788C99` |
| Xanh đá | 40 | 95 | 149 | `#285F95` |
| Xám đậm | 77 | 77 | 79 | `#4D4D4F` |
| Hồng sen | 236 | 205 | 207 | `#ECCDCF` |

#### Nguyên tắc sử dụng và phân bổ tỷ lệ màu sắc trên các banner

- Banner gồm **màu chủ đạo** đi kèm với **tông màu phụ trợ**.
- **Màu chủ đạo là màu chiếm > 50% diện tích banner.**
- Các màu được dùng làm màu chủ đạo:
  - Xanh đen
- Màu **không** được dùng làm màu chủ đạo (chỉ dùng làm phụ trợ):
  - Xám bạc
  - Xanh đá
  - Xám đậm
  - Hồng sen (rất hạn chế)
- Trong trường hợp màu xanh đen không là màu chủ đạo, ưu tiên dùng xanh đen làm tông màu phụ trợ.

**Trường hợp dùng đúng:** Xanh đen là chủ đạo.

**Trường hợp dùng sai:**

- Dùng màu không có trong bảng màu.
- Màu xám bạc là chủ đạo.
- Màu hồng sen là chủ đạo.
- Xanh đen chỉ chiếm 5% diện tích mà được gọi là chủ đạo — sai.

**Ví dụ minh hoạ trong PDF:** “Miễn phí dịch vụ phòng chờ”, “Nhân 3 điểm thưởng”, “Thời gian từ 05–04/11/2023”.

### Graphic — Yếu tố hình ảnh: Hình ảnh người

**Phong cách thiết kế: Kết hợp 2 phong cách**

1. Ảnh chụp không can thiệp các yếu tố đồ hoạ (ưu tiên).
2. Các tín hiệu đồ hoạ kết với hình ảnh người mẫu đã tách nền (dùng nền sáng kết hợp với khối hình nhân vật đi theo bảng màu).

**Phong cách chụp ảnh:**

- **Ảnh chụp không can thiệp các yếu tố đồ hoạ:** ưu tiên sử dụng.
- **Các tín hiệu đồ hoạ kết với hình ảnh người mẫu đã tách nền:** chỉ dùng nền sáng kết hợp với khối hình nhân vật đi theo bảng màu.
- **Cảm giác chung:** đảm bảo tính cách thương hiệu tinh tế, đẳng cấp, toàn diện, cởi mở; nhân vật thể hiện được sự thư thái tận hưởng và sự chủ động trong cuộc sống.
- **Quốc tịch:** người mẫu có nét mặt của người Việt Nam.
- **Độ tuổi:** không hạn chế.
- **Trang phục:** mặc trang phục đơn giản có trong bảng màu.
- **Ánh sáng:** dùng ánh sáng tự nhiên hay ánh sáng ban ngày để tránh sự tương phản.

**Không dùng:**

- Dùng người quá cách điệu.
- Màu quần áo không có trong bảng màu.
- Tạo dáng gượng ép.
- Dùng ánh sáng không tự nhiên.

### Graphic — Yếu tố hình ảnh: Hình ảnh vật thể

**Phong cách thiết kế: Kết hợp 2 phong cách**

1. Ảnh chụp người mẫu hoặc cảnh thật: ưu tiên sử dụng.
2. Các tín hiệu đồ hoạ kết với hình ảnh vật đã tách nền: chỉ sử dụng trên nền sáng kết hợp hình chính theo bảng màu.

**Loại hình ảnh vật thể được dùng:**

- Hình ảnh đồ vật.
- Hình ảnh kiến trúc, không gian.

**Phong cách tạo hình:**

Đối với hình ảnh đồ vật:

- **Tập trung:** góc chụp cận cảnh với vật thể là trung tâm, nhấn mạnh chi tiết và chất liệu.
- **Nắm bắt khoảnh khắc:** ảnh chụp macro hoặc ảnh chụp từ trên không để ghi lại khoảnh khắc, tạo sự cường điệu cho sự kiện hoặc hoạt động.

Đối với hình ảnh kiến trúc, không gian:

- **Bố cục cân bằng:** chọn hình ảnh có đủ khoảng trắng tạo cảm giác không gian sang trọng.
- **Góc rộng:** hiển thị không gian rộng và thoáng.

**Không dùng:**

- Dùng sai tông màu.
- Ảnh chỉnh sửa quá nhiều.
- Ánh sáng không tự nhiên.
- Ảnh kiến trúc dùng góc hẹp.

---

## Phân khúc Private

### Text — Nội dung banner

**Font:** Avertar STD CY | Playfair Display (chỉ dùng cho title)

| Tên gọi | Note | Độ nặng | Cỡ chữ | Số lượng ký tự |
|---|---|---|---|---|
| Title | — | Bold | 48 px ~ 81 px | Tối đa 40 (cả dấu cách) |
| Description | — | Regular | Tối thiểu 30 px | Tự cân đối với layout và title |

> Đã xác minh bằng hình ảnh trang 29: bảng Text của Private trong PDF gốc chỉ có hai hàng Title và Description, **không có hàng Action** như ở Mass và Priority. Ví dụ minh hoạ cũng không có nút CTA, chỉ có dòng chữ trên ảnh và dấu `>`.

**Ví dụ trong guideline:** trang ví dụ của Private chủ yếu là hình minh hoạ màu sắc với nội dung “Thẻ Visa Infinite với nhiều ưu đãi, đặc quyền vượt trội”, “Nâng hạn mức tín dụng siêu nhanh ngay trên app”, “Đặc quyền tham dự sự kiện của các thương hiệu cao cấp”.

### Graphic — Yếu tố hình ảnh: Màu sắc

Bảng màu thừa hưởng và phát triển từ bảng màu thương hiệu của tập đoàn.

Có hai màu chính: màu **xanh đen** là màu chính gợi lên cảm giác mạnh mẽ, tính toàn vẹn và ổn định. **Vàng kim loại** là màu sắc gắn liền nhất với địa vị và sự sung túc, mang lại sự hoành tráng và khác biệt. Ngoài ra có bảng màu bổ trợ: nâu đất, xám đen, xám lạnh và vàng cam.

Các sắc độ có thể dùng đi kèm với màu chính nhằm điều chỉnh sự hài hoà cho banner. Ưu tiên sử dụng màu ví dụ ở thước ưu tiên (hình bên cạnh trong PDF).

#### Màu chính

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Xanh Đen | 11 | 28 | 43 | `#0B1C2B` |
| Vàng kim loại | 146 | 119 | 73 | `#927749` |

> **Cảnh báo lỗi in trong PDF gốc:** trên trang 30, con số in cạnh mảng màu Xanh Đen là R90 G75 B44 — bộ số này cho ra màu nâu `#5A4B2C`, không khớp mảng màu. Lấy mẫu trực tiếp từ mảng màu trong PDF cho ra (11, 28, 43) → `#0B1C2B`, gần như trùng với Xanh đen của Priority (7, 28, 44). File này dùng giá trị lấy mẫu `#0B1C2B` làm chuẩn, và ghi rõ con số in sai để đối chiếu với Ux team.

#### Màu bổ trợ

| Màu | R | G | B | HEX |
|---|---|---|---|---|
| Nâu đất | 104 | 80 | 64 | `#685040` |
| Xám đen | 88 | 89 | 91 | `#58595B` |
| Xám lạnh | 147 | 149 | 152 | `#939598` |
| Vàng cam | 250 | 162 | 57 | `#FAA239` |

#### Nguyên tắc sử dụng và phân bổ tỷ lệ màu sắc trên các banner

- Banner gồm **màu chủ đạo** đi kèm với **tông màu phụ trợ**.
- **Màu chủ đạo là màu chiếm > 50% diện tích banner.**
- Các màu được dùng làm màu chủ đạo:
  - Xanh đen
  - Vàng kim loại
- Màu **không** được dùng làm màu chủ đạo (chỉ dùng làm phụ trợ):
  - Vàng cam
  - *(Trong PDF, danh sách phụ trợ của Private chỉ ghi rõ “Vàng cam” ở phần này; Nâu đất, Xám đen, Xám lạnh được liệt kê ở bảng màu bổ trợ phía trên.)*
- Trong trường hợp màu xanh đen không là màu chủ đạo, ưu tiên dùng xanh đen làm tông màu phụ trợ. *(Câu này xuất hiện ở phần nguyên tắc chung; giữ nguyên theo PDF.)*

**Trường hợp dùng đúng:** Vàng kim loại là chủ đạo; Xanh đen là chủ đạo.

**Trường hợp dùng sai:**

- Dùng màu không có trong bảng màu.
- Màu vàng cam là chủ đạo.
- Nâu đất là chủ đạo.

### Graphic — Yếu tố hình ảnh: Hình ảnh người

**Phong cách thiết kế:** Chỉ dùng ảnh chụp, không can thiệp các yếu tố đồ hoạ như cắt dán đè lên hình hoặc cắt nền.

**Các phong cách chụp ảnh:**

- **Cảm giác chung:** mô tả sự tương tác ấm áp giữa các thế hệ khác nhau trong một gia đình để thể hiện yếu tố phát triển vững bền và di sản. Hình ảnh phải có bố cục cẩn thận, bảng màu cân bằng và được sắp đặt tỉ mỉ đến từng chi tiết. Người mẫu mang phong thái tự tin, tận hưởng sự thành công và thịnh vượng.
- **Quốc tịch:** người mẫu có nét mặt của người Việt Nam.
- **Độ tuổi:** ưu tiên người mẫu trưởng thành, độ tuổi 30+.
- **Trang phục:** mặc trang phục đơn giản có trong bảng màu. Chất liệu quần áo thể hiện sự cao cấp.
- **Ánh sáng:** ánh sáng tự nhiên, cân bằng. Tông ấm áp.

**Không dùng:**

- Dùng yếu tố đồ hoạ chèn vào hình.
- Màu quần áo không có trong bảng màu.
- Dùng tông màu lạnh.
- Dùng người mẫu nước ngoài.

### Graphic — Yếu tố hình ảnh: Hình ảnh vật thể

**Phong cách thiết kế:** Chỉ dùng ảnh chụp, không can thiệp các yếu tố đồ hoạ như cắt dán đè lên hình hoặc cắt nền.

**Loại hình ảnh vật thể được dùng:**

- Hình ảnh đồ vật.
- Hình ảnh kiến trúc, không gian.

**Phong cách tạo hình:**

Đối với hình ảnh đồ vật:

- **Tập trung:** góc chụp cận cảnh với vật thể là trung tâm, nhấn mạnh chi tiết và chất liệu.
- **Nắm bắt khoảnh khắc:** ảnh chụp macro hoặc ảnh chụp từ trên không để ghi lại khoảnh khắc, tạo sự cường điệu cho sự kiện hoặc hoạt động.

Đối với hình ảnh kiến trúc, không gian:

- **Bố cục cân bằng:** chọn hình ảnh có đủ khoảng trắng tạo cảm giác không gian sang trọng.
- **Góc rộng:** hiển thị không gian rộng và thoáng.

**Không dùng:**

- Không tập trung vào một vật thể.
- Ảnh chỉnh sửa quá nhiều.
- Ánh sáng không tự nhiên.
- Ảnh kiến trúc dùng góc hẹp.

---

## Phụ lục A — Checklist nhanh cho bộ phận kinh doanh

> Phụ lục này **không phải nguyên văn trong PDF** — là checklist do Muse tổng hợp lại từ các quy tắc trên, để người làm banner tự kiểm tra trước khi gửi duyệt.

- [ ] Đã chọn đúng phân khúc (Mass / Priority / Private) theo tập khách hàng.
- [ ] Đã chọn đúng định dạng và kích thước tối thiểu (16:9, 17:5, 12:4, 3:4, hoặc nhóm 16:9).
- [ ] Title ≤ 40 ký tự (cả dấu cách), cỡ 48–81 px ở kích thước tối thiểu, tịnh tiến khi làm khổ lớn hơn.
- [ ] Description cân đối với layout và title, cỡ tối thiểu 30 px.
- [ ] Action (CTA) ≤ 14 ký tự (cả dấu cách), cỡ tối thiểu 30 px — riêng Private không có hàng Action trong bảng Text của guideline.
- [ ] Màu chủ đạo chiếm > 50% diện tích, và là màu được phép làm chủ đạo của phân khúc đó.
- [ ] Không dùng màu ngoài bảng màu; không để banner quá nhiều trắng.
- [ ] Nội dung và hình ảnh chính không chạm vào vùng không an toàn, không bị cắt / che.
- [ ] Logo MB có mặt; logo đối tác chỉ thêm khi có đối tác ngoài MB.
- [ ] Banner nhóm: Parent 2/3 – Child 1/3, mỗi banner đều có CTA ở phía dưới, bo góc 16 px.
- [ ] Hình người: người Việt Nam, đúng độ tuổi và phong cách của phân khúc, trang phục trong bảng màu, ánh sáng tự nhiên.
- [ ] Hình vật thể: đúng tông màu bảng màu, ít vật thể, ưu tiên chất liệu kính / ảnh chụp thật (tuỳ phân khúc), không dùng chất liệu nhựa (Mass) hay cắt dán đồ hoạ (Private).
- [ ] Đã xem trước banner ở đúng vị trí trên app (Trang chủ / Khám phá / Thẻ / Ưu đãi / Thanh toán / Vay Online).

## Phụ lục B — Bảng tra nhanh

| | Mass | Priority | Private |
|---|---|---|---|
| Font | Avertar STD CY | Avertar STD CY + Playfair Display (title) | Avertar STD CY + Playfair Display (title) |
| Title | Bold, 48–81 px, ≤ 40 ký tự | Bold, 48–81 px, ≤ 40 ký tự | Bold, 48–81 px, ≤ 40 ký tự |
| Description | Regular, ≥ 30 px | Regular, ≥ 30 px | Regular, ≥ 30 px |
| Action | Regular, ≥ 30 px, ≤ 14 ký tự | Regular, ≥ 30 px, ≤ 14 ký tự | Không có trong bảng Text của guideline (chỉ Title + Description) |
| Màu chủ đạo được phép | Xanh đậm, Xanh da trời, Sen tím | Xanh đen | Xanh đen, Vàng kim loại |
| Màu chỉ làm phụ trợ | Xanh bạc hà, Hồng tím | Xám bạc, Xanh đá, Xám đậm, Hồng sen (rất hạn chế) | Vàng cam (+ Nâu đất, Xám đen, Xám lạnh ở bảng bổ trợ) |
| Người mẫu | Việt Nam, 20–30, tự nhiên | Việt Nam, không giới hạn tuổi, tinh tế / thư thái | Việt Nam, 30+, gia đình nhiều thế hệ, ấm áp |
| Vật thể | Glassmorphism / vật thật, chất liệu kính | Ảnh thật / đồ hoạ trên nền sáng, cận cảnh / macro | Chỉ ảnh chụp thật, cận cảnh / macro, góc rộng |

## Điểm cần đối chiếu lại

1. **Màu Xanh Đen của phân khúc Private (trang 30) — đã xác minh, là lỗi in trong PDF gốc:** con số in là R90 G75 B44 (`#5A4B2C`, tông nâu), nhưng lấy mẫu trực tiếp từ mảng màu cho ra (11, 28, 43) → `#0B1C2B` (xanh đen, gần trùng Priority). File này dùng `#0B1C2B`; nên báo lại Ux team để sửa bản guideline gốc.
2. **Hàng Action của phân khúc Private (trang 29) — đã xác minh bằng hình ảnh:** bảng Text của Private chỉ có Title và Description, không có hàng Action. Ví dụ minh hoạ cũng không có nút CTA.
3. **Khoảng cách layout (trang 7–8, 12–13):** các con số 36 px / 62 px / 72 px / 120 px / 52 px là nhãn trên sơ đồ; cách gán chính xác từng số cho từng cạnh cần đối chiếu lại với sơ đồ gốc khi thiết kế chi tiết.
4. **Trang 15, 22, 28** là trang chia phân khúc (chỉ có tiêu đề Mass / Priority / Private, không có nội dung chữ thêm).
5. **Trang 18–19, 25, 31** là trang ví dụ đúng/sai bằng hình ảnh; nội dung chữ trong file này chỉ ghi lại phần chữ đọc được, còn bố cục màu trong ví dụ cần xem trực tiếp trên PDF.
