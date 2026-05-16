# BM-08 — BẢNG TỔNG HỢP CHI PHÍ THEO KHÓA / HẠNG

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-08 |
| **Tên biểu mẫu** | BẢNG TỔNG HỢP CHI PHÍ THEO KHÓA / HẠNG |
| **Căn cứ pháp lý** | PL01 Điều 28-29 · P3 Điều 14.4 |
| **Căn cứ lập** | Căn cứ lập BM-10 |
| **Người sử dụng** | KT tổng hợp · KT trưởng |
| **Tần suất** | Hàng tháng |

---

## 2. TIÊU ĐỀ & THÔNG TIN KỲ BÁO CÁO

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Kỳ kế toán | D6 | `Tháng ……/……` |
| Ngày lập | K6 | `……/……/……` |
| Người lập | _(ô trống, A7)_ | _(nhập tay)_ |
| Đơn vị tiền | K7 | `Đồng Việt Nam (VNĐ)` |

> **Màu sắc tiêu đề:** Dòng 1–2 dùng nền xanh nhạt `#D6E4F0`, chữ xanh đậm `#1F4D78`, in đậm.

---

## 3. MỤC ĐÍCH SỬ DỤNG

Tổng hợp toàn bộ chi phí TK 621 / 622 / 627 đã phát sinh trong kỳ, phân tách theo **mã đối tượng** (khóa học / hạng GPLX). Đây là **đầu vào bắt buộc** để lập:
- **BM-10** — Tính giá thành
- **BM-09** — Xác định chi phí dở dang

Số liệu phải khớp với sổ chi tiết TK 154A/B/C trước khi KT trưởng ký.

---

## 4. PHẦN 1 — CHI TIẾT CHI PHÍ THEO KHÓA HỌC & HẠNG GPLX

### 4.1 Cấu trúc bảng (A11:N21)

#### Hàng tiêu đề nhóm (dòng 11)

| Cột | Nhóm | Tài khoản |
|---|---|---|
| A–B | KHÓA / HẠNG | — |
| C–E | **NHÓM A — NVL TRỰC TIẾP** | TK 621 |
| F–I | **NHÓM B — NHÂN CÔNG TRỰC TIẾP** | TK 622 |
| J–L | **NHÓM C — SXC** | TK 627 |
| M | TỔNG CP KỲ NÀY | — |
| N | GHI CHÚ | — |

#### Hàng tiêu đề cột (dòng 12)

| Cột | Tên cột | Ghi chú |
|---|---|---|
| A | Mã khóa | |
| B | Hạng GPLX | |
| C | NL xe — TK 621A | Nhóm A |
| D | Vật tư tiêu hao | Nhóm A |
| E | Tài liệu HV | Nhóm A |
| F | GV cơ hữu | Nhóm B |
| G | GVLK khoán | Nhóm B |
| H | Thuê xe ĐTLK | Nhóm B |
| I | KC khác | Nhóm B |
| J | KH TSCĐ | Nhóm C |
| K | SC bảo dưỡng | Nhóm C |
| L | CP SXC khác | Nhóm C |
| M | TỔNG | `=SUM(C:L)` theo hàng |
| N | Ghi chú | |

#### Danh sách khóa học (dòng 13–20)

| Dòng | Mã khóa | Hạng GPLX | Công thức cột M |
|---|---|---|---|
| 13 | KH-B | Hạng B | `=SUM(C13:L13)` |
| 14 | KH-C1 | Hạng C1 | `=SUM(C14:L14)` |
| 15 | KH-C2 | Hạng C2 | `=SUM(C15:L15)` |
| 16 | KH-C | Hạng C | `=SUM(C16:L16)` |
| 17 | KH-D1 | Hạng D1 | `=SUM(D17:L17)` |
| 18 | KH-D2 | Hạng D2 | `=SUM(C18:L18)` |
| 19 | KH-D | Hạng D | `=SUM(C19:L19)` |
| 20 | KH-NH | Nâng hạng | `=SUM(C20:L20)` |

#### Dòng tổng cộng (dòng 21) — **In đậm**

| Cột | Công thức |
|---|---|
| C21 | `=SUM(C13:C20)` |
| D21 | `=SUM(D13:D20)` |
| E21 | `=SUM(E13:E20)` |
| F21 | `=SUM(F13:F20)` |
| G21 | `=SUM(G13:G20)` |
| H21 | `=SUM(H13:H20)` |
| I21 | `=SUM(I13:I20)` |
| J21 | `=SUM(J13:J20)` |
| K21 | `=SUM(K13:K20)` |
| L21 | `=SUM(L13:L20)` |
| M21 | `=SUM(M13:M20)` |

---

## 5. PHẦN 2 — KIỂM TRA ĐỐI CHIẾU VỚI SỔ KẾ TOÁN

### Cấu trúc bảng (A24:G28)

| Cột | Tên cột |
|---|---|
| A | Nhóm TK |
| B | Tên khoản mục |
| C | TK kế toán chi tiết |
| D | Tổng phát sinh Nợ kỳ này |
| E | Tổng từ BM-08 Phần 1 |
| F | Chênh lệch (`=D-E`) |
| G | Nguyên nhân (nếu có) |

### Dữ liệu mặc định (dòng 25–28)

| Dòng | Nhóm TK | Tên khoản mục | TK chi tiết | Công thức chênh lệch |
|---|---|---|---|---|
| 25 | Nhóm A | NVL trực tiếp | 621A / B / C | `=D25-E25` |
| 26 | Nhóm B | Nhân công TT | 622A / B / C | `=D26-E26` |
| 27 | Nhóm C | Chi phí SXC | 6271A…6278A / B / C | `=D27-E27` |
| 28 | **TỔNG CỘNG** | | | `=D28-E28` |

> ⚠️ **Kiểm tra:** Chênh lệch phải = 0 trước khi KT trưởng ký duyệt. Nếu có chênh lệch → ghi nguyên nhân rõ ràng và chờ KT trưởng xử lý trước khi chuyển lập BM-09, BM-10.

---

## 6. PHẦN KÝ DUYỆT

Nền ô: `#F2F2F2` (xám nhạt) · Chữ đen · In đậm

| Vị trí | Chức danh | Nội dung |
|---|---|---|
| A32–A34 | **KẾ TOÁN TỔNG HỢP (Người lập)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| D32–D34 | **KẾ TOÁN TRƯỞNG (Soát xét & ký)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| J32–J34 | **PGĐ TC PHÊ DUYỆT** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 7. LIÊN KẾT BIỂU MẪU

```
BM-08 (đầu ra)
    ├──► BM-09  (xác định CP dở dang TK 154A)
    └──► BM-10  (tính giá thành)
```

---

## 8. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM-08_09_Chi_phi_Do_dang.xlsx` |
| Sheet | `BM-08 Tổng hợp CP-Khóa hạng` |
| Vùng dữ liệu | `A1:N36` |
| Số dòng | 36 · Số cột: 14 (A–N) |
