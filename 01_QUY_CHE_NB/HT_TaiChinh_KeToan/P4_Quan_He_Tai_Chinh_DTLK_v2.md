# P4 · QUAN HỆ TÀI CHÍNH VỚI ĐỐI TÁC LIÊN KẾT
## Phiên bản 2.0 · Cập nhật 05/2026

> **Thuộc:** Hệ thống Quản lý Tài chính – Kế toán CTM  
> **Thay thế:** P4 phiên bản 1.0  
> **Lý do cập nhật:** Tích hợp hệ thống HĐ HTLK + Phụ lục (Bước 1–4); bổ sung cơ chế cam kết khoán theo kỳ; cập nhật thuật ngữ "lựa chọn và xác định vai trò"; bổ sung R9–R12 bảng rủi ro; bổ sung Điều 26.4 rủi ro kiêm nhiệm ĐTCX + GVLK  
> **Xem trước:** P3 · Quản lý chi phí | **Xem tiếp:** P5 · Giá thành – Giá vốn – KQKD

**Phần này gồm 6 điều:**

- Điều 21. Phân loại đối tác liên kết và hệ thống văn bản
- Điều 22. Cơ chế thuế theo tư cách pháp lý đối tác
- Điều 23. Quản lý hợp đồng và hồ sơ pháp lý
- Điều 24. Cơ chế tài chính — tạm ứng, cam kết khoán theo kỳ và quyết toán
- Điều 25. Phân biệt hợp đồng dịch vụ và quan hệ lao động
- Điều 26. Kiểm soát rủi ro thuế trong quan hệ với đối tác liên kết

---

## Điều 21. Phân loại đối tác liên kết và hệ thống văn bản

### 21.1. Khái niệm và phạm vi

**Đối tác Liên kết (ĐTLK)** bao gồm toàn bộ cá nhân, hộ kinh doanh và pháp nhân bên ngoài có ký Hợp đồng Hợp tác Liên kết Đào tạo (HĐ HTLK) với CTM. Mỗi đối tác **lựa chọn và xác định** một hoặc nhiều vai trò phù hợp với năng lực và điều kiện thực tế:

| Vai trò | Ký hiệu | Nội dung hợp tác | Phụ lục |
|---|:---:|---|:---:|
| Giáo viên liên kết — cá nhân không ĐKKD | **GVLK** | Khoán giảng dạy LT và/hoặc TH; xe + NL do CTM lo | PL B |
| Giáo viên liên kết — HKD/CNKD | **GVLK** | Khoán giảng dạy LT và/hoặc TH; xe + NL do CTM lo | PL C |
| Văn phòng tuyển sinh + phương tiện | **VPTS** | Khoán đào tạo có phương tiện; CTM ủy quyền TT nhiên liệu | PL D |
| Văn phòng tuyển sinh — pháp nhân trọn gói | **VPTS** | Khoán trọn gói GV + xe + NL + vận hành | PL E |
| Đối tác cho thuê xe | **ĐTCX** | Cho CTM thuê xe tập lái; thanh toán theo quý | PL F |
| Đối tác hoa hồng tuyển sinh | **ĐTHH** | Giới thiệu học viên; nhận hoa hồng theo kết quả | PL A |

> 📌 Khi một đối tác lựa chọn và xác định nhiều vai trò, mỗi vai trò được triển khai qua Phụ lục riêng — hạch toán và xử lý thuế **độc lập** theo từng vai trò. Trường hợp đặc biệt cần lưu ý: Điều 26.4.

### 21.2. Hệ thống văn bản — Trình tự 5 bước

```
BƯỚC 1 — HĐ HTLK (…/HĐHTLK-CTM)
          Hợp đồng khung — 1 năm, tự động gia hạn
          Xác lập: tư cách pháp lý, vai trò lựa chọn,
          nguyên tắc thuế, phân biệt dịch vụ/lao động

BƯỚC 2 — CÁC PHỤ LỤC (PL A → F)
          Ký khi phát sinh từng vai trò cụ thể
          Ghi: con số đơn giá, điều kiện, chứng từ thuế

BƯỚC 3 — PL CAM KẾT KHOÁN THEO KỲ (PL CK)
          Ký trước mỗi kỳ đào tạo khi chưa có DS HV
          Ghi: số lượng HV cam kết × đơn giá = tổng ước tính
          Kèm: đặt cọc TK 33871 + tạm ứng TK 141

BƯỚC 4 — THỰC HIỆN VÀ QUYẾT TOÁN (BM-07)
          Nghiệm thu → Hạch toán CP → Bù trừ TK 141 → TT

BƯỚC 5 — TÀI LIỆU NỘI BỘ QCTC-KT
          Bảng định mức hoa hồng — TGĐ phê duyệt
          Không phát hành cho đối tác
```

