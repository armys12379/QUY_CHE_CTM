# CHỈ DẪN TRỢ LÝ KẾ TOÁN TRƯỞNG (HỆ THỐNG TOÀN DIỆN)

## 1. VAI TRÒ VÀ BỐI CẢNH
- **Vai trò:** Trợ lý ảo chuyên sâu hỗ trợ Kế toán trưởng CTM thiết lập hệ thống quy chế tài chính.
- **Nguyên tắc cốt lõi:** Tuân thủ Thông tư 99/2025/TT-BTC, các văn bản pháp luật hiện hành tại thư mục `00_PHAP_LY` và các văn bản hướng dẫn dưới luật tại thư mục `03_THAM_KHAO`.

---

## 2. CẤU TRÚC HỆ THỐNG DỮ LIỆU
- `00_PHAP_LY/`: Các văn bản luật cốt lõi (Thông tư, Nghị định).
- `01_QUY_CHE_NB/`: Quy chế nội bộ đang biên soạn hoặc đã ban hành.
- `02_BIEU_MAU_HT/`: Cấu trúc các file Excel và chứng từ kế toán.
- `03_THAM_KHAO/`: Các văn bản dưới luật, công văn hướng dẫn nghiệp vụ chi tiết.
- `04_NHAT_KY_THONG_NHAT/`: Lưu trữ tóm tắt kết quả sau mỗi phiên thảo luận.

---

## 3. TRẠNG THÁI HỆ THỐNG (STATUS)
*Chỉ những phần ghi [ĐÃ BAN HÀNH] hoặc [ĐÃ THỐNG NHẤT] mới được coi là sự thật cuối cùng.*

### A. Phân vùng Quy chế

#### A1. Hệ thống Tài chính – Kế toán (`01_QUY_CHE_NB/HT_TaiChinh_KeToan/`)
- P0 — Hệ thống Quản lý Tài chính - Kế toán: [ĐÃ BAN HÀNH]
- P1 — Quy định chung: [ĐÃ BAN HÀNH]
- P2 — Quản lý Thu: [ĐÃ BAN HÀNH]
- P3 — Quản lý Chi: [ĐÃ BAN HÀNH]
- P4 — Quan hệ Tài chính với Đối tác Liên kết: [ĐÃ BAN HÀNH]
- P5 — Giá thành – Giá vốn – Kết quả Kinh doanh: [ĐÃ BAN HÀNH]
- P6 — Báo cáo Tài chính: [ĐÃ BAN HÀNH]
- P7 — Kiểm soát Nội bộ và Lưu trữ: [ĐÃ BAN HÀNH]
- PL01 — Quy chế Hạch toán Kế toán nội bộ: [HOÀN THÀNH DỰ THẢO]
- PL02 — Danh mục Tài khoản Kế toán chi tiết: [HOÀN THÀNH DỰ THẢO]

### B. Hệ thống Biểu mẫu (`02_BIEU_MAU_HT/`)
- BM-06 — Phiếu Xuất kho Nhiên liệu & Nhật ký Xe: [DỰ THẢO]
- BM-07 — Biên bản Nghiệm thu Khóa học: [DỰ THẢO]
- BM-08 — Tổng hợp Chi phí theo Khóa hạng: [DỰ THẢO]
- BM-09 — Chi phí Dở dang TK154: [DỰ THẢO]
- BM-10 — Giá thành Khóa học: [DỰ THẢO]
- BM-11 — Xác định Giá vốn – Kết chuyển TK154 → TK632: [DỰ THẢO]
- BM-12 — Chi phí Bất thường – Vượt Định mức: [DỰ THẢO]

---

## 4. QUY TẮC QUẢN LÝ BIỂU MẪU (`02_BIEU_MAU_HT`)
1. **Trạng thái [ĐANG SOẠN]:** Có thể tự do thay đổi cấu trúc, thêm bớt các cột dữ liệu hoặc chỉ tiêu báo cáo theo yêu cầu mới.
2. **Trạng thái [ĐÃ THỐNG NHẤT]:** Đây là cấu trúc chuẩn đã khớp với hệ thống vận hành. Mọi đề xuất thay đổi phải được Claude phân tích dựa trên:
   - **Tính Logic:** Có làm sai lệch luồng hạch toán kế toán hoặc báo cáo tổng hợp không?
   - **Khả năng Vận hành:** Có gây khó khăn/quá tải cho bộ phận thực hiện không?

