# BM-09 — BẢNG XÁC ĐỊNH CHI PHÍ SẢN XUẤT DỞ DANG (TK 154)

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-09 |
| **Tên biểu mẫu** | BẢNG XÁC ĐỊNH CHI PHÍ SẢN XUẤT DỞ DANG (TK 154) |
| **Căn cứ pháp lý** | PL01 Điều 31 · P3 Điều 14.1 |
| **Căn cứ xác nhận** | Phòng ĐT xác nhận số HV dở dang |
| **Người sử dụng** | KT tổng hợp · Phòng ĐT · KT trưởng |
| **Tần suất** | Hàng tháng |

---

## 2. TIÊU ĐỀ & THÔNG TIN KỲ BÁO CÁO

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Kỳ kế toán | D6 | `Tháng ……/……` |
| Ngày lập | I6 | `……/……/……` |
| Người lập | _(ô trống, A7)_ | _(nhập tay)_ |
| Đơn vị | I7 | `VNĐ` |

> **Màu sắc tiêu đề:** Dòng 1–2 dùng nền xanh nhạt, chữ xanh đậm, in đậm (tương tự BM-08).

---

## 3. MỤC ĐÍCH SỬ DỤNG

Xác định chính xác số dư **TK 154A** (CP dở dang đầu kỳ và cuối kỳ) cho từng khóa học đang triển khai.

- **Phòng Đào tạo** xác nhận danh sách HV dở dang trước khi KT trưởng ký.
- Kết quả BM-09 là **đầu vào bắt buộc** cho **BM-10** (công thức giá thành).

---

## 4. PHẦN 1 — DANH SÁCH KHÓA HỌC ĐANG DỞ DANG CUỐI KỲ

> **Định nghĩa:** Khóa dở dang = khóa đã khai giảng nhưng chưa hoàn thành trong kỳ (chưa có BM-07 cuối khóa).  
> **Hạn nộp:** Phòng Đào tạo cung cấp danh sách chậm nhất **ngày 3 tháng sau**.

### Cấu trúc bảng (A13:K24)

| Cột | Tên cột | Loại |
|---|---|---|
| A | Mã khóa | Nhập tay |
| B | Hạng GPLX | Nhập tay |
| C | Ngày khai giảng | Nhập tay |
| D | Ngày KT dự kiến | Nhập tay |
| E | Số HV đăng ký | Nhập tay |
| F | Số HV hoàn thành | Nhập tay |
| G | Số HV dở dang | Công thức: `=IF(E>0, E-F, "")` |
| H | % HT ước tính | Công thức: `=IF(E>0, F/E, "")` |
| I | TK 154 (chi tiết) | Mặc định: `154A` |
| J | Trạng thái | Mặc định: `🔄 Đang học` |
| K | Ghi chú | Nhập tay |

### Các dòng dữ liệu (14–23) — 10 dòng mặc định

| Dòng | Cột G (công thức) | Cột H (công thức) | Cột I | Cột J |
|---|---|---|---|---|
| 14 | `=IF(E14>0,E14-F14,"")` | `=IF(E14>0,F14/E14,"")` | `154A` | `🔄 Đang học` |
| 15 | `=IF(E15>0,E15-F15,"")` | `=IF(E15>0,F15/E15,"")` | `154A` | `🔄 Đang học` |
| 16 | `=IF(E16>0,E16-F16,"")` | `=IF(E16>0,F16/E16,"")` | `154A` | `🔄 Đang học` |
| 17 | `=IF(E17>0,E17-F17,"")` | `=IF(E17>0,F17/E17,"")` | `154A` | `🔄 Đang học` |
| 18 | `=IF(E18>0,E18-F18,"")` | `=IF(E18>0,F18/E18,"")` | `154A` | `🔄 Đang học` |
| 19 | `=IF(E19>0,E19-F19,"")` | `=IF(E19>0,F19/E19,"")` | `154A` | `🔄 Đang học` |
| 20 | `=IF(E20>0,E20-F20,"")` | `=IF(E20>0,F20/E20,"")` | `154A` | `🔄 Đang học` |
| 21 | `=IF(E21>0,E21-F21,"")` | `=IF(E21>0,F21/E21,"")` | `154A` | `🔄 Đang học` |
| 22 | `=IF(E22>0,E22-F22,"")` | `=IF(E22>0,F22/E22,"")` | `154A` | `🔄 Đang học` |
| 23 | `=IF(E23>0,E23-F23,"")` | `=IF(E23>0,F23/E23,"")` | `154A` | `🔄 Đang học` |

