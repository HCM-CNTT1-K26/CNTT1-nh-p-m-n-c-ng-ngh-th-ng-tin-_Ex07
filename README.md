# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session11_Ex07
### 1. Phân tích lỗi & Cơ chế Auto TOC

* **Cơ chế:** Auto TOC quét theo **Outline Level** (Heading 1, 2, 3), không quét theo hình thức (cỡ chữ, tô màu, in đậm).
* **Lỗi cụ thể:** Toàn bộ 7 tiêu đề đều mang style **Normal** (văn bản thô) + chỉnh thủ công. Do đó Word coi toàn bộ file là đoạn văn thường $\rightarrow$ Auto TOC rỗng.
* **Tác hại lệch cấp (Dòng 2.1.1):** Nếu chọn nhầm H2 thay vì H3, dòng `2.1.1` sẽ bị đẩy ra ngang hàng với `2.1`, làm sai lệch khoảng thụt lùi (Indentation) và hỏng logic phân cấp logic cây.

---

### 2. Các bước sửa lỗi & Nghiệm thu

**Bước 1: Gán lại Style chuẩn bằng phím tắt**

* Click vào từng dòng và bấm tổ hợp phím tương ứng:
1.  Thông tin chung hội nghị $\rightarrow$ ** Ctrl + Alt + 1** (H1)
2.  Tên hội nghị  $\rightarrow$ ** Ctrl + Alt + 2** (H2)
3.  Thời gian & địa điểm $\rightarrow$ **`Ctrl + Alt + 2** (H2)
4.  Cơ cấu ban tổ chức $\rightarrow$ **Ctrl + Alt + 1** (H1)
5.  Ban Nội dung $\rightarrow$ **Ctrl + Alt + 2** (H2)
6. Tiểu ban Kỹ thuật $\rightarrow$ **Ctrl + Alt + 3** (H3)
7.  Lịch trình sự kiện $\rightarrow$ **Ctrl + Alt + 1** (H1)



**Bước 2: Chèn Mục lục**

* Đặt con trỏ ở trang đầu $\rightarrow$ **References** $\rightarrow$ **Table of Contents** $\rightarrow$ Chọn mẫu **Automatic Table**.

---

### 3. Xử lý bẫy nhảy trang

* **Trả lời:** Mục lục **KHÔNG** tự cập nhật số trang khi nội dung bị đẩy sang trang khác.
* **Thao tác sửa:**
1. Click vào khung Mục lục.
2. Nhấn phím **`F9`** (hoặc **`Fn + F9`**).
3. Chọn **Update page numbers only** (hoặc *Update entire table*) $\rightarrow$ Bấm **OK**.
