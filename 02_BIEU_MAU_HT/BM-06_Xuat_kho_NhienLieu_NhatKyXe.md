# BM-06 — PHIẾU XUẤT KHO NHIÊN LIỆU & NHẬT KÝ XE

---

## 1. THÔNG TIN CHUNG

| Trường | Nội dung |
|---|---|
| **Đơn vị** | CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG THƯƠNG MẠI CÁT TƯỜNG MINH |
| **Bộ phận** | Trung tâm GDNN & Sát hạch lái xe Bình Thuận |
| **Mã biểu mẫu** | BM-06 |
| **Tên biểu mẫu** | PHIẾU XUẤT KHO NHIÊN LIỆU & NHẬT KÝ XE |
| **Căn cứ pháp lý** | NQ-HĐQT Điều 5.3 · PL01 Điều 16 |
| **Người sử dụng** | Thủ kho · KT vật tư · Bộ phận PT |
| **Tần suất** | Từng ca / ngày |

> **Màu sắc tiêu đề:** Dòng 1–2 nền xanh nhạt `#D6E4F0`, chữ xanh đậm `#1F4D78`, in đậm.

---

## 2. PHẦN A — PHIẾU XUẤT KHO NHIÊN LIỆU (TK 1521)

### Các trường thông tin (A6:D18)

| Trường | Vị trí (Excel) | Nội dung / Giá trị mặc định |
|---|---|---|
| Số phiếu | D7 | `……/BM-06A/……` |
| Ngày xuất | D8 | `……/……/……` |
| Mã khóa học | _(ô trống, A9)_ | _(nhập tay)_ |
| Hạng GPLX | D10 | `⬜ B  ⬜ C1  ⬜ C2  ⬜ C  ⬜ D1  ⬜ D2  ⬜ D` |
| Xe biển số | _(ô trống, A11)_ | _(nhập tay)_ |
| Loại nhiên liệu | D12 | `⬜ Xăng RON 95  ⬜ Xăng RON 92  ⬜ Dầu Diesel` |
| Định mức (lít/giờ) | _(ô trống, A13)_ | _(nhập tay)_ |
| Số giờ ca | _(ô trống, A14)_ | _(nhập tay)_ |
| Số lít định mức | _(ô trống, A15)_ | _(nhập tay / tính)_ |
| Số lít thực xuất | _(ô trống, A16)_ | _(nhập tay)_ |
| Ghi chú | _(ô trống, A17)_ | _(nhập tay)_ |

> ⚠️ **Lưu ý A18:** Xuất vượt định mức phải có **BM-12** kèm theo. Phiếu tạm ứng nhiên liệu xe thuê → **TK 141**, thanh toán với xe ĐTLK theo **BM-07**.

---

## 3. PHẦN B — NHẬT KÝ XE HÀNG THÁNG

### Cấu trúc bảng (A21:L42)

| Cột | Tên cột | Loại |
|---|---|---|
| A | Ngày | Nhập tay |
| B | Biển số xe | Nhập tay |
| C | Hạng xe | Nhập tay |
| D | Ca (S/C/T) | Nhập tay _(Sáng / Chiều / Tối)_ |
| E | Giờ bắt đầu | Nhập tay |
| F | Giờ kết thúc | Nhập tay |
| G | Số giờ | Nhập tay |
| H | Km đầu | Nhập tay |
| I | Km cuối | Nhập tay |
| J | Số km | Nhập tay |
| K | Nhiên liệu (lít) | Nhập tay |
| L | Ghi chú | Nhập tay |

- **Số dòng dữ liệu:** 20 dòng (dòng 22–41)

### Dòng tổng cộng (dòng 42) — **In đậm**

| Cột | Công thức |
|---|---|
| G42 | `=SUM(G22:G41)` |
| J42 | `=SUM(J22:J41)` |
| K42 | `=SUM(K22:K41)` |

---

## 4. PHẦN KÝ DUYỆT

Nền ô: `#F2F2F2` · Chữ đen · In đậm

| Vị trí (Excel) | Chức danh | Nội dung |
|---|---|---|
| A44–A46 | **NGƯỜI LẬP (Thủ kho / KT vật tư)** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| D44–D46 | **BỘ PHẬN PHƯƠNG TIỆN XÁC NHẬN** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| G44–G46 | **KẾ TOÁN TRƯỞNG** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |
| J44–J46 | **PGĐ TC PHÊ DUYỆT** | Ký và ghi rõ họ tên · Ngày: ……/……/…… |

---

## 5. LIÊN KẾT BIỂU MẪU

```
BM-06 (Phần A) ──► TK 1521 (xuất kho nhiên liệu)
BM-06 (NL vượt ĐM) ──► BM-12 (bắt buộc kèm theo)
BM-06 (xe thuê tạm ứng) ──► TK 141 → quyết toán theo BM-07
BM-06 (Phần B) ──► BM-08 (tổng hợp CP nhiên liệu theo khóa)
```

---

## 6. THÔNG TIN FILE

| Thuộc tính | Giá trị |
|---|---|
| File gốc | `BM_6_7_10_11_12.xlsx` |
| Sheet | `BM-06 Xuất kho NL-Nhật ký xe` |
| Vùng dữ liệu | `A1:L47` |
| Số dòng | 47 · Số cột: 12 (A–L) |
