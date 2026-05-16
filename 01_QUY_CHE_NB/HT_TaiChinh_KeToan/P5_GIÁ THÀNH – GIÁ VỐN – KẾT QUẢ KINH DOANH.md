# P5- GIÁ THÀNH – GIÁ VỐN – KẾT QUẢ KINH DOANH

> 📄 **Thuộc:** [🏛️ HỆ THỐNG QUẢN LÝ TÀI CHÍNH - KẾ TOÁN](https://www.notion.so/H-TH-NG-QU-N-L-T-I-CH-NH-K-TO-N-352971b95929817199cfda90f8284930?pvs=21)
> 

> 🔗 **Xem trước:** [🤝 P4 · Quan hệ tài chính với đối tác liên kết](https://www.notion.so/P4-QUAN-H-T-I-CH-NH-V-I-I-T-C-LI-N-K-T-352971b95929819ca9e3f8123a5ea565?pvs=21) | **Xem tiếp:** [📊 P6 · Báo cáo tài chính](https://www.notion.so/P6-B-o-c-o-t-i-ch-nh-352971b9592981d6b2ffd87c3847443c?pvs=21)
> 
> 
> **Phần này gồm 10 điều:**
> 
- Điều 27. Nguyên tắc tập hợp chi phí và xác định đối tượng giá thành
- Điều 28. Hệ thống tài khoản và mã đối tượng chi phí
- Điều 29. Tập hợp chi phí trực tiếp theo đối tượng
- Điều 30. Phân bổ chi phí chung
- Điều 31. Chi phí sản xuất kinh doanh dở dang
- Điều 32. Tính giá thành theo từng nhóm hoạt động
- Điều 33. Kết chuyển giá vốn — TK 154 → TK 632
- Điều 34. Xác định kết quả kinh doanh
- Điều 35. Bộ báo cáo quản trị giá thành và KQKD
- Điều 36. Kiểm soát, phê duyệt và lưu trữ hồ sơ giá thành

---

## Điều 27. Nguyên tắc tập hợp chi phí và xác định đối tượng giá thành

### 27.1. Nguyên tắc phù hợp giữa doanh thu và chi phí

Chi phí được tập hợp và ghi nhận **tương ứng với doanh thu mà nó tạo ra**, không căn cứ vào thời điểm thanh toán *(Điều 6 Luật Kế toán 2015; Điều 8 Luật 67/2025/QH15)*:

| Thời điểm | Ghi nhận chi phí | Ghi nhận doanh thu |
| --- | --- | --- |
| Trong khóa học đang thực hiện | Tập hợp vào **TK 154A** *(chi phí SXKD dở dang đào tạo)* — chưa kết chuyển giá vốn | Chưa ghi nhận doanh thu TK 5113A *(đang ở TK 33872)* |
| Học viên hoàn thành khóa | Kết chuyển **TK 154A → TK 632A** *(giá vốn đào tạo)* | Kết chuyển **TK 33872 → TK 5113A** *(doanh thu đào tạo)* |
| Hoạt động cho thuê/sát hạch | Tập hợp TK 154B riêng theo từng kỳ/hợp đồng | Ghi nhận TK 5113B theo tiến độ dịch vụ |

> ⚠️ **Nguyên tắc đồng bộ bắt buộc:** Kỳ kết chuyển giá vốn TK 154A/B → TK 632A/B phải trùng với kỳ ghi nhận doanh thu TK 5113A/5113B tương ứng.
> 

### 27.2. Ba nhóm đối tượng tính giá thành

Nguồn tuyển sinh là chiều phân tích quản trị, không làm thay đổi đối tượng tính giá thành chính theo hạng GPLX.

| Nhóm | Đối tượng | Đơn vị tính | Mã ví dụ |
| --- | --- | --- | --- |
| **Nhóm 1** | Đào tạo lái xe — theo **nguồn tuyển sinh × hạng GPLX** | 01 học viên hoàn thành khóa | `TT_B2`, `TT_C`, `VPLK_B2`, `GVLK_C` |
| **Nhóm 2** | Cho thuê/vận hành xe đào tạo — theo **nhóm xe × hạng GPLX** | 01 giờ quy đổi | `XE_DT_B1`, `XE_DT_B2`, `XE_DT_C` |
| **Nhóm 3** | Cho thuê/vận hành xe sát hạch — theo **nhóm xe × hạng GPLX** | 01 giờ quy đổi | `XE_SH_B2`, `XE_SH_C` |

> 📌 **Nguồn tuyển sinh** là cấp phân loại thứ nhất của Nhóm 1 — giúp đánh giá hiệu quả chi phí theo từng kênh: TT *(Trung tâm trực tiếp)*, VPLK *(Văn phòng liên kết)*, GVLK *(Giáo viên liên kết nhận khoán trọn gói)*. Chi phí dùng chung cho nhiều nguồn cùng hạng phân bổ theo số học viên hoàn thành từng nguồn trong kỳ.
> 

### 27.3. Kỳ tính giá thành

Kỳ tính giá thành là **tháng hoặc quý** — Giám đốc quyết định áp dụng thống nhất cho toàn bộ năm tài chính. Nếu thay đổi kỳ tính giữa năm phải có tờ trình Kế toán trưởng, phê duyệt của Giám đốc và thuyết minh trong báo cáo tài chính.

### 27.4. Điều kiện đưa chi phí vào giá thành

Chi phí chỉ được đưa vào giá thành khi **đồng thời** đáp ứng:

- ① Thực tế phát sinh phục vụ hoạt động SXKD *(Điều 14 P3)*
- ② Có chứng từ hợp lệ *(hóa đơn điện tử / chứng từ được phép thay thế)*
- ③ Khoản ≥ 5 triệu đồng đã thanh toán chuyển khoản *(NĐ 320/2025)*
- ④ Đúng đối tượng chi phí đã xác định *(Điều 28)*
- ⑤ Đã được Kế toán trưởng kiểm tra và phê duyệt đưa vào giá thành

> ⚠️ Chi phí không đủ điều kiện phải **tách riêng** vào TK 811 *(chi phí không được trừ)* — không được đưa vào TK 154 hoặc TK 632.
> 

---

## Điều 28. Hệ thống tài khoản và mã đối tượng chi phí

### 28.1. Sơ đồ luồng tài khoản

```
TK 621 ──┐
TK 622 ──┼──→  TK 154  ──→  TK 632  ──→  TK 911
TK 627 ──┘     (dở dang)    (giá vốn)    (KQKD)
                  ↑
            Phân bổ từ:
            TK 641 (bán hàng) ──→ TK 911 trực tiếp
            TK 642 (QLDN)     ──→ TK 911 trực tiếp
```

> 📌 **TK 641 và TK 642 không đi qua TK 154** — kết chuyển thẳng vào TK 911 cuối kỳ, không tính vào giá thành.
> 

### 28.2. Chi tiết tài khoản cấp 2 theo hoạt động

| TK | Tên | Hoạt động | Ghi chú |
| --- | --- | --- | --- |
| **TK 154A** | CP SXKD dở dang — Đào tạo lái xe | Nhóm 1 | Chi tiết theo mã `[Nguồn]_[Hạng]` |
| **TK 154B** | CP SXKD dở dang — Cho thuê xe đào tạo | Nhóm 2 | Chi tiết theo mã `XE_DT_[Hạng]` |
| **TK 154B** | CP SXKD dở dang — Cho thuê xe sát hạch | Nhóm 3 | Chi tiết theo mã `XE_SH_[Hạng]` |
| **TK 154C** | CP SXKD dở dang — Hoạt động sát hạch | Riêng | Chi tiết theo từng kỳ sát hạch |
| **TK 632A** | Giá vốn — Đào tạo lái xe | Nhóm 1 | Đối chiếu với TK 5113A |
| **TK 632B** | Giá vốn — Cho thuê xe đào tạo | Nhóm 2 | Đối chiếu với TK 5113B |
| **TK 632B** | Giá vốn — Cho thuê xe sát hạch | Nhóm 3 | Đối chiếu với TK 5113B |
| **TK 632C** | Giá vốn — Hoạt động sát hạch | Riêng | Đối chiếu với TK 5113B |

### 28.3. Mã đối tượng chi phí — quy ước đặt tên

| Cấu trúc mã | Ý nghĩa | Ví dụ |
| --- | --- | --- |
| `[Nguồn]_[Hạng]` | Nhóm 1 — Đào tạo | `TT_B2`, `VPLK_C`, `GVLK_B2` |
| `XE_DT_[Hạng]` | Nhóm 2 — Xe đào tạo | `XE_DT_B1`, `XE_DT_C` |
| `XE_SH_[Hạng]` | Nhóm 3 — Xe sát hạch | `XE_SH_B2`, `XE_SH_C` |
| `SH_[Kỳ]` | Hoạt động sát hạch | `SH_Q1_2026`, `SH_T3_2026` |
| `PN_[Hạng]` | Nhóm 1 — Khoán trọn gói pháp nhân | `PN_B2`, `PN_C` |

Mỗi mã đối tượng chi phí chỉ được thuộc một nhóm hoạt động duy nhất, không được hạch toán chồng chéo giữa các nhóm.

> 📌 Danh mục mã đối tượng đầy đủ ban hành tại **Phụ lục 01 — Quy chế hạch toán kế toán nội bộ**.
> 

---

## Điều 29. Tập hợp chi phí trực tiếp theo đối tượng

> 📌 **Nguyên tắc xuyên suốt — bất biến với HT1, HT2, HT3:**
- **Nhiên liệu:** Công ty **luôn thanh toán trực tiếp hoặc ủy quyền thanh toán** cho nhà cung cấp xăng dầu. Không khoán tiền nhiên liệu. Không gộp vào đơn giá khoán. **Ngoại lệ duy nhất: HT4** — pháp nhân tự chịu toàn bộ.
- **Nhân công:** Khác nhau theo từng hình thức — xem chi tiết bên dưới.
> 

### Bảng tổng quan 4 hình thức

|  | **HT1** Tự đào tạo | **HT2** Khoán giảng dạy | **HT3** Khoán đào tạo có phương tiện | **HT4** Khoán trọn gói |
| --- | --- | --- | --- | --- |
| **Đối tác** | Nội bộ *(GV cơ hữu hoặc cá nhân khoán giảng dạy)* | Cá nhân / HKD | Cá nhân / HKD | Pháp nhân có chức năng đào tạo |
| **Nhiên liệu** | ✅ Công ty cung cấp | ✅ Công ty cung cấp | ✅ Công ty cung cấp | ❌ Pháp nhân tự lo |
| **Phương tiện** | Xe sở hữu/thuê của Công ty | Xe sở hữu/thuê của Công ty | **ĐTLK tự lo xe** | Pháp nhân tự lo |
| **Nhân công** | GV cơ hữu + khoán giảng dạy | Khoán giảng dạy | Khoán đào tạo *(GV + PT + vận hành)* | Khoán toàn bộ *(GV+PT+NL+vận hành)* |
| **TK 141** | ✅ Có *(xe thuê)* | ✅ Có *(xe thuê)* | ✅ Có *(xe của ĐTLK)* | ❌ Không |
| **Mã đối tượng** | `TT_[Hạng]` | `VPLK_[Hạng]`, `GVLK_[Hạng]` | `VPLK_[Hạng]`, `GVLK_[Hạng]` | `PN_[Hạng]` |

---

### HT1 — Tự đào tạo *(mã: `TT_[Hạng]`)*

Trung tâm tự tuyển sinh và tự tổ chức đào tạo — sử dụng GV cơ hữu hoặc giao khoán cá nhân giảng dạy.

**A. Chi phí nhiên liệu — TK 621**

*A1. Xe Công ty sở hữu — xuất kho từng ca:*

```
Nợ TK 621.[TT_Hạng]    — Theo định mức từng ca (phiếu xuất kho BM-06)
    Có TK 152          — Xuất kho nhiên liệu
```

*A2. Xe thuê từ ĐTLK — thanh toán/ủy quyền thanh toán trực tiếp NCC:*

```
Trong khóa — theo dõi qua TK 141 từng khóa:
Nợ TK 141.[TT_Hạng/khóa]   — Theo hóa đơn NCC thực tế phát sinh
    Có TK 112              — Chuyển khoản cho NCC xăng dầu

Khi khóa hoàn thành — quyết toán và thu hồi ngay:
Phần trong định mức:
Nợ TK 621.[TT_Hạng]
    Có TK 141.[TT_Hạng/khóa]

Phần vượt định mức chưa phê duyệt:
Nợ TK 811
    Có TK 141.[TT_Hạng/khóa]
```

> ⚠️ **TK 141 từng khóa = 0 ngay khi khóa kết thúc.**
> 

**B. Chi phí nhân công trực tiếp — TK 622**

*B1. Giáo viên cơ hữu biên chế:*

```
Nợ TK 622.[TT_Hạng]   — Lương trực tiếp giảng dạy
Nợ TK 3383            — BHXH phần Công ty (17,5%)
Nợ TK 3384            — BHYT phần Công ty (3%)
Nợ TK 3385            — BHTN phần Công ty (1%)
Nợ TK 3386            — BHTNLĐ phần Công ty (0,5%)
    Có TK 334         — Lương phải trả GV
    Có TK 338x        — Các khoản trích theo lương
```

*B2. Giao khoán cá nhân giảng dạy — không ĐKKD:*

```
Nợ TK 622.[TT_Hạng]   — Tổng tiền khoán trước thuế
    Có TK 3335        — Thuế TNCN khấu trừ tại nguồn (10%)
    Có TK 112         — Số tiền thực chuyển khoản
```

Chứng từ bắt buộc: BM-07 + Bảng kê giờ giảng dạy xác nhận + Chứng từ khấu trừ 06/MST.

**C. Vật tư tiêu hao, tài liệu giáo trình — TK 621**

```
Nợ TK 621.[TT_Hạng]
    Có TK 152         — Xuất kho theo phiếu xuất
```

---

### HT2 — Khoán giảng dạy *(ĐTLK cá nhân/HKD — mã: `VPLK_[Hạng]`, `GVLK_[Hạng]`)*

ĐTLK nhận khoán **phần nhân công giảng dạy** — Công ty lo phương tiện và nhiên liệu.

> 📌 **Phân biệt HT2 với HT3:** HT2: ĐTLK chỉ cung cấp giáo viên — xe và nhiên liệu đều do Công ty lo. HT3: ĐTLK cung cấp cả giáo viên + phương tiện — nhiên liệu vẫn do Công ty lo.
> 

**A. Chi phí nhiên liệu — TK 621** *(giống HT1)*

```
Xe sở hữu: Nợ TK 621.[VPLK_Hạng / GVLK_Hạng] / Có TK 152
Xe thuê ĐTLK: TK 141 → NCC → quyết toán khi khóa xong (giống HT1)
```

> ⚠️ Nghiêm cấm gộp nhiên liệu vào đơn giá khoán dưới bất kỳ hình thức nào *(HT2 và HT3)*.
> 

**B. Chi phí giao khoán — TK 622**

*B1. ĐTLK là cá nhân không ĐKKD:*

```
Nợ TK 622.[GVLK_Hạng]  — Tổng tiền khoán trước thuế
    Có TK 3335         — Thuế TNCN khấu trừ tại nguồn (10%)
    Có TK 112          — Số tiền thực chuyển khoản
```

Chứng từ: BM-07 + Hợp đồng khoán + Chứng từ khấu trừ 06/MST.

*B2. ĐTLK là cá nhân KD/HKD — dưới ngưỡng xuất HĐ:*

```
Nợ TK 622.[VPLK_Hạng / GVLK_Hạng]  — Toàn bộ giá trị hợp đồng
    Có TK 331                       — Công nợ phải trả ĐTLK
    (Không có TK 1331)
Khi thanh toán: Nợ TK 331 / Có TK 112
```

Chứng từ: BM-07 + Hợp đồng dịch vụ + Bảng kê thay HĐ *(PL 06)* + Cam kết DT năm *(PL 05)*.

*B3. ĐTLK là cá nhân KD/HKD — từ ngưỡng xuất HĐ trở lên:*

```
Nợ TK 622.[VPLK_Hạng / GVLK_Hạng]  — Giá trị dịch vụ chưa thuế
Nợ TK 1331                          — Thuế GTGT đầu vào được khấu trừ
    Có TK 331
Khi thanh toán: Nợ TK 331 / Có TK 112
```

Chứng từ: BM-07 + Hợp đồng dịch vụ + Hóa đơn GTGT điện tử + Cam kết DT năm *(PL 05)*.

*B4. ĐTLK là pháp nhân:*

```
Nợ TK 622.[VPLK_Hạng]  — Giá trị dịch vụ chưa thuế
Nợ TK 1331             — Thuế GTGT đầu vào được khấu trừ
    Có TK 331
Khi thanh toán: Nợ TK 331 / Có TK 112
```

Chứng từ: BM-07 + Hợp đồng kinh tế + Hóa đơn GTGT điện tử.

---

### HT3 — Khoán đào tạo có phương tiện *(ĐTLK tự lo xe — mã: `VPLK_[Hạng]`, `GVLK_[Hạng]`)*

ĐTLK nhận khoán đào tạo và **tự cung cấp phương tiện** *(xe tập lái)*: tự chịu chi phí khấu hao/thuê xe, bảo hiểm, sửa chữa. **Nhiên liệu vẫn do Công ty thanh toán trực tiếp hoặc ủy quyền thanh toán.**

| Điều kiện | Nội dung bắt buộc |
| --- | --- |
| **Hợp đồng** | Ghi rõ đơn giá khoán bao gồm GV + phương tiện + sửa chữa + bảo hiểm xe; nhiên liệu tính riêng do Công ty cung cấp |
| **Nhật ký xe** | ĐTLK cung cấp nhật ký vận hành xe hàng tháng |
| **Biên bản nghiệm thu** | BM-07 — bắt buộc trước mọi thanh toán |

**A. Chi phí nhiên liệu — TK 621** *(giống HT1, HT2)*

```
Xe của ĐTLK — thanh toán/ủy quyền NCC:
Nợ TK 141.[ĐTLK/khóa] / Có TK 112
Quyết toán khi khóa xong: phần trong định mức → TK 621; vượt → TK 811
```

> 📌 HT3: xe thuộc ĐTLK — Công ty không ghi nhận TK 2111 hay TK 001. Hợp đồng cần mô tả rõ xe sử dụng *(biển số, loại xe, hạng)*.
> 

**B. Chi phí giao khoán *(GV + PT + vận hành, không bao gồm NL)* — TK 622**

Xử lý thuế theo đúng tư cách pháp lý ĐTLK — giống bút toán B1→B4 của HT2. Điểm khác biệt: đơn giá khoán đã bao gồm cả phương tiện.

---

### HT4 — Khoán trọn gói *(Pháp nhân có chức năng đào tạo — mã: `PN_[Hạng]`)*

Pháp nhân **tự chịu toàn bộ** chi phí: giáo viên, phương tiện, **nhiên liệu**, vận hành. Công ty chỉ trả **phí khoán duy nhất**. Đây là hình thức **duy nhất** Công ty không cung cấp nhiên liệu.

> 📌 **Phân biệt HT3 với HT4:** HT3: ĐTLK tự lo phương tiện — nhiên liệu vẫn do Công ty cung cấp. HT4: Pháp nhân tự lo **toàn bộ kể cả nhiên liệu**.
> 

| Điều kiện | Nội dung bắt buộc |
| --- | --- |
| **Tư cách pháp lý** | Pháp nhân có giấy phép đào tạo lái xe |
| **Hợp đồng** | Ghi rõ phạm vi khoán toàn bộ GV + PT + NL + vận hành; đơn giá theo đầu HV hoàn thành |
| **Biên bản nghiệm thu** | BM-07 — bắt buộc |
| **Chứng từ** | Hóa đơn GTGT điện tử bắt buộc |
| **Thanh toán** | Chuyển khoản bắt buộc *(NĐ 320/2025)* |

**Hạch toán — TK 622:**

```
Nợ TK 622.[PN_Hạng]    — Giá trị khoán toàn bộ chưa thuế GTGT
Nợ TK 1331             — Thuế GTGT đầu vào được khấu trừ
    Có TK 331          — Công nợ phải trả pháp nhân
Khi thanh toán: Nợ TK 331 / Có TK 112
```

> ⚠️ **Chi phí nhiên liệu: không phát sinh phía Công ty.** Không có TK 621 nhiên liệu, không có TK 141, không có định mức nhiên liệu cho mã `PN_[Hạng]`.
⚠️ **Kiểm soát giá khoán:** Đơn giá khoán phải được đối chiếu với giá thành nội bộ của Trung tâm khi tự đào tạo.
> 

TK 141 phải được quyết toán theo từng khóa đào tạo trước khi thực hiện tính giá thành và kết chuyển giá vốn.

---

### Bảng tóm tắt — Chi phí trực tiếp theo 4 hình thức

| Khoản chi phí | TK | **HT1** Tự đào tạo | **HT2** Khoán giảng dạy | **HT3** Khoán đào tạo + PT | **HT4** Khoán trọn gói |
| --- | --- | --- | --- | --- | --- |
| **NL xe sở hữu** | 621 | Xuất kho TK 152 | Xuất kho TK 152 | Xuất kho TK 152 | ❌ Không |
| **NL xe thuê** | 621 | TK 141 → NCC | TK 141 → NCC | TK 141 → NCC *(xe của ĐTLK)* | ❌ Không |
| **Khấu hao xe** | 627 | TK 2141 | TK 2141 | ❌ Gộp vào khoán | ❌ Không |
| **Tiền thuê xe** | 627 | TK 331 | TK 331 | ❌ Gộp vào khoán | ❌ Không |
| **GV cơ hữu** | 622 | Lương + BHXH | ❌ Không | ❌ Không | ❌ Không |
| **Khoán cá nhân** | 622 | Khoán giảng dạy *(khấu trừ 10%)* | Khoán giảng dạy | Khoán GV + PT + vận hành | ❌ Không |
| **HKD/Pháp nhân** | 622 | ❌ Không | Khoán giảng dạy theo HĐ | Khoán GV+PT+vận hành theo HĐ | **Khoán toàn bộ** theo HĐ |
| **Vật tư, tài liệu** | 621 | Xuất kho | Xuất kho | Xuất kho | Theo HĐ |
| **TK 141?** | — | ✅ Có *(xe thuê)* | ✅ Có *(xe thuê)* | ✅ Có *(xe của ĐTLK)* | ❌ Không |
| **Hóa đơn** | — | Theo tư cách | Theo tư cách | Theo tư cách | **HĐ GTGT (bắt buộc)** |

> ⚠️ **Biên bản nghiệm thu nội bộ *(BM-07)* là điều kiện tiên quyết** — bắt buộc cho cả 4 hình thức.
> 

### 29.3. Chi phí sản xuất chung — TK 627 *(chỉ phát sinh với HT1 và HT2)*

> 📌 HT3: khấu hao xe và tiền thuê xe đã gộp vào đơn giá khoán — không phát sinh TK 627. HT4: toàn bộ chi phí vận hành thuộc về pháp nhân — không phát sinh TK 627.
> 

**A. Khấu hao xe tập lái sở hữu *(HT1, HT2)*:**

```
Nợ TK 627.[TT_Hạng / VPLK_Hạng / GVLK_Hạng]
    Có TK 2141  — Hao mòn lũy kế TSCĐ hữu hình

Khấu hao phân bổ cho mã [X] =
    (Giờ/km thực tế mã [X] / Tổng giờ/km vận hành toàn đội xe trong kỳ)
    × Tổng khấu hao kỳ
```

**B. Tiền thuê xe từ ĐTLK *(HT1, HT2)*:**

```
Nợ TK 627.[TT_Hạng / VPLK_Hạng / GVLK_Hạng]
    Có TK 331   — Công nợ thuê xe theo hợp đồng
Khi thanh toán: Nợ TK 331 / Có TK 112 (bắt buộc nếu ≥5 triệu)
```

**C. Bảo dưỡng, sửa chữa thường xuyên *(HT1, HT2)*:**

```
Nợ TK 627.[mã đối tượng] / Có TK 112/331
```

**D. Bảo hiểm xe — phân bổ từ TK 242 *(HT1, HT2)*:**

```
Khi mua: Nợ TK 242 / Có TK 112
Phân bổ hàng tháng: Nợ TK 627.[mã đối tượng] / Có TK 242
```

**E. Điện, nước, vận hành sân tập — phân bổ *(HT1, HT2)*:**

```
Nợ TK 627.[mã đối tượng]  — Theo tỷ lệ doanh thu hoặc giờ sử dụng
    Có TK 331/112
```

---

## Điều 30. Phân bổ chi phí chung

### 30.1. Nguyên tắc phân bổ

Chi phí dùng chung cho nhiều đối tượng phải phân bổ theo **tiêu thức hợp lý, có thể giải trình và nhất quán** giữa các kỳ.

### 30.2. Tiêu thức phân bổ theo từng loại chi phí

| Loại chi phí chung | Tiêu thức phân bổ ưu tiên | Tiêu thức thay thế |
| --- | --- | --- |
| Khấu hao xe sử dụng đa mục đích | Giờ/km vận hành thực tế theo từng hoạt động | Doanh thu từng hoạt động |
| Điện, nước sân tập dùng chung | Giờ sử dụng thực tế theo từng hoạt động | Doanh thu từng hoạt động |
| Chi phí bảo trì sân tập, phòng học | Số học viên/lượt sử dụng | Doanh thu từng hoạt động |
| Lương giáo viên dạy cả nhiều hạng | Số giờ giảng dạy theo từng hạng | Số học viên từng hạng |
| Chi phí dùng chung nhiều nguồn tuyển sinh cùng hạng | Số học viên hoàn thành từng nguồn | Doanh thu từng nguồn |

### 30.3. Bảng phân bổ chi phí chung — bắt buộc mỗi kỳ

```
Nợ TK 154.[mã đối tượng]  — Theo kết quả bảng phân bổ
    Có TK 627             — Kết chuyển chi phí SXC đã tập hợp trong kỳ
```

---

## Điều 31. Chi phí sản xuất kinh doanh dở dang

### 31.1. Xác định học viên/đối tượng dở dang

| Chỉ tiêu | Nguồn dữ liệu |
| --- | --- |
| Số học viên dở dang đầu kỳ | Bảng dở dang kỳ trước *(BM-P5-03)* |
| Số học viên phát sinh trong kỳ | Phòng Đào tạo cung cấp — chậm nhất ngày 5 tháng sau |
| Số học viên hoàn thành khóa trong kỳ | Biên bản hoàn thành khóa + BM-P5-01 |
| Số học viên dở dang cuối kỳ | = Đầu kỳ + Phát sinh − Hoàn thành |

Việc xác định số học viên dở dang phải phù hợp với dữ liệu đào tạo thực tế do Phòng Đào tạo cung cấp.

> 📌 Học viên đã hoàn thành đủ giờ đào tạo được tính là **hoàn thành khóa** — bất kể kết quả sát hạch đạt hay không đạt.
> 

### 31.2. Đánh giá chi phí dở dang cuối kỳ

```
Chi phí dở dang cuối kỳ =
    (Chi phí dở dang đầu kỳ + Chi phí phát sinh trong kỳ)
    × (Số học viên dở dang cuối kỳ / Tổng số học viên trong kỳ)
```

### 31.3. Chi phí tính giá thành

```
Chi phí tính giá thành = CP dở dang đầu kỳ + CP phát sinh kỳ − CP dở dang cuối kỳ
```

---

## Điều 32. Tính giá thành theo từng nhóm hoạt động

### 32.1. Nhóm 1 — Giá thành đào tạo lái xe

```
Giá thành 1 học viên hoàn thành [Nguồn_Hạng] =
    (CP dở dang đầu kỳ + CP phát sinh trong kỳ − CP dở dang cuối kỳ)
    ÷ Số học viên hoàn thành khóa trong kỳ
```

**Bảng cấu trúc giá thành đào tạo — ví dụ mã `TT_B2`:**

| Khoản mục chi phí | TK | CP dở dang đầu kỳ | CP phát sinh kỳ | CP dở dang cuối kỳ | CP tính GT |
| --- | --- | --- | --- | --- | --- |
| Nhiên liệu | 621 |  |  |  |  |
| Giao khoán GVLK | 622 |  |  |  |  |
| Lương GV cơ hữu | 622 |  |  |  |  |
| Khấu hao xe | 627 |  |  |  |  |
| Tiền thuê xe | 627 |  |  |  |  |
| Sửa chữa, bảo dưỡng | 627 |  |  |  |  |
| Chi phí SXC khác | 627 |  |  |  |  |
| **Tổng cộng** |  |  |  |  |  |
| Số học viên hoàn thành |  |  |  |  |  |
| **Giá thành / học viên** |  |  |  |  | **=** |

### 32.2. Nhóm 2 — Giá thành giờ hoạt động xe đào tạo

```
Giá thành 1 giờ quy đổi [XE_DT_Hạng] =
    Tổng chi phí tập hợp cho nhóm xe trong kỳ
    ÷ Tổng số giờ quy đổi thực tế của nhóm xe trong kỳ

Quy đổi km → giờ:
Giờ quy đổi = (Số km thực tế × Đơn giá thuê/km) ÷ Đơn giá thuê/giờ
```

### 32.3. Nhóm 3 — Giá thành giờ hoạt động xe sát hạch

```
Giá thành 1 giờ quy đổi [XE_SH_Hạng] =
    Tổng chi phí xe sát hạch tập hợp trong kỳ
    ÷ Tổng số giờ quy đổi hoạt động sát hạch trong kỳ
```

### 32.4. Hoạt động sát hạch — giá vốn theo kỳ

```
Giá vốn kỳ sát hạch [SH_Kỳ] =
    CP nhân sự phục vụ sát hạch (TK 622)
    + CP thuê CSVC/thiết bị sát hạch (TK 627)
    + CP giá thành xe sát hạch phân bổ (từ Nhóm 3)
    + CP vận hành thiết bị chấm điểm (TK 627)
```

---

## Điều 33. Kết chuyển giá vốn — TK 154 → TK 632

### 33.1. Điều kiện kết chuyển

Chỉ được kết chuyển giá vốn khi **đồng thời**:
- ① Học viên đã hoàn thành đủ giờ đào tạo theo **TT 14/2025/TT-BXD** *(khóa khai giảng từ 01/09/2025)* hoặc **TT 35/2024/TT-BGTVT** *(khóa khai giảng trước 01/09/2025)* — có xác nhận Phòng Đào tạo
- ② Biên bản nghiệm thu nội bộ *(BM-07)* đã ký đầy đủ
- ③ Bảng tính giá thành *(BM-P5-04)* đã được Kế toán trưởng duyệt
- ④ Kỳ kết chuyển giá vốn = Kỳ ghi nhận doanh thu TK **5113A** tương ứng

Việc kết chuyển giá vốn không được thực hiện khi chưa đủ điều kiện ghi nhận doanh thu.

### 33.2. Bút toán kết chuyển giá vốn

```
Nhóm 1 — Đào tạo:
Nợ TK 632A   — Giá vốn đào tạo = Giá thành/HV × Số HV hoàn thành
    Có TK 154A

Nhóm 2 — Cho thuê xe đào tạo:
Nợ TK 632B   — Giá vốn = Giá thành/giờ × Số giờ quy đổi đã cung cấp
    Có TK 154B

Nhóm 3 — Cho thuê xe sát hạch:
Nợ TK 632B   — Giá vốn = Giá thành/giờ × Số giờ quy đổi sát hạch
    Có TK 154B

Hoạt động sát hạch:
Nợ TK 632C   — Giá vốn kỳ sát hạch
    Có TK 154C
```

### 33.3. Kiểm tra đối chiếu sau kết chuyển

| Kiểm tra | Yêu cầu |
| --- | --- |
| TK 154A/B/C còn số dư | Phải = CP dở dang cuối kỳ đã xác định |
| TK 632A kỳ này | Phải tương ứng với số học viên hoàn thành theo BM-P5-05 |
| TK 632A/B/C / TK 5113A/5113B | Tỷ lệ giá vốn/doanh thu phải trong biên độ hợp lý |

---

## Điều 34. Xác định kết quả kinh doanh

### 34.1. Cấu trúc xác định KQKD

```
KQKD = Doanh thu thuần − Giá vốn − Chi phí bán hàng − Chi phí QLDN
       + Doanh thu tài chính − Chi phí tài chính
       + Thu nhập khác − Chi phí khác
```

| Chỉ tiêu | TK | Nguồn số liệu |
| --- | --- | --- |
| Doanh thu đào tạo | TK 5113A | P2 — Ghi nhận khi HV hoàn thành khóa |
| Doanh thu sát hạch | TK 5113B | P2 — Ghi nhận theo kỳ sát hạch |
| Doanh thu cho thuê, dịch vụ khác | TK 5113B/C | P2 — Ghi nhận theo dịch vụ hoàn thành |
| Giá vốn | TK 632A/B/C | P5 — Kết chuyển từ TK 154A/B/C |
| Chi phí bán hàng | TK 641 | P3 — Hoa hồng, marketing |
| Chi phí QLDN | TK 642 | P3 — Lương BGĐ, kế toán, văn phòng |
| Doanh thu tài chính | TK 515 | Lãi tiền gửi, lãi chậm trả |
| Thu nhập khác | TK 711 | Thanh lý tài sản, bồi thường BH |
| Chi phí tài chính | TK 635 | Lãi vay, phí ngân hàng |
| Chi phí khác | TK 811 | Chi phí không được trừ, vượt định mức |

### 34.2. Bút toán cuối kỳ — kết chuyển xác định KQKD

```
Kết chuyển doanh thu:
Nợ TK 5111/5112/5113/515/711
    Có TK 911

Kết chuyển chi phí:
Nợ TK 911
    Có TK 632A/B/C, 641, 642, 635, 811

Xác định lợi nhuận (lãi):
Nợ TK 911 / Có TK 421

Xác định lợi nhuận (lỗ):
Nợ TK 421 / Có TK 911
```

### 34.3. Thuế thu nhập doanh nghiệp

```
Thuế TNDN tạm tính hàng quý:
Nợ TK 8211   — Chi phí thuế TNDN hiện hành
    Có TK 3334   — Thuế TNDN phải nộp (tạm tính = Lợi nhuận kế toán × 20%)

Khi nộp:
Nợ TK 3334 / Có TK 112
```

> 📌 Thuế TNDN tạm tính theo **quý** — chậm nhất ngày 30 tháng đầu quý tiếp theo. Quyết toán năm chậm nhất **31/3 năm sau**. Căn cứ Luật 67/2025/QH15.
> 

---

## Điều 35. Bộ báo cáo quản trị giá thành và KQKD

### 35.1. Báo cáo bắt buộc hàng kỳ *(tháng/quý)*

| # | Tên báo cáo | Biểu mẫu | Người lập | Người duyệt | Hạn nộp |
| --- | --- | --- | --- | --- | --- |
| 1 | Báo cáo kết quả đào tạo kỳ | **BM-P5-01** | Phòng ĐT | GĐĐH hoặc PGĐ đào tạo | 05 NLV sau kỳ SH · 10 NLV cuối năm |
| 2 | Bảng tổng hợp chi phí theo khóa/hạng/hoạt động | **BM-P5-02** | KT tổng hợp | KT trưởng | Ngày 5 tháng sau |
| 3 | Bảng xác định chi phí dở dang đầu/cuối kỳ | **BM-P5-03** | KT tổng hợp | KT trưởng | Ngày 5 tháng sau |
| 4 | Bảng tính giá thành theo học viên hoàn thành | **BM-P5-04** | KT tổng hợp | KT trưởng | Ngày 7 tháng sau |
| 5 | Bảng xác định giá vốn theo từng hoạt động | **BM-P5-05** | KT tổng hợp | TGĐ hoặc PGĐ TC | Ngày 7 tháng sau |
| 6 | Báo cáo chi phí bất thường/vượt định mức | **BM-P5-06** | Người phát hiện | KT trưởng / TGĐ | Ngay khi phát sinh |

Hiệu quả theo đối tác liên kết: Giá thành, doanh thu và lợi nhuận theo từng đối tác (P4)

### 35.2. Báo cáo quản trị cho Ban Giám đốc

**Hàng tháng** *(chậm nhất ngày 10 tháng sau)*:

| Báo cáo | Nội dung |
| --- | --- |
| **Lãi/lỗ theo khóa học** | Doanh thu − Giá vốn theo từng mã đối tượng; tỷ suất lợi nhuận/học viên |
| **Chi phí theo xe** | Tổng chi phí/giờ hoặc /km từng xe; so sánh với định mức |
| **Hiệu quả theo GVLK/VPTS** | Số học viên hoàn thành/GVLK; chi phí giao khoán/học viên |
| **Hiệu quả theo nguồn tuyển sinh** | Giá thành/học viên theo từng nguồn TT/VPLK/GVLK |

**Hàng quý** *(chậm nhất ngày 15 tháng đầu quý tiếp theo)*:

| Báo cáo | Nội dung |
| --- | --- |
| **KQKD tổng hợp** | Doanh thu/Giá vốn/Lợi nhuận gộp/Chi phí BH&QLDN/LNTT/Thuế TNDN/LNST |
| **Phân tích biến động giá thành** | So sánh giá thành thực tế vs định mức; nguyên nhân biến động |
| **Đối chiếu 3 chiều** | Doanh thu P2 ↔︎ Chi phí P3 ↔︎ Giá thành P5 |

### 35.3. Đối chiếu 3 chiều bắt buộc trước khi khóa sổ

| Đối chiếu | Yêu cầu |
| --- | --- |
| Tổng doanh thu TK 5113A (P2) ↔︎ Tổng giá vốn TK 632A (P5) | Tỷ lệ giá vốn/doanh thu phải trong biên độ hợp lý |
| Tổng chi phí TK 621+622+627 (P3) ↔︎ Tổng TK 154 đã kết chuyển + TK 154 dở dang | Phải bằng nhau |
| Số học viên hoàn thành (Phòng ĐT) ↔︎ Số HV tính giá thành (BM-P5-04) ↔︎ Số HV ghi nhận DT (P2) | Ba số liệu phải khớp nhau |

> ⚠️ **Nếu 3 chiều không khớp:** Dừng khóa sổ, báo cáo Kế toán trưởng ngay.
> 

---

## Điều 36. Kiểm soát, phê duyệt và lưu trữ hồ sơ giá thành

### 36.1. Phân công trách nhiệm

| Công việc | Người thực hiện | Người kiểm tra | Người phê duyệt |
| --- | --- | --- | --- |
| Tập hợp chi phí theo mã đối tượng | KT vật tư/KT tiền lương/KT công nợ | KT tổng hợp | — |
| Lập bảng phân bổ chi phí chung | KT tổng hợp | KT trưởng | KT trưởng |
| Xác định dở dang cuối kỳ | KT tổng hợp + Phòng ĐT | KT trưởng | KT trưởng |
| Tính giá thành BM-10 | KT tổng hợp | KT trưởng | KT trưởng |
| Xác định giá vốn BM-11 | KT tổng hợp | KT trưởng | TGĐ hoặc PGĐ TC |
| Kết chuyển TK 154 → TK 632 | KT tổng hợp | KT trưởng | KT trưởng |
| Kết chuyển xác định KQKD (TK 911) | KT tổng hợp | KT trưởng | KT trưởng |

### 36.2. Nghiêm cấm

- Hạch toán chi phí sai mã đối tượng nhằm điều chỉnh lợi nhuận theo từng nguồn
- Kết chuyển giá vốn sang kỳ khác không trùng kỳ ghi nhận doanh thu
- Điều chuyển chi phí giữa các mã đối tượng sau khi đã khóa sổ kỳ
- Đưa chi phí không đủ điều kiện vào TK 154 để “cất” qua kỳ sau

### 36.3. Lưu trữ hồ sơ giá thành

Bộ hồ sơ giá thành từng kỳ lưu trữ **tối thiểu 10 năm** *(Điều 41 Luật Kế toán 2015)*, bao gồm:

- **BM-P5-01:** Báo cáo kết quả đào tạo kỳ *(Phòng ĐT lập -có chữ ký GĐĐH GĐ phụ trách đào tạo)*
- **BM-P5-02:** Bảng tổng hợp chi phí theo đối tượng *(có chữ ký KT trưởng)*
- **BM-P5-03:** Bảng xác định chi phí dở dang *(có chữ ký KT trưởng)*
- **BM-P5-04:** Bảng tính giá thành *(có chữ ký KT trưởng)*
- **BM-P5-05:** Bảng xác định giá vốn *(có chữ ký TGĐ hoặc PGĐ TC)*
- **BM-P5-06:** Báo cáo chi phí bất thường *(nếu có)*
- Bảng phân bổ chi phí chung
- Biên bản đối chiếu 3 chiều trước khi khóa sổ

Lưu song song **bản cứng** *(có đủ chữ ký gốc)* và **bản điện tử** *(file PDF scan có chữ ký)*.

---

*— Hết Phần 5 —*

*Cập nhật lần cuối: 05/2026 · Phòng Tài chính – Kế toán CTM*

> 🔗 **Xem tiếp:** [📊 P6 · Báo cáo tài chính](https://www.notion.so/P6-B-o-c-o-t-i-ch-nh-352971b9592981d6b2ffd87c3847443c?pvs=21)
> 

[BM-P5-02 đến BM-P5-06 — BIỂU MẪU KẾ TOÁN GIÁ THÀNH](https://www.notion.so/BM-P5-02-n-BM-P5-06-BI-U-M-U-K-TO-N-GI-TH-NH-354971b9592980f39141fd65f027643a?pvs=21)

[BM-P5-01 — BÁO CÁO KẾT QUẢ ĐÀO TẠO KỲ](https://www.notion.so/BM-P5-01-B-O-C-O-K-T-QU-O-T-O-K-354971b95929804dac12eb6129345255?pvs=21)