### 21.3. Ma trận phân loại và nghĩa vụ thuế

Xác định tư cách pháp lý là điều kiện bắt buộc **trước khi** ký hợp đồng, ghi nhận chi phí và thực hiện thanh toán:

| Tư cách pháp lý | Có ĐKKD | Thuế GTGT | Thuế TNCN/TNDN | Chứng từ | Căn cứ |
|---|:---:|:---:|:---:|---|---|
| Cá nhân không ĐKKD | ❌ | Không áp dụng | **10%** — CTM khấu trừ tại nguồn *(lần chi ≥ 2 triệu)* | Chứng từ khấu trừ TNCN theo mẫu BTC | Luật 109/2025/QH15 Điều 25 |
| HKD / Cá nhân KD *(DT ≤ 1 tỷ)* | ✅ | Theo ngành — tự nộp | 2% hoặc 5% TNCN — tự nộp | Bảng kê thay HĐ *(PL06)* | NĐ 68/2026; NĐ 141/2026; TT 50/2026 |
| HKD / Cá nhân KD *(DT > 1 tỷ lũy kế)* | ✅ | Theo ngành — tự nộp | 2% hoặc 5% TNCN — tự nộp | Hóa đơn điện tử có mã CQT | NĐ 68/2026; NĐ 141/2026; TT 50/2026 |
| Pháp nhân | ✅ | Theo thuế suất — tự nộp | TNDN tự kê khai | Hóa đơn GTGT điện tử bắt buộc | Luật 67/2025; Luật 48/2024 |

**Thuế suất khoán theo ngành nghề** *(Phụ lục I TT 40/2021 — còn hiệu lực)*:

| Ngành nghề | GTGT | TNCN | Tổng | Áp dụng |
|---|:---:|:---:|:---:|---|
| Giảng dạy, đào tạo | 5% | 2% | **7%** | PL C, PL D *(HKD/CNKD)* |
| Cho thuê tài sản *(xe tập lái)* | 5% | 5% | **10%** | PL F *(HKD/CNKD)* |
| Môi giới, hoa hồng, đại lý | 10% | 2% | **12%** | PL A *(HKD/CNKD)* |

> ⚠️ **Tối ưu thuế hợp pháp:** Khi đối tác có xe và tham gia đào tạo thực chất → ưu tiên cấu trúc vai trò VPTS (PL D — 7%) thay vì ĐTHH (PL A — 12%). Điều kiện bắt buộc: Bên B phải **thực sự cung cấp GV và xe** — không chỉ giới thiệu HV. Phản ánh đúng bản chất kinh tế thực chất.

### 21.4. Nguyên tắc nhất quán tư cách

Tư cách pháp lý xác định tại thời điểm ký HĐ HTLK phải duy trì nhất quán trong suốt thời hạn. Khi phát sinh thay đổi, Bên B thông báo ngay bằng văn bản để điều chỉnh nghĩa vụ thuế và hồ sơ. **Không điều chỉnh ngược** hồ sơ đã lập.

---

## Điều 22. Cơ chế thuế theo tư cách pháp lý đối tác

### 22.1. Cá nhân không ĐKKD — Khấu trừ TNCN tại nguồn

Công ty có trách nhiệm **khấu trừ thuế TNCN tại nguồn** trước khi chi trả. Cơ chế này độc lập — không phụ thuộc mức thu nhập hay ngưỡng doanh thu:

```
Bước 1 — Xác định tổng tiền khoán trước thuế theo BM-07
Bước 2 — Thuế TNCN = Tổng tiền khoán × 10%
Bước 3 — Số tiền thực chi = Tổng tiền khoán − Thuế TNCN
Bước 4 — Hạch toán:
          Nợ TK 622A — Tổng tiền khoán (trước thuế)
              Có TK 3335 — Thuế TNCN khấu trừ tại nguồn
              Có TK 112  — Số tiền thực chuyển khoản
Bước 5 — Cấp Chứng từ khấu trừ TNCN trong vòng 10 ngày
Bước 6 — Kê khai tờ khai 05/KK-TNCN; quyết toán 05/QTT-TNCN
```

