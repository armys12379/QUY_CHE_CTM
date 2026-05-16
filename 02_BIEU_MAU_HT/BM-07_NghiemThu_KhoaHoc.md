# BM-07 — BIÊN BẢN NGHIỆM THU KHÓA HỌC ĐÀO TẠO LÁI XE

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-07 |
| **Tên biểu mẫu** | BIÊN BẢN NGHIỆM THU KHÓA HỌC ĐÀO TẠO LÁI XE |
| **Căn cứ pháp lý** | NQ-HĐQT Điều 5.3 · TT 14/2025/TT-BXD · NĐ 94/2026/NĐ-CP |
| **Người sử dụng** | Phòng ĐT · GVLK/VPTS · GĐĐH · KT trưởng |
| **Tần suất** | Từng khóa học |

> 🔒 **CẢNH BÁO (A6):** BM-07 là **chứng từ gốc bắt buộc** — Thiếu BM-07 có chữ ký GĐĐH: KT **KHÔNG** ghi nhận DT TK 5113A, **KHÔNG** quyết toán NL TK 141, **KHÔNG** thanh toán GVLK/VPTS.

> **Màu sắc tiêu đề:** Dòng 1–2 nền xanh nhạt `#D6E4F0`, chữ xanh đậm `#1F4D78`, in đậm.

---

## 2. PHẦN 1 — THÔNG TIN CHUNG (A7:D17)

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Số BM-07 | D8 | `……/BM-07/……` |
| Ngày lập | D9 | `……/……/……` |
| Mã khóa học | _(ô trống, A10)_ | _(nhập tay)_ |
| Ngày khai giảng | _(ô trống, A11)_ | _(nhập tay)_ |
| Hạng GPLX | D12 | `⬜ B  ⬜ C1  ⬜ C2  ⬜ C  ⬜ D1  ⬜ D2  ⬜ D  ⬜ Nâng hạng: ___ → ___` |
| Ngày kết thúc | _(ô trống, A13)_ | _(nhập tay)_ |
| Nguồn tuyển sinh | D14 | `⬜ Trực tiếp (TT)  ⬜ VPLK  ⬜ GVLK  ⬜ Pháp nhân (PN)` |
| Mã ĐTLK | _(ô trống, A15)_ | _(nhập tay)_ |
| Người lập | _(ô trống, A16)_ | _(nhập tay)_ |
| Bộ phận | D17 | `Phòng Đào tạo` _(cố định)_ |

---

## 3. PHẦN 2 — DANH SÁCH HỌC VIÊN HOÀN THÀNH CHƯƠNG TRÌNH ĐÀO TẠO

> **Điều kiện hoàn thành (TT 14/2025/TT-BXD):** ✅ Đủ số giờ lý thuyết · ✅ Đủ số giờ TH sân tập · ✅ Đủ số km đường trường

### Cấu trúc bảng (A21:J37)

| Cột | Tên cột | Loại |
|---|---|---|
| A | STT | Số thứ tự (1–15) |
| B | Họ và tên | Nhập tay |
| C | CCCD | Nhập tay |
| D | Giờ LT Thực tế | Nhập tay |
| E | Giờ LT Theo QĐ | Nhập tay |
| F | Giờ TH sân Thực tế | Nhập tay |
| G | Giờ TH sân Theo QĐ | Nhập tay |
| H | Km đường Thực tế | Nhập tay |
| I | Km đường Theo QĐ | Nhập tay |
| J | Kết quả | `⬜ Đạt  ⬜ Chưa đạt` |

- **Số dòng HV:** 15 dòng (dòng 22–36)

### Dòng tổng (dòng 37) — **In đậm**

| Cột | Công thức |
|---|---|
| C37 | `=COUNTIF(J22:J36,"*Đạt*")&" HV hoàn thành"` |

---

## 4. PHẦN 3A — PHƯƠNG TIỆN SỞ HỮU (NĐ 94/2026/NĐ-CP)

### Cấu trúc bảng (A40:I43)

| Cột | Tên cột | Giá trị mặc định |
|---|---|---|
| A | Biển số xe | Nhập tay |
| B | Hạng xe | Nhập tay |
| C | Năm SX | Nhập tay |
| D | Niên hạn còn lại | `…… năm` |
| E | Kiểm định còn HL | `⬜ Có  ⬜ Không` |
| F | Bảo hiểm còn HL | `⬜ Có  ⬜ Không` |
| G | Số giờ khóa này | Nhập tay |
| H | Số km khóa này | Nhập tay |
| I | Tình trạng | `⬜ Đạt  ⬜ Không` |

