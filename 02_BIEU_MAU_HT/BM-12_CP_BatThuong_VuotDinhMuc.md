# BM-12 — BÁO CÁO CHI PHÍ BẤT THƯỜNG / VƯỢT ĐỊNH MỨC

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-12 |
| **Tên biểu mẫu** | BÁO CÁO CHI PHÍ BẤT THƯỜNG / VƯỢT ĐỊNH MỨC |
| **Căn cứ pháp lý** | NQ-HĐQT Điều 5.2 (Nhóm B*) · PL08 |
| **Điều kiện bắt buộc** | Khi CP vượt định mức PL08 |
| **Người sử dụng** | Người lập · KT trưởng · PGĐ TC · TGĐ |
| **Tần suất** | Khi phát sinh |

> 🔴 **CẢNH BÁO (A6):** BM-12 là **yêu cầu bắt buộc** kèm theo mọi khoản chi Nhóm B* (vượt định mức PL08). Phê duyệt theo mức tiền tại Điều 5.2 NQ-HĐQT. **Không có BM-12 → KT từ chối hạch toán.**

---

## 2. THÔNG TIN PHIẾU (A7:D14)

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Số BM-12 | D7 | `……/BM-12/……` |
| Ngày lập | D8 | `……/……/……` |
| Người lập | _(ô trống, A9)_ | _(nhập tay)_ |
| Bộ phận | _(ô trống, A10)_ | _(nhập tay)_ |
| Mã khóa học | _(ô trống, A11)_ | _(nhập tay)_ |
| Hạng GPLX | _(ô trống, A12)_ | _(nhập tay)_ |
| Loại chi phí | D13 | `⬜ Nhiên liệu  ⬜ Nhân công GVLK  ⬜ Thuê xe  ⬜ Khác: ___` |
| Kỳ kế toán | D14 | `Tháng ……/……` |

---

## 3. PHẦN 1 — PHÂN TÍCH VƯỢT ĐỊNH MỨC

### Cấu trúc bảng (A17:J23)

| Cột | Tên cột | Loại |
|---|---|---|
| A | STT | 1–5 |
| B | Khoản mục | Nhập tay |
| C | Đơn vị | Nhập tay |
| D | Định mức (PL08) | Nhập tay |
| E | Thực tế phát sinh | Nhập tay |
| F | Chênh lệch vượt | Công thức: `=E-D` |
| G | Đơn giá (đ) | Nhập tay |
| H | Thành tiền vượt (đ) | Công thức: `=F*G` |
| I | TK kế toán | Nhập tay |
| J | Ghi chú | Nhập tay |

- **Số dòng dữ liệu:** 5 dòng (18–22)
- Dòng 18 có công thức mẫu: F18 = `=E18-D18` · H18 = `=F18*G18`

### Dòng tổng (dòng 23) — **In đậm**

| Ô | Công thức |
|---|---|
| H23 | `=SUM(H18:H22)` |

---

## 4. PHẦN 2 — NGUYÊN NHÂN VÀ GIẢI TRÌNH (A25:A29)

| Trường | Ghi chú |
|---|---|
| Nguyên nhân phát sinh vượt định mức | Vùng văn bản tự do (nhiều dòng) — nhập tay |

---

## 5. PHẦN 3 — BIỆN PHÁP KHẮC PHỤC (A30:A34)

| Trường | Ghi chú |
|---|---|
| Biện pháp khắc phục và phòng ngừa | Vùng văn bản tự do (nhiều dòng) — nhập tay |

---

## 6. PHẦN 4 — PHÊ DUYỆT THEO THẨM QUYỀN

> **Căn cứ:** Điều 5.2 NQ-HĐQT

### Bảng phân cấp phê duyệt

| Mức | Người phê duyệt | Ngưỡng áp dụng |
|---|---|---|
| **M1** | KẾ TOÁN TRƯỞNG | Tổng vượt định mức **< 1.000.000 đồng** |
| **M2** | PHÓ GĐ TÀI CHÍNH | Tổng vượt định mức **từ 1.000.000 đến dưới 5.000.000 đồng** |
| **M3–M6** | TỔNG GIÁM ĐỐC | Tổng vượt định mức **từ 5.000.000 đồng trở lên** |

### Chi tiết từng ô phê duyệt

#### KẾ TOÁN TRƯỞNG — M1 (dòng 38–42)

| Trường | Vị trí | Nội dung |
|---|---|---|
| Ý kiến | D39 | `Áp dụng khi tổng vượt định mức < 1.000.000 đồng` |
| Kết luận | D40 | `⬜ Chấp thuận hạch toán  ⬜ Không chấp thuận — Lý do: ___` |
| Chữ ký | A41 | _(ký tay)_ |
| Ngày | D42 | `……/……/……` |

#### PHÓ GĐ TÀI CHÍNH — M2 (dòng 44–48)

| Trường | Vị trí | Nội dung |
|---|---|---|
| Ý kiến | D45 | `Áp dụng khi tổng vượt định mức từ 1.000.000 đến dưới 5.000.000 đồng` |
| Kết luận | D46 | `⬜ Chấp thuận hạch toán  ⬜ Không chấp thuận — Lý do: ___` |
| Chữ ký | A47 | _(ký tay)_ |
| Ngày | D48 | `……/……/……` |

#### TỔNG GIÁM ĐỐC — M3–M6 (dòng 50–54)

| Trường | Vị trí | Nội dung |
|---|---|---|
| Ý kiến | D51 | `Áp dụng khi tổng vượt định mức từ 5.000.000 đồng trở lên` |
| Kết luận | D52 | `⬜ Chấp thuận hạch toán  ⬜ Không chấp thuận — Lý do: ___` |
| Chữ ký | A53 | _(ký tay)_ |
| Ngày | D54 | `……/……/……` |

---

## 7. LƯU TRỮ (A56)

> 📌 BM-12 gốc kèm **BM-07** + chứng từ chi → **Kế toán trưởng** giữ bản chính · Scan lưu hệ thống ngay sau khi có phê duyệt · Tối thiểu **10 năm**.

---

## 8. LIÊN KẾT BIỂU MẪU

```
BM-06 (NL vượt ĐM) ──► BM-12 (bắt buộc kèm BM-06A)
BM-12 (phê duyệt xong) ──► KT hạch toán CP vượt định mức
BM-12 ──► BM-07 (kèm khi quyết toán GVLK vượt khoán)
BM-12 ──► BM-08 (CP bất thường nhập vào cột CP SXC khác)
```

---

## 9. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM_6_7_10_11_12.xlsx` |
| Sheet | `BM-12 CP bất thường-vượt ĐM` |
| Vùng dữ liệu | `A1:J56` |
| Số dòng | 56 · Số cột: 10 (A–J) |
