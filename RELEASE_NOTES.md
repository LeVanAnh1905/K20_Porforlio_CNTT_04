# Release Notes

## v7 - Bản bàn giao Portfolio Lab 5

- **Ngày cập nhật tài liệu:** 2026-10-30
- **Sản phẩm:** Portfolio cá nhân - HTML5/CSS3 tĩnh
- **Repository:** [K20_Porforlio_CNTT_04](https://github.com/LeVanAnh1905/K20_Porforlio_CNTT_04)
- **Bản mã nguồn gần nhất đã commit:** [`97f4d22d8e8057d9446db4e22959ce984d3fb57c`](https://github.com/LeVanAnh1905/K20_Porforlio_CNTT_04/commit/97f4d22d8e8057d9446db4e22959ce984d3fb57c)
- **Bản xuất bản:** [GitHub Pages](https://levananh1905.github.io/K20_Porforlio_CNTT_04/)

### Thay đổi chính

- Bổ sung README với mô tả chức năng thực tế, cây thư mục, cách chạy local, hướng dẫn kiểm tra và liên kết xuất bản/minh chứng.
- Chuẩn hóa tên nhật ký AI thành `AI_LOG.md` và ghi lại dữ kiện, quyết định, giới hạn kiểm chứng.
- Ghi nhận sản phẩm là website tĩnh có điều hướng theo mục, lưới dự án responsive, focus bàn phím và form kiểm tra bằng validation của trình duyệt.

### Lỗi đã sửa và thay đổi liên quan

Commit `97f4d22` có thông điệp "sửa 2 lỗi". Diff thực tế thay đổi tên hiển thị và một số nhãn/nội dung trợ giúp của form; commit không mô tả hai lỗi cụ thể. Không có đủ bằng chứng để gắn commit này với các ghi chú "Không hiện ảnh", "Không hiện đúng đường dẫn" hoặc "Lỗi sever 404".

### Hạn chế và trạng thái

- Form chỉ gửi dữ liệu giả bằng `GET` tới `ket-qua.html`; không gửi email, không có backend và dữ liệu được đưa vào URL.
- Tệp `kiem-tra-lab5.txt` còn ghi tên Bùi Đức Duy, trong khi trang và tài khoản GitHub xác định Lê Vân Anh. Cần xác nhận/đính chính hồ sơ trước khi nộp.
- Tại thời điểm cập nhật, `index.html` có chỉnh sửa chưa commit; README, nhật ký AI và release notes trong bản làm việc cũng chưa nằm trong commit `97f4d22`. Commit được liên kết ở trên là mốc mã nguồn đã có trên GitHub, không đại diện cho toàn bộ các chỉnh sửa local hiện tại.
- Chưa thực hiện kiểm thử local/browser cho form, bàn phím hoặc các viewport trong lần cập nhật tài liệu này.

### Tiếp tục kiểm tra và bàn giao

1. Xác nhận tên tác giả và nội dung minh chứng trong `kiem-tra-lab5.txt`.
2. Chạy local theo README; kiểm tra điều hướng, responsive, focus, validation và trang kết quả với dữ liệu giả.
3. Commit và push bản cuối, rồi thay liên kết commit phía trên bằng SHA chính xác của bản bàn giao.
4. Kiểm tra lại GitHub Pages sau khi xuất bản và xác nhận nó hiển thị đúng commit đã bàn giao.