- **Số dòng xe:** 3 dòng (41–43)

---

## 5. PHẦN 3B — PHƯƠNG TIỆN THUÊ ĐỐI TÁC LIÊN KẾT

### Cấu trúc bảng (A46:I49)

| Cột | Tên cột | Ghi chú so với 3A |
|---|---|---|
| A | Biển số xe | |
| B | Hạng xe | |
| C | **Tên ĐTLK** | _(thay cho "Năm SX")_ |
| D | Niên hạn còn lại | `…… năm` |
| E | Kiểm định còn HL | `⬜ Có  ⬜ Không` |
| F | Bảo hiểm còn HL | `⬜ Có  ⬜ Không` |
| G | Số giờ khóa này | |
| H | Số km khóa này | |
| I | Tình trạng | `⬜ Đạt  ⬜ Không` |

- **Số dòng xe:** 3 dòng (47–49)

---

## 6. PHẦN 4 — QUYẾT TOÁN GVLK / VPTS

### Cấu trúc bảng (A52:H59)

| Cột | Tên cột | Loại |
|---|---|---|
| A | Họ và tên GVLK/VPTS | Nhập tay |
| B | MST / CCCD | Nhập tay |
| C | Hình thức | `⬜① ⬜② ⬜③ ⬜④` |
| D | Số giờ / Số HV | Nhập tay |
| E | Đơn giá khoán (đ) | Nhập tay |
| F | Tổng trước thuế (đ) | Công thức: `=E*D` |
| G | Thuế TNCN khấu trừ (đ) | Nhập tay |
| H | Thực nhận (đ) | Công thức: `=F-G` |

- **Số dòng GVLK:** 6 dòng (53–58)

### Hình thức thanh toán

| Ký hiệu | Mô tả |
|---|---|
| ① | GV cơ hữu |
| ② | Cá nhân không ĐKKD (khấu trừ 10% TNCN) |
| ③ | Cá nhân KD / HKD / Pháp nhân (xuất hóa đơn) |
| ④ | Thỉnh giảng |

### Dòng tổng cộng (dòng 59) — **In đậm**

| Cột | Công thức |
|---|---|
| F59 | `=SUM(F53:F58)` |
| G59 | `=SUM(G53:G58)` |
| H59 | `=SUM(H53:H58)` |

---

## 7. PHẦN 5 — XÁC NHẬN CÁC BÊN

Nền ô: `#F2F2F2` · Chữ đen · In đậm

| Vị trí (Excel) | Chức danh | Nội dung |
|---|---|---|
| A63–A65 | **NGƯỜI LẬP (Phòng Đào tạo)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| D63–D65 | **ĐẠI DIỆN GVLK/VPTS** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| G63–G65 | **BỘ PHẬN PHƯƠNG TIỆN** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| J63–J65 | **TRƯỞNG PHÒNG ĐÀO TẠO** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 8. PHẦN 6 — PHÊ DUYỆT — GIÁM ĐỐC ĐIỀU HÀNH (A69:D74)

| Trường | Vị trí | Nội dung |
|---|---|---|
| Họ và tên | A70 | _(nhập tay)_ |
| Kết luận | D71 | `⬜ Xác nhận đủ điều kiện  ⬜ Chưa đủ — Lý do: ___` |
| Chữ ký | A72 | _(ký tay)_ |
| Ngày ký | D73 | `……/……/……` |

> 📌 **Lưu ý A74:** GĐĐH chỉ ký nghiệm thu **chuyên môn đào tạo** — **KHÔNG** phê duyệt chi tài chính (NQ-HĐQT Điều 5.3). Lưu trữ tối thiểu **10 năm**.

---

## 9. LIÊN KẾT BIỂU MẪU

```
BM-07 (đầu ra) ──► KT ghi nhận DT TK 5113A
BM-07 (đầu ra) ──► Quyết toán NL TK 141
BM-07 (đầu ra) ──► Thanh toán GVLK/VPTS
BM-07 ──► BM-09 (số HV hoàn thành)
BM-07 ──► BM-10 (giá thành khóa học)
BM-12 ──► BM-07 (kèm khi CP vượt định mức)
```

---

## 10. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM_6_7_10_11_12.xlsx` |
| Sheet | `BM-07 Nghiệm thu khóa học` |
| Vùng dữ liệu | `A1:L74` |
| Số dòng | 74 · Số cột: 12 (A–L) |