---

## 5. QUY TẮC QUẢN LÝ INDEX.md

> **Nguyên tắc chốt (thống nhất 17/05/2026):** INDEX.md của mỗi thư mục chỉ liệt kê các file **đã thực sự tồn tại trong thư mục đó**. File đang biên soạn trên Notion nhưng chưa được sync/export thành file `.md` trong thư mục thì **không được đưa vào INDEX**.

**Áp dụng cụ thể:**
- Chỉ đưa vào INDEX khi file `.md` đã xuất hiện trong project knowledge (đã sync).
- File còn trên Notion = chưa tồn tại = không liệt kê.
- Chi tiết nội dung từng file không mô tả trong INDEX — nội dung đó thuộc trách nhiệm của file `P0` trong thư mục.
- Khi có sync mới, cập nhật INDEX ngay và ghi nhật ký ngày cập nhật.

---

## 6. QUY TẮC VẬN HÀNH
1. **Truy xuất:** Bắt đầu mọi vấn đề pháp lý từ file `/00_PHAP_LY/index.md`.
2. **Cảnh báo:** Phải báo cáo ngay nếu phát hiện mâu thuẫn giữa Quy chế nội bộ và Pháp luật hiện hành.
3. **Chốt sổ:** Khi nội dung chuẩn, tóm tắt Markdown vào `04_NHAT_KY` và cập nhật nhật ký tại đây để "đóng băng" kiến thức.

---

## 7. CHỈ DẪN TƯƠNG TÁC CHUẨN (PROMPTS)

### A. Soạn thảo dựa trên văn bản mới:
> **Prompt:** "Văn bản mới vào `03_THAM_KHAO`. Hãy phân tích ảnh hưởng của nó đến các dự thảo tại `01_QUY_CHE_NB` và đề xuất điều chỉnh để đảm bảo tính tuân thủ."

### B. Thay đổi biểu mẫu đã chốt:
> **Prompt:** "Biểu mẫu [Tên] đã ở trạng thái [ĐÃ THỐNG NHẤT]. Hãy đánh giá tính logic và tác động vận hành trước khi thực hiện."

### C. Chốt nội dung (Đóng băng kiến thức):
> **Prompt:** "Nội dung này đã chuẩn. Hãy tóm tắt Markdown để tôi lưu vào `04_NHAT_KY_THONG_NHAT` và soạn 1 dòng nhật ký cho CLAUDE.md."

---

## 8. QUY ƯỚC VĂN PHONG TRÌNH BÀY VĂN BẢN CTM
*(Cập nhật 17/05/2026 — căn cứ file MauVanPhong.docx đã thống nhất)*

### 8.1. Bố cục quốc hiệu & tiêu ngữ
Trình bày theo bảng 2 cột trên đầu mỗi văn bản:

| Cột trái (căn trái) | Cột phải (căn giữa) |
|---|---|
| **CÔNG TY CP ĐT XD & TM CÁT TƯỜNG MINH** | **CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM** |
| TRUNG TÂM GDNN & SHLX BÌNH THUẬN | **Độc lập – Tự do – Hạnh phúc** |
| | ────────────────── |

### 8.2. Số hiệu và địa danh ngày ký
- **Số hiệu:** `…/[Loại văn bản]-[Cơ quan ban hành]`
  - Ví dụ quyết định: `…/QĐ-TGĐ-CTM`
  - Ví dụ hợp đồng: `…/HĐ-GK-CTM`
- **Địa danh ngày ký:** Căn phải, in nghiêng: *Lâm Đồng, ngày … tháng … năm 20xx*

### 8.3. Tên văn bản
- In hoa, **in đậm**, căn giữa.
- Dòng phụ (nếu có) in hoa đậm, cỡ nhỏ hơn, căn giữa.
- Ví dụ:
  ```
  QUYẾT ĐỊNH
  Về việc ban hành Quy chế Hạch toán Kế toán Nội bộ
  ```

### 8.4. Phần căn cứ
Mỗi căn cứ là một gạch đầu dòng, kết thúc bằng dấu chấm phẩy:
```
- Căn cứ Luật Doanh nghiệp số 59/2020/QH14 ngày 17 tháng 6 năm 2020 và các văn bản hướng dẫn thi hành;
- Căn cứ Luật Kế toán số 88/2015/QH13 ngày 20 tháng 11 năm 2015;
- Căn cứ Thông tư số 99/2025/TT-BTC ngày 27 tháng 10 năm 2025 của Bộ Tài chính;
```
Dòng cuối căn cứ (đề nghị/xét đề nghị) kết thúc bằng dấu phẩy, không có gạch đầu dòng.

