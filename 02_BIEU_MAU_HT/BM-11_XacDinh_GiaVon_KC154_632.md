# BM-11 — BẢNG XÁC ĐỊNH GIÁ VỐN — KẾT CHUYỂN TK 154 → TK 632

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-11 |
| **Tên biểu mẫu** | BẢNG XÁC ĐỊNH GIÁ VỐN — KẾT CHUYỂN TK 154 → TK 632 |
| **Căn cứ pháp lý** | NQ-HĐQT Điều 5.3 · PL01 Điều 33 · PGĐ TC phê duyệt |
| **Người sử dụng** | KT tổng hợp · KT trưởng · PGĐ TC |
| **Tần suất** | Hàng tháng |

> **Màu sắc tiêu đề:** Dòng 1–2 nền xanh nhạt `#D6E4F0`, chữ xanh đậm `#1F4D78`, in đậm.

---

## 2. THÔNG TIN KỲ BÁO CÁO (A6:D8)

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Kỳ kế toán | D6 | `Tháng ……/……` |
| Người lập | _(ô trống, A7)_ | _(nhập tay)_ |
| Ngày lập | D8 | `……/……/……` |

---

## 3. CHI TIẾT THEO NHÓM HOẠT ĐỘNG

### Cấu trúc bảng (A11:J15)

| Cột | Tên cột |
|---|---|
| A | STT |
| B | Nhóm hoạt động |
| C | TK 154 (Chi tiết) |
| D | Dư đầu kỳ (đ) |
| E | CP PS kỳ (đ) |
| F | Giá thành KH (đ) |
| G | Dư cuối kỳ (đ) — `=D+E-F` |
| H | Số HV / ca SH |
| I | Giá vốn kết chuyển (đ) — `=F` |
| J | Ghi chú |

### Dữ liệu các nhóm hoạt động (dòng 12–14)

| Dòng | STT | Nhóm hoạt động | TK 154 | Công thức G | Công thức I |
|---|---|---|---|---|---|
| 12 | **A** | Đào tạo lái xe (ĐT) | `154A` | `=D12+E12-F12` | `=F12` |
| 13 | **B** | Cho thuê xe ĐT liên kết | `154B` | `=D13+E13-F13` | `=F13` |
| 14 | **C** | Cho thuê xe SH liên kết | `154C` | `=D14+E14-F14` | `=F14` |

### Dòng tổng cộng (dòng 15) — **In đậm**

| Cột | Công thức |
|---|---|
| D15 | `=SUM(D12:D14)` |
| E15 | `=SUM(E12:E14)` |
| F15 | `=SUM(F12:F14)` |
| G15 | `=SUM(G12:G14)` |
| I15 | `=SUM(I12:I14)` |

---

## 4. BẢNG ĐỊNH KHOẢN KẾT CHUYỂN

### Cấu trúc bảng (A18:H21)

| Cột | Tên cột |
|---|---|
| A | STT |
| B | Định khoản |
| D | Nợ TK |
| E | Có TK |
| F | Số tiền (đ) |
| H | Ghi chú |

### Các bút toán kết chuyển (dòng 19–21)

| Dòng | STT | Nội dung định khoản | Nợ TK | Có TK | Công thức số tiền |
|---|---|---|---|---|---|
| 19 | 1 | Kết chuyển giá vốn ĐT | **632A** | **154A** | `=I12` |
| 20 | 2 | Kết chuyển giá vốn thuê xe ĐT | **632B** | **154B** | `=I13` |
| 21 | 3 | Kết chuyển giá vốn thuê xe SH | **632C** | **154C** | `=I14` |

---

## 5. PHẦN KÝ DUYỆT

Nền ô: `#F2F2F2` · Chữ đen · In đậm

| Vị trí (Excel) | Chức danh | Nội dung |
|---|---|---|
| A24–A26 | **KẾ TOÁN TỔNG HỢP (Người lập)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| C24–C26 | **KẾ TOÁN TRƯỞNG (Soát xét và ký)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| E24–E26 | **PGĐ TC (Phê duyệt)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| G25–G26 | _(ô phụ ký)_ | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 6. LIÊN KẾT BIỂU MẪU

```
BM-10 ──► BM-11 (Giá thành KH → cột F)
BM-09 ──► BM-11 (Dư đầu kỳ TK 154A → cột D)
BM-08 ──► BM-11 (CP phát sinh kỳ TK 154A → cột E)

BM-11 ──► Sổ cái TK 632 (ghi nhận giá vốn)
BM-11 ──► BM-09 kỳ sau (Dư cuối kỳ TK 154A → cột G)
```

---

## 7. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM_6_7_10_11_12.xlsx` |
| Sheet | `BM-11 Xác định giá vốn` |
| Vùng dữ liệu | `A1:J27` |
| Số dòng | 27 · Số cột: 10 (A–J) |