### Dòng tổng cộng (dòng 24) — **In đậm**

| Cột | Công thức |
|---|---|
| E24 | `=SUM(E14:E23)` |
| F24 | `=SUM(F14:F23)` |
| G24 | `=SUM(G14:G23)` |

---

## 5. PHẦN 2 — XÁC ĐỊNH GIÁ TRỊ CHI PHÍ DỞ DANG TK 154A CUỐI KỲ

### Phương pháp tính

```
CP dở dang cuối kỳ = CP đầu kỳ + CP phát sinh kỳ − CP tính vào giá thành các khóa hoàn thành
```

Kết quả = **Dư Nợ TK 154A cuối kỳ** trên sổ cái. Chi tiết phân bổ theo từng mã khóa.

### Cấu trúc bảng (A28:K39)

| Cột | Tên cột | Ký hiệu | Loại |
|---|---|---|---|
| A | Mã khóa | | Nhập tay |
| B | Hạng GPLX | | Nhập tay |
| C | Dư Nợ 154A Đầu kỳ (đ) | C | Nhập tay |
| D | CP phát sinh kỳ này (đ) | D | Nhập tay |
| E | CP đã tính vào GT (đ) | E | Nhập tay |
| F | Dư Nợ 154A Cuối kỳ (đ) | F | Công thức: `=IF(C+D-E<>0, C+D-E, "")` |
| G | Trong đó: NL (đ) | | Nhập tay |
| H | Trong đó: Nhân công (đ) | | Nhập tay |
| I | Trong đó: SXC (đ) | | Nhập tay |
| J | Kiểm tra (F = C+D−E) | | Công thức kiểm tra |
| K | Ghi chú | | Nhập tay |

### Công thức cột F và J (dòng 29–38)

| Dòng | Cột F | Cột J |
|---|---|---|
| 29 | `=IF(C29+D29-E29<>0,C29+D29-E29,"")` | `=IF(F29=C29+D29-E29,"✓ OK","⚠ Sai")` |
| 30 | `=IF(C30+D30-E30<>0,C30+D30-E30,"")` | `=IF(F30=C30+D30-E30,"✓ OK","⚠ Sai")` |
| 31 | `=IF(C31+D31-E31<>0,C31+D31-E31,"")` | `=IF(F31=C31+D31-E31,"✓ OK","⚠ Sai")` |
| 32 | `=IF(C32+D32-E32<>0,C32+D32-E32,"")` | `=IF(F32=C32+D32-E32,"✓ OK","⚠ Sai")` |
| 33 | `=IF(C33+D33-E33<>0,C33+D33-E33,"")` | `=IF(F33=C33+D33-E33,"✓ OK","⚠ Sai")` |
| 34 | `=IF(C34+D34-E34<>0,C34+D34-E34,"")` | `=IF(F34=C34+D34-E34,"✓ OK","⚠ Sai")` |
| 35 | `=IF(C35+D35-E35<>0,C35+D35-E35,"")` | `=IF(F35=C35+D35-E35,"✓ OK","⚠ Sai")` |
| 36 | `=IF(C36+D36-E36<>0,C36+D36-E36,"")` | `=IF(F36=C36+D36-E36,"✓ OK","⚠ Sai")` |
| 37 | `=IF(C37+D37-E37<>0,C37+D37-E37,"")` | `=IF(F37=C37+D37-E37,"✓ OK","⚠ Sai")` |
| 38 | `=IF(C38+D38-E38<>0,C38+D38-E38,"")` | `=IF(F38=C38+D38-E38,"✓ OK","⚠ Sai")` |

