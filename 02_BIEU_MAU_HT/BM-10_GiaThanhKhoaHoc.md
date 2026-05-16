# BM-10 — BẢNG TÍNH GIÁ THÀNH KHÓA HỌC

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-10 |
| **Tên biểu mẫu** | BẢNG TÍNH GIÁ THÀNH KHÓA HỌC |
| **Căn cứ pháp lý** | NQ-HĐQT Điều 5.3 · PL01 Điều 32 |
| **Công thức cốt lõi** | `(CP đầu kỳ + CP PS – CP cuối kỳ) ÷ Số HV hoàn thành` |
| **Người sử dụng** | KT tổng hợp · KT trưởng |
| **Tần suất** | Từng khóa học |

> **Màu sắc tiêu đề:** Dòng 1–2 nền xanh nhạt `#D6E4F0`, chữ xanh đậm `#1F4D78`, in đậm.

---

## 2. THÔNG TIN KHÓA HỌC (A6:D13)

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Mã khóa học | _(ô trống, A6)_ | _(nhập tay)_ |
| Hạng GPLX | D7 | `⬜ B  ⬜ C1  ⬜ C2  ⬜ C  ⬜ D  ⬜ Nâng hạng` |
| Ngày khai giảng | _(ô trống, A8)_ | _(nhập tay)_ |
| Ngày kết thúc | _(ô trống, A9)_ | _(nhập tay)_ |
| Số HV đăng ký | _(ô trống, A10)_ | _(nhập tay)_ |
| Số HV hoàn thành (n) | _(ô trống, A11)_ | _(nhập từ BM-07)_ |
| Số HV dở dang cuối kỳ | _(ô trống, A12, ref: C12)_ | _(nhập từ BM-09)_ |
| Kỳ kế toán | D13 | `Tháng ……/……` |

---

## 3. CHI TIẾT CHI PHÍ VÀ TÍNH GIÁ THÀNH

### Cấu trúc bảng (A16:J28)

| Cột | Tên cột |
|---|---|
| A | STT |
| B | Khoản mục chi phí |
| C | TK kế toán |
| D | Đầu kỳ (đ) |
| E | Phát sinh kỳ (đ) |
| F | Cuối kỳ (đ) |
| G | Tổng kỳ (đ) — `=D+E-F` |
| H | Số HV |
| I | Đơn giá GT/HV (đ) |
| J | Ghi chú |

---

### Nhóm A — CHI PHÍ TRỰC TIẾP (dòng 17–22)

| Dòng | STT | Khoản mục | TK kế toán | Công thức cột G |
|---|---|---|---|---|
| 17 | **A** | **CHI PHÍ TRỰC TIẾP** | — | — |
| 18 | 1 | Nhiên liệu | `1521` | `=D18+E18-F18` |
| 19 | 2 | Giáo viên liên kết (GVLK) | `6271A` | `=D19+E19-F19` |
| 20 | 3 | Vật phẩm thực hành | `1522` | `=D20+E20-F20` |
| 21 | 4 | Thuê xe đối tác (ĐTLK) | `6272` | `=D21+E21-F21` |
| 22 | — | **Cộng A** | — | `=SUM(G17:G21)` |

---

### Nhóm B — CHI PHÍ PHÂN BỔ (dòng 23–27)

| Dòng | STT | Khoản mục | TK kế toán | Công thức cột G |
|---|---|---|---|---|
| 23 | **B** | **CHI PHÍ PHÂN BỔ** | — | — |
| 24 | 5 | Lương NV quản lý phân bổ | `6421` | `=D24+E24-F24` |
| 25 | 6 | Khấu hao TSCĐ phân bổ | `6274` | `=D25+E25-F25` |
| 26 | 7 | Chi phí chung phân bổ khác | `6422` | `=D26+E26-F26` |
| 27 | — | **Cộng B** | — | `=SUM(G23:G26)` |

---

### Dòng tổng (dòng 28) — **In đậm**

| Ô | Nội dung | Công thức |
|---|---|---|
| B28 | TỔNG CHI PHÍ (A+B) | — |
| G28 | Tổng CP kỳ | `=G22+G27` |
| I28 | **Đơn giá GT/HV** | `=IF(C12>0, G28/C12, 0)` |

> 📌 **C12** = Số HV hoàn thành (từ BM-07), được tham chiếu làm mẫu số tính đơn giá.

---

## 4. CÔNG THỨC VÀ LƯU Ý (A30)

```
Giá thành / HV = (CP đầu kỳ + CP phát sinh kỳ – CP cuối kỳ) ÷ Số HV hoàn thành (BM-07)
Kết chuyển: TK 154 → TK 632 theo BM-11
```

---

## 5. PHẦN KÝ DUYỆT

Nền ô: `#F2F2F2` · Chữ đen · In đậm

| Vị trí (Excel) | Chức danh | Nội dung |
|---|---|---|
| A32–A34 | **KẾ TOÁN TỔNG HỢP (Người lập)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| C32–C34 | **KẾ TOÁN TRƯỞNG (Soát xét)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| E32–E34 | **PGĐ TC (Phê duyệt)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 6. LIÊN KẾT BIỂU MẪU

```
BM-08 ──► BM-10 (CP phát sinh kỳ: D, E cột)
BM-09 ──► BM-10 (CP dở dang cuối kỳ: F cột + số HV dở dang)
BM-07 ──► BM-10 (số HV hoàn thành: C12)

BM-10 ──► BM-11 (giá thành KH → kết chuyển TK 154 → 632)
```

---

## 7. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM_6_7_10_11_12.xlsx` |
| Sheet | `BM-10 Giá thành khóa học` |
| Vùng dữ liệu | `A1:J35` |
| Số dòng | 35 · Số cột: 10 (A–J) |