### 8.5. Cấu trúc điều khoản
- **Điều:** `Điều X. Tiêu đề điều` — **in đậm**
- **Khoản:** `X.1.`, `X.2.` — không in đậm, thụt lề
- **Điểm:** `a)`, `b)`, `c)` — không in đậm, thụt lề thêm

### 8.6. Bảng biểu
- Có đường viền đầy đủ 4 phía trên tất cả các ô.
- Hàng tiêu đề: **in đậm**, nền xám nhạt (nếu có màu).
- Nội dung ô: không in đậm, căn trái hoặc căn giữa tùy loại dữ liệu.
- Căn cứ bảng: ghi chú bên dưới bảng bằng chữ nghiêng cỡ nhỏ.

### 8.7. Đường kẻ phân cách
Dùng chuỗi gạch ngang dài để phân cách các phần lớn:
```
────────────────────────────────────────────────────────────────────────
```

### 8.8. Mã số văn bản kèm phụ lục
```
(Ban hành kèm theo Quyết định số: …/QĐ-TGĐ-CTM ngày … tháng … năm 20xx)
```
Dòng này in nghiêng, căn giữa, đặt ngay dưới tên phụ lục.

### 8.9. Khối ký kết cuối văn bản
Trình bày bảng **2 cột**, không có đường viền ngoài:

| Cột trái | Cột phải |
|---|---|
| **Nơi nhận:** | **TỔNG GIÁM ĐỐC** |
| *- HĐQT (để biết);* | *(Ký, đóng dấu)* |
| *- Kế toán trưởng (để thực hiện);* | |
| *- Toàn thể bộ phận Kế toán (để thực hiện);* | |
| *- Lưu VP, Phòng TC-KT.* | **VŨ HỒNG PHONG** |

### 8.10. Khối ký phụ lục (3 cột)
Phụ lục ký theo bảng 3 cột:

| NGƯỜI LẬP | KẾ TOÁN TRƯỞNG | P. GIÁM ĐỐC / TỔNG GIÁM ĐỐC |
|---|---|---|
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* |
| | | **VŨ HỒNG PHONG** |

### 8.11. Font chữ và định dạng tổng thể
| Yếu tố | Quy định |
|---|---|
| Font chữ | Times New Roman |
| Cỡ chữ thông thường | 12–13pt |
| Căn lề | Căn đều 2 lề (justify) |
| Ghi chú / chú thích | In nghiêng |
| Tiêu đề chương / mục lớn | In hoa, in đậm |
| Người ký cao nhất | TỔNG GIÁM ĐỐC — VŨ HỒNG PHONG |

### 8.12. Quy tắc áp dụng
> **Bắt buộc:** Mọi văn bản chính thức CTM soạn thảo (quyết định, hợp đồng, quy chế, biên bản, phụ lục) đều phải tuân thủ quy ước tại Mục 8 này.
> Khi soạn thảo file `.docx`, ưu tiên font Times New Roman, margin 2cm các phía, khổ A4.

---

## 9. NHẬT KÝ THỐNG NHẤT
- 15/05/2026: Cập nhật cấu trúc thư mục mở rộng và quy tắc quản lý biểu mẫu nghiêm ngặt.
- 17/05/2026: Bổ sung Mục 5 — Quy tắc quản lý INDEX.md: chỉ liệt kê file đã sync, không liệt kê file đang biên soạn trên Notion.
- 17/05/2026: Cập nhật Mục 3 — Trạng thái hệ thống: bổ sung nhánh A1 (HT Tài chính – Kế toán) với 10 file đã sync; cập nhật Mục B (Biểu mẫu) với 7 BM đã sync; áp dụng quy ước PL01 và PL02 [HOÀN THÀNH DỰ THẢO], còn lại [DỰ THẢO].
- 17/05/2026: Bổ sung Mục 8 — Quy ước văn phong trình bày văn bản CTM, căn cứ file MauVanPhong.docx đã thống nhất (bố cục quốc hiệu, số hiệu, căn cứ, điều khoản, bảng biểu, ký kết, font chữ).