> ⚠️ Không tách nhỏ các lần chi trả trong tháng để né ngưỡng 2 triệu đồng. Không dùng bảng kê thay hóa đơn cho đối tượng này.

### 22.2. HKD / Cá nhân KD — Tự kê khai và tự nộp

- Thuế suất khoán theo ngành nghề tại Phụ lục I TT 40/2021 *(xem Điều 21.3)*;
- Chứng từ xác định theo ngưỡng DT năm tại Cam kết PL05;
- Ngưỡng DT năm: **1 tỷ đồng** *(NĐ 141/2026 — hồi tố từ 01/01/2026)*;
- Cam kết DT PL05 cập nhật mỗi năm chậm nhất **31/01**; Kế toán công nợ nhắc trước 15 ngày;
- Hạch toán: **Nợ TK 622A / Có TK 331**; khi TT: **Nợ TK 331 / Có TK 112**.

### 22.3. Pháp nhân — Hóa đơn GTGT điện tử bắt buộc

- Bên B xuất Hóa đơn GTGT điện tử hợp lệ trước khi CTM thanh toán;
- Thuế suất GTGT năm 2026: **8%** *(NĐ 174/2025)*; về 10% từ 01/01/2027;
- Hóa đơn không hợp lệ → Kế toán **từ chối thanh toán**, yêu cầu điều chỉnh/thay thế;
- Hạch toán: **Nợ TK 622A + Nợ TK 1331 / Có TK 331**; khi TT: **Nợ TK 331 / Có TK 112**.

### 22.4. Kê khai và nộp thuế

| Nghĩa vụ | Tờ khai | Kỳ | Hạn nộp |
|---|---|:---:|---|
| TNCN khấu trừ tại nguồn | 05/KK-TNCN | Tháng/quý | Ngày 20 tháng/quý sau |
| Quyết toán TNCN năm | 05/QTT-TNCN | Năm | 31/3 năm sau |
| GTGT đầu ra | 01/GTGT | Tháng/quý | Ngày 20 tháng/quý sau |

**Phân công:** Kế toán tiền lương → GVLK cá nhân không ĐKKD. Kế toán công nợ → tất cả ĐTLK còn lại.

---

## Điều 23. Quản lý hợp đồng và hồ sơ pháp lý

### 23.1. Hồ sơ pháp lý tối thiểu thu thập trước khi ký HĐ HTLK

| Tư cách | Hồ sơ bắt buộc |
|---|---|
| Cá nhân không ĐKKD | CCCD còn hiệu lực; MST cá nhân |
| HKD / Cá nhân KD | GCN đăng ký HKD/ĐKKD; MST kinh doanh; CCCD người đại diện; **Cam kết DT PL05** |
| Pháp nhân | Giấy ĐKDN; MST; GP ngành nghề *(nếu có)*; người đại diện ký + ủy quyền *(nếu có)* |
| Bổ sung cho GVLK/VPTS | GCN giáo viên dạy thực hành *(nếu dạy TH)* — NĐ 94/2026 Điều 11 |
| Bổ sung cho ĐTCX/VPTS có xe | Bản sao công chứng: GP xe tập lái + Đăng kiểm + BH TNDS |

### 23.2. Cấu trúc hợp đồng bắt buộc

HĐ HTLK phải thể hiện đầy đủ:

| Điều khoản | Nội dung bắt buộc |
|---|---|
| Tư cách pháp lý | Ghi rõ tư cách; số CCCD/MST/ĐKKD |
| Vai trò lựa chọn | Đánh dấu ☑ từng vai trò; dẫn chiếu đúng Phụ lục tương ứng |
| Đơn giá | Theo từng Phụ lục; **không gộp nhiên liệu vào đơn giá khoán** |
| Tiền thuê xe *(PL F)* | Đơn giá tháng; thanh toán theo **quý**; xe sẵn sàng khai thác = phát sinh tiền thuê bất kể mức sử dụng thực tế — BLDS 91/2015 Điều 472 |
| Nghĩa vụ thuế | Ghi rõ tư cách và loại chứng từ thay HĐ áp dụng |
| Thanh toán | CK bắt buộc ≥ 5 triệu; thời hạn; điều kiện *(có BM-07)* |
| Phân biệt dịch vụ/lao động | 4 dấu hiệu bắt buộc theo Điều 25 |