### Dòng tổng cộng (dòng 39) — **In đậm**

| Cột | Công thức |
|---|---|
| C39 | `=SUM(C29:C38)` |
| D39 | `=SUM(D29:D38)` |
| E39 | `=SUM(E29:E38)` |
| F39 | `=SUM(F29:F38)` |
| G39 | `=SUM(G29:G38)` |
| H39 | `=SUM(H29:H38)` |
| I39 | `=SUM(I29:I38)` |

---

## 6. PHẦN 3 — ĐỐI CHIẾU SỔ CÁI TK 154A CUỐI KỲ

> Các số liệu dưới đây phải khớp với **sổ cái TK 154A** trước khi KT trưởng ký duyệt. Chênh lệch bất kỳ phải giải trình.

| Dòng | Nội dung | Đơn vị | Ghi chú |
|---|---|---|---|
| 43 | Dư Nợ TK 154A **đầu kỳ** (từ sổ cái) | đ | Nhập tay |
| 44 | Tổng CP phát sinh Nợ TK 154A kỳ này (từ BM-08) | đ | Nhập tay |
| 45 | Tổng CP kết chuyển Có TK 154A → TK 632 kỳ này (từ BM-11) | đ | Nhập tay |
| 46 | **Dư Nợ TK 154A cuối kỳ tính từ BM-09 Phần 2** | — | `= Đầu kỳ + PS Nợ − Kết chuyển` |
| 47 | Dư Nợ TK 154A **cuối kỳ** trên sổ cái | đ | Nhập tay |
| 48 | **Chênh lệch (phải = 0)** | — | `= Dòng 4 − Dòng 5` |

---

## 7. PHẦN 4 — XÁC NHẬN CỦA PHÒNG ĐÀO TẠO

> Phòng Đào tạo xác nhận: Danh sách khóa dở dang tại Phần 1 là chính xác và đầy đủ theo thực tế theo dõi học viên tính đến cuối kỳ.

| Trường | Vị trí | Nội dung |
|---|---|---|
| Họ và tên | A53 | Trưởng / Đại diện Phòng ĐT |
| Kết luận | D54 | `⬜ Xác nhận danh sách chính xác` · `⬜ Cần điều chỉnh — Lý do: ___` |
| Chữ ký | A55 | _(ký tay)_ |
| Ngày xác nhận | D56 | `……/……/……` |

---

## 8. PHẦN KÝ DUYỆT

Nền ô: `#F2F2F2` (xám nhạt) · Chữ đen · In đậm

| Vị trí (Excel) | Chức danh | Nội dung |
|---|---|---|
| A59–A61 | **KẾ TOÁN TỔNG HỢP (Người lập)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| C59–C61 | **TRƯỞNG P. ĐÀO TẠO (Xác nhận HV dở dang)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| E59–E61 | **KẾ TOÁN TRƯỞNG (Soát xét & ký duyệt)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| G59–G61 | **PGĐ TC PHÊ DUYỆT** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 9. LIÊN KẾT BIỂU MẪU

```
BM-08  ──► BM-09 (đầu vào: CP phát sinh kỳ này)
BM-07  ──► BM-09 (đầu vào: HV hoàn thành)
BM-11  ──► BM-09 (đầu vào: CP kết chuyển TK 154A → 632)
Phòng ĐT ─► BM-09 (xác nhận danh sách khóa dở dang)

BM-09  ──► BM-10 (đầu ra: CP dở dang cuối kỳ)
```

---

## 10. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM-08_09_Chi_phi_Do_dang.xlsx` |
| Sheet | `BM-09 Chi phí dở dang TK154` |
| Vùng dữ liệu | `A1:K63` |
| Số dòng | 63 · Số cột: 11 (A–K) |