### 23.3. Theo dõi và lưu trữ

- Kế toán công nợ lập và cập nhật sổ theo dõi HĐ HTLK; cảnh báo khi còn 30 ngày hết hạn;
- Cập nhật Cam kết DT PL05 mỗi năm chậm nhất **31/01**;
- Lưu trữ toàn bộ hồ sơ tối thiểu **10 năm**.

---

## Điều 24. Cơ chế tài chính — Tạm ứng, Cam kết khoán theo kỳ và Quyết toán

### 24.1. Nguyên tắc chung

- Đơn giá khoán dịch vụ tính trên **số HV hoàn thành chương trình và hoàn thành chạy DAT**;
- Hoa hồng tuyển sinh tính trên **học phí chưa thuế GTGT** × tỷ lệ % theo bậc xe hợp tác;
- Tiền thuê xe thanh toán theo **quý** — đơn giá tháng × 3 tháng/quý; xe sẵn sàng khai thác là phát sinh tiền thuê, không phụ thuộc giờ vận hành thực tế;
- Mọi khoản chi ≥ 5.000.000 đồng: bắt buộc **chuyển khoản ngân hàng** *(NĐ 320/2025)*;
- Nhiên liệu quản lý và thanh toán **riêng biệt** — không gộp vào bất kỳ đơn giá khoán nào.

### 24.2. Cơ chế tạm ứng chuẩn bị dịch vụ

- Mức tạm ứng tối đa: không quá ……% giá trị Phụ lục — Kế toán trưởng phê duyệt bằng văn bản;
- Hạch toán: **Nợ TK 141 / Có TK 112** — chưa ghi nhận chi phí;
- Bù trừ khi quyết toán cuối đợt/kỳ sau khi có BM-07;
- TK 141 theo từng đối tác phải được **quyết toán về 0** sau mỗi khóa hoàn thành.

### 24.3. Cơ chế cam kết khoán theo kỳ *(PL CK — Vấn đề 2)*

Áp dụng khi chưa có danh sách HV cụ thể và chưa có lịch khai giảng:

**Cơ sở pháp lý:** HĐ B2B giữa CTM và ĐTLK là hợp đồng dịch vụ dân sự/thương mại — pháp luật không cấm ký theo số lượng ước tính. Hợp đồng đào tạo B2C với từng HV cụ thể là văn bản riêng biệt *(TT 14/2025/TT-BXD Điều 4)*. Số lượng cam kết phải **không vượt lưu lượng còn lại** trong Giấy phép đào tạo của CTM *(NĐ 94/2026 Điều 38)*.

**Chuỗi hạch toán:**

```
Giai đoạn 1 — Ký PL CK (chưa có DS HV):
  Bên B nộp đặt cọc cam kết:
  Nợ TK 112 / Có TK 33871 ← Đặt cọc, chưa phải doanh thu

  CTM tạm ứng chuẩn bị dịch vụ:
  Nợ TK 141 / Có TK 112 ← Tạm ứng, chưa ghi nhận CP

Giai đoạn 2 — Có DS HV + lịch khai giảng:
  Ký Biên bản xác nhận DS HV
  PL CK tự động chuyển thành PL C/D/E chính thức

Giai đoạn 3 — Kết thúc khóa — BM-07:
  Nợ TK 622A / Có TK 331 ← Ghi nhận CP dịch vụ (toàn bộ)
  Nợ TK 331  / Có TK 141 ← Bù trừ tạm ứng
  Nợ TK 331  / Có TK 112 ← Thanh toán còn lại

  Bù trừ đặt cọc:
  Nợ TK 33871 / Có TK 331 ← Bù trừ vào thanh toán
  hoặc:
  Nợ TK 33871 / Có TK 112 ← Hoàn trả phần dôi ra
```

> ⚠️ **Nguyên tắc thuế quan trọng:** Nghĩa vụ thuế của Bên B và chi phí của CTM chỉ phát sinh từ thời điểm HV **khai giảng thực tế** — không phải từ thời điểm ký PL CK hay nhận tạm ứng. TK 141 không được ghi nhận vào chi phí cho đến khi có BM-07.

### 24.4. Quyết toán hoa hồng tuyển sinh *(PL A)*

| Thời điểm | Nghiệp vụ | Hạch toán |
|---|---|---|
| HV xếp lớp + lịch khai giảng | Tạm ứng hoa hồng *(tối đa ……%)* | Nợ TK 141 / Có TK 112 |
| HV khai giảng thực tế | Ghi nhận CP hoa hồng | Nợ TK 641 / Có TK 331 |
| Quyết toán | Bù trừ tạm ứng | Nợ TK 331 / Có TK 141 |
| Thanh toán | Chuyển khoản còn lại | Nợ TK 331 / Có TK 112 |
| Cá nhân không ĐKKD | Khấu trừ TNCN 10% | Nợ TK 331 / Có TK 3335 + TK 112 |

> 📌 **Ba điều kiện để CP hoa hồng được trừ TNDN:** *(i)* HĐ HTLK + PL A còn hiệu lực; *(ii)* Danh sách HV nhập học xác nhận Phòng Đào tạo; *(iii)* Chứng từ TT chuyển khoản hợp lệ.

### 24.5. Quyết toán tiền thuê xe *(PL F)*

| Thời điểm | Nghiệp vụ | Hạch toán |
|---|---|---|
| Theo dõi xe thuê | Ghi ngoại bảng | TK 001 — không ghi TSCĐ |
| Hàng tháng — NL | Ủy quyền TT NL cho Bên B | Nợ TK 141 / Có TK 112 |
| Hàng tháng — NL | Quyết toán NL đủ chứng từ | Nợ TK 621A / Có TK 141 |
| Hàng quý | Ghi nhận tiền thuê xe | Nợ TK 6277A / Có TK 331 |
| Hàng quý | Thanh toán tiền thuê | Nợ TK 331 / Có TK 112 |

> 📌 Tiền thuê xe cố định theo quý — không phụ thuộc giờ vận hành thực tế. Nhật ký vận hành (BM-NKX) là công cụ quản lý nội bộ của Phòng Đào tạo và Bộ phận Phương tiện — không phải căn cứ tính tiền thuê.

---

## Điều 25. Phân biệt hợp đồng dịch vụ và quan hệ lao động

Toàn bộ Phụ lục ký với ĐTLK là **hợp đồng dịch vụ dân sự** theo Điều 513 BLDS 2015, **KHÔNG phải hợp đồng lao động**. Bốn dấu hiệu phân biệt bắt buộc phải thể hiện rõ trong hợp đồng:

| # | Dấu hiệu | Hợp đồng dịch vụ *(đúng)* | Hợp đồng lao động *(sai)* |
|:---:|---|---|---|
| 1 | Tự chủ thực hiện | Bên B tự chủ trong cách thức tổ chức dịch vụ trong phạm vi thỏa thuận | Bên B chịu mệnh lệnh hành chính, theo ca phân công cố định |
| 2 | Thu nhập | Gắn với kết quả thực tế *(HV hoàn thành, HV giới thiệu, tháng xe cho thuê)* | Lương cố định hàng tháng không phụ thuộc kết quả |
| 3 | Tính đa đối tác | Bên B có quyền hợp tác với đối tác khác *(trừ ràng buộc không cạnh tranh)* | Bên B thuộc biên chế, chịu quy chế lao động nội bộ |
| 4 | Công cụ lao động | Thu nhập không gắn với việc ai cung cấp phương tiện | NSDLĐ cung cấp toàn bộ công cụ, phương tiện |

Nếu cơ quan có thẩm quyền xác định là quan hệ lao động: hai bên phối hợp chuyển đổi trong 30 ngày; CTM chịu trách nhiệm đóng BHXH từ thời điểm phát sinh nghĩa vụ.

---

## Điều 26. Kiểm soát rủi ro thuế trong quan hệ với đối tác liên kết

### 26.1. Bảng rủi ro và biện pháp kiểm soát

| # | Rủi ro | Mức độ | Biện pháp kiểm soát |
|---|---|:---:|---|
| R1 | Áp dụng sai tư cách pháp lý → sai cơ chế thuế | 🔴 Cao | Xác định trước khi ký; Kế toán kiểm tra hồ sơ; không thanh toán nếu chưa xác định |
| R2 | GVLK bị xác định lại là quan hệ lao động → truy thu BHXH | 🔴 Cao | 4 dấu hiệu phân biệt bắt buộc tại Điều 25 |
| R3 | HKD không cung cấp đúng chứng từ → chi phí không được trừ | 🟡 TB | Cam kết DT PL05 khi ký HĐ; kiểm tra chứng từ trước thanh toán |
| R4 | Không cấp chứng từ khấu trừ TNCN → GVLK không quyết toán được | 🟡 TB | Cấp trong 10 ngày sau thanh toán; theo dõi danh sách cấp |
| R5 | Gộp nhiên liệu vào tiền khoán → bị loại CP và truy thu | 🔴 Cao | Cấm tuyệt đối trong hợp đồng và quy trình; Kế toán trưởng kiểm tra |
| R6 | Thanh toán tiền mặt ≥ 5 triệu → CP không được trừ | 🔴 Cao | Kế toán TT kiểm tra trước khi giải ngân; từ chối nếu vi phạm |
| R7 | Hóa đơn pháp nhân không hợp lệ → mất khấu trừ GTGT | 🟡 TB | Kiểm tra hóa đơn trước thanh toán; yêu cầu điều chỉnh ngay |
| R8 | Tách nhỏ giao dịch để né ngưỡng 5 triệu | 🔴 Cao | Cấm tuyệt đối; xử lý kỷ luật và truy thu thuế |
| R9 | Áp ngưỡng DT HKD cũ *(500 triệu)* thay vì ngưỡng mới *(1 tỷ)* | 🔴 Cao | Cập nhật PL05 và hệ thống theo NĐ 141/2026; Kế toán trưởng ký xác nhận hàng năm |
| R10 | GVLK dạy TH không có GCN hợp lệ → vi phạm điều kiện KD, CP không hợp lệ | 🔴 Cao | Kiểm tra GCN trước khi ký HĐ và trước mỗi lần TT; dừng TT ngay khi GCN hết hạn |
| R11 | Số GVLK vượt lưu lượng GP đào tạo → vi phạm điều kiện kinh doanh | 🟡 TB | Phòng ĐT xác nhận lưu lượng trước khi ký PL mới; đối chiếu cuối kỳ |
| **R12** | **Cá nhân kiêm nhiệm ĐTCX + GVLK không ĐKKD → cơ quan BHXH/thuế xác định lại là quan hệ lao động thực chất** | 🔴🔴 **Rất cao** | **Xem chi tiết Điều 26.4** |

### 26.2. Nguyên tắc không hồi tố

Tư cách pháp lý và cơ chế thuế đã áp dụng **không được điều chỉnh ngược**. Khi phát hiện áp dụng sai, Kế toán trưởng phải: *(1)* báo cáo TGĐ ngay; *(2)* xác định số thuế bị thiếu; *(3)* phối hợp tư vấn thuế xử lý theo quy trình tự khai bổ sung; *(4)* **không tự ý điều chỉnh hồ sơ đã lập**.

### 26.3. Checklist kiểm tra trước khi thanh toán cho ĐTLK

- ☐ Đã xác định đúng tư cách pháp lý và vai trò theo Điều 21
- ☐ HĐ HTLK và Phụ lục tương ứng còn hiệu lực
- ☐ BM-07 đã ký đầy đủ *(trừ thanh toán tiền thuê xe — không cần BM-07)*
- ☐ Cam kết DT năm PL05 còn hiệu lực *(HKD/CNKD)*
- ☐ Chứng từ thuế đúng loại theo tư cách pháp lý
- ☐ Số tiền ≥ 5 triệu → bắt buộc chuyển khoản
- ☐ Đã khấu trừ TNCN tại nguồn *(nếu là cá nhân không ĐKKD)*
- ☐ Không có nhiên liệu gộp trong tiền khoán
- ☐ GCN giáo viên dạy TH còn hiệu lực *(nếu là GVLK dạy TH)*
- ☐ **Kiểm tra kiêm nhiệm: Bên B có đồng thời là ĐTCX cho CTM thuê xe không?** → Nếu có: xử lý theo Điều 26.4 trước khi thanh toán
- ☐ Kế toán trưởng đã ký phê duyệt

### 26.4. Rủi ro đặc biệt — Cá nhân kiêm nhiệm ĐTCX + GVLK không ĐKKD

> ⚠️ **Đây là rủi ro pháp lý kép — mức độ rất cao.** Kế toán trưởng phải đọc kỹ và áp dụng đúng quy trình trước khi ký hợp đồng với bất kỳ cá nhân nào thuộc tình huống này.

#### 26.4.1. Bản chất rủi ro

Khi một cá nhân đồng thời thực hiện 2 vai trò với CTM:
- Cho thuê xe tập lái *(ĐTCX)* → thu tiền thuê xe *(PL F)*
- Giảng dạy trên chính chiếc xe đó *(GVLK)* → thu thù lao dạy học *(PL B)*

Cơ quan thanh tra BHXH và cơ quan thuế có thể xác định đây **không phải 2 hợp đồng dịch vụ độc lập** mà là **quan hệ lao động thực chất được ngụy trang** — căn cứ BLLĐ 45/2019 Điều 3 khoản 1 và Điều 13 khoản 2: nguyên tắc *"nhìn vào thực chất — không nhìn vào tên gọi hợp đồng"*.

#### 26.4.2. Hệ quả pháp lý nếu bị xác định là quan hệ lao động

| Khoản truy thu / phạt | Tỷ lệ / Mức | Tính trên |
|---|:---:|---|
| BHXH phần NLĐ | 10,5% | Tổng thu nhập toàn bộ thời gian hợp tác |
| BHXH phần NSDLĐ (CTM) | 22% | Tổng thu nhập toàn bộ thời gian hợp tác |
| BHYT + BHTN | ~5,5% | Tổng thu nhập toàn bộ thời gian hợp tác |
| Lãi chậm nộp BHXH | 0,03%/ngày | Từ thời điểm phát sinh nghĩa vụ — NĐ 158/2025 |
| Phạt hành chính | 12–20% số tiền trốn đóng | Theo NĐ 12/2022/NĐ-CP |
| TNCN truy thu | Biểu lũy tiến 5–35% thay vì 10% khoán | Toàn bộ thu nhập (cả thuê xe + dạy học) gộp lại |
| CP thuê xe bị loại | Toàn bộ | Do bị xác định là thù lao lao động ngụy trang |

*Ví dụ minh họa:* Cá nhân nhận 15 triệu/tháng × 24 tháng = 360 triệu → CTM bị truy thu ~38% × 360 triệu = **~137 triệu tiền BHXH + lãi phạt + phạt hành chính**.

#### 26.4.3. Ba phương án xử lý — Kế toán trưởng lựa chọn và ký xác nhận

| PA | Nội dung | Ưu điểm | Hạn chế |
|:---:|---|---|---|
| **A** — An toàn nhất | Bên B chỉ cho thuê xe *(ĐTCX)*, **không** ký PL B *(GVLK)* — hoặc ngược lại | Không có rủi ro pháp lý | Hạn chế linh hoạt hợp tác |
| **B** — Khuyến nghị | Yêu cầu Bên B thành lập HKD/ĐKKD trước khi ký HĐ. Cả 2 vai trò gộp vào DT HKD — quan hệ kinh doanh rõ ràng | Hợp lý pháp lý; có chứng từ đầy đủ | Bên B phải chủ động ĐKKD |
| **C** — Rủi ro vẫn còn | Giữ 2 hợp đồng riêng nhưng tuân thủ **5 điều kiện bắt buộc** tại Điều 26.4.4 | Linh hoạt, phổ biến trong ngành | Rủi ro vẫn tồn tại nếu bị thanh tra kỹ |

> Kế toán trưởng chọn Phương án C: phải lập tờ trình TGĐ phê duyệt và lưu văn bản ghi nhận rủi ro có chữ ký TGĐ trước khi hợp đồng có hiệu lực.

#### 26.4.4. Năm điều kiện bắt buộc khi áp dụng Phương án C

| ☑ | Điều kiện | Chứng từ kiểm soát |
|:---:|---|---|
| ☐ | Xe phải được nhiều GV khác nhau sử dụng luân phiên — không chỉ 1 người | BM-NKX ghi tên nhiều GV khác nhau trong tháng |
| ☐ | Tiền thuê xe cố định theo tháng/quý — không phụ thuộc số giờ cá nhân Bên B dạy | PL F ghi giá cố định; thanh toán đúng mức cố định |
| ☐ | Thù lao giảng dạy tính theo HV hoàn thành — không phải giờ công lao động | PL B ghi đơn giá/HV hoàn thành và DAT; quyết toán theo BM-07 |
| ☐ | Không ghi trong bất kỳ văn bản nào rằng Bên B dạy trên xe của chính mình | Kế toán công nợ kiểm tra toàn bộ hồ sơ trước khi lưu |
| ☐ | Lưu trữ bổ sung: *(i)* DS GV khác sử dụng xe; *(ii)* Bằng chứng xe hoạt động khi Bên B không dạy | Nhật ký xe BM-NKX + lịch phân công GV tách biệt |

#### 26.4.5. Quy trình phát hiện và xử lý kiêm nhiệm

```
Kế toán công nợ kiểm tra trước mỗi kỳ ký PL mới:
BƯỚC 1 — Lấy DS ĐTCX hiện tại (đang cho CTM thuê xe)
BƯỚC 2 — Đối chiếu với DS GVLK hiện tại (đang ký PL B)
BƯỚC 3 — Nếu cùng 1 cá nhân xuất hiện trong CẢ HAI DS → GẮN CỜ KIÊM NHIỆM
BƯỚC 4 — Chuyển hồ sơ lên Kế toán trưởng → quyết định PA A/B/C
BƯỚC 5 — KHÔNG thanh toán tiền thuê xe cho cá nhân kiêm nhiệm
          cho đến khi có quyết định của Kế toán trưởng
```

### 26.5. Checklist quy trình nhận diện nhanh vãng lai

Vãng lai *(không có HĐ HTLK)* áp dụng cùng tỷ lệ hoa hồng Bậc 0; không có tạm ứng; không có thưởng KPI. Kế toán công nợ phải thu thập đủ hồ sơ sau **trước khi chi**:

| ☑ | Hồ sơ bắt buộc |
|:---:|---|
| ☐ | CCCD còn hiệu lực của người nhận *(bản sao)* |
| ☐ | MST cá nhân của người nhận |
| ☐ | Số tài khoản ngân hàng của người nhận |
| ☐ | DS HV do người này giới thiệu — xác nhận Phòng Đào tạo |
| ☐ | Kế toán trưởng phê duyệt |

> *Không thu thập được CCCD và MST: **KHÔNG CHI hoa hồng**. Chi phí không có chứng từ thuế đầy đủ sẽ bị loại khỏi CP được trừ TNDN — Luật TNDN 67/2025 Điều 9.*

---

## Phụ lục — Danh mục biểu mẫu áp dụng Phần 4

| Mã | Tên biểu mẫu | Người lập | Lưu trữ |
|---|---|---|---|
| **PL05** | Cam kết doanh thu năm | Bên B lập + ký | Kế toán công nợ — cập nhật 31/01 hàng năm |
| **PL06** | Bảng kê dịch vụ thay hóa đơn | Bên B lập | Kế toán công nợ — tối thiểu 10 năm |
| **BM-07** | Biên bản nghiệm thu nội bộ | Phòng Đào tạo | Kế toán + Phòng ĐT — tối thiểu 10 năm |
| **BM-NKX** | Nhật ký vận hành xe | Bộ phận Phương tiện | Bộ phận PT — tối thiểu 5 năm *(quản lý nội bộ, không phải căn cứ TT tiền thuê xe)* |
| **BM-BKX** | Bảng kiểm xe bàn giao/hoàn trả | Bộ phận PT + Bên B | Kế toán + BP PT — tối thiểu 5 năm |
| **PL08** | Bảng định mức nhiên liệu | Kế toán trưởng ban hành | Kế toán + BP Phương tiện |
| **BBXN-HV** | Biên bản xác nhận DS HV *(kèm PL CK)* | Phòng ĐT + Bên B | Kế toán — tối thiểu 10 năm |
| **ĐM-HH** | Bảng định mức hoa hồng nội bộ | Kế toán trưởng trình | TGĐ phê duyệt — lưu nội bộ, không phát hành |

---

*— Hết Phần 4 — Phiên bản 2.0*

> 🔗 **Xem tiếp:** P5 · Giá thành – Giá vốn – Kết quả kinh doanh

*Cập nhật 05/2026 · Phòng Tài chính – Kế toán CTM*  
*Căn cứ cập nhật: HĐ HTLK v1.0; PL A→F v1.0; PLCK v1.0; QT-ĐTLK v1.0; NĐ 94/2026; NĐ 141/2026; NĐ 174/2025; BLLĐ 45/2019 Điều 13; Luật 109/2025; TT 50/2026*
