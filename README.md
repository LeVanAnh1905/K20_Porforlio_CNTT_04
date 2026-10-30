# Portfolio cá nhân - Lab 5

- **Tên sản phẩm:** Portfolio cá nhân (Lab 5 - HTML5 và CSS3)
- **Tác giả:** Lê Vân Anh (trên trang giới thiệu là "Vân Ahn"); hồ sơ GitHub: [LeVanAnh1905](https://github.com/LeVanAnh1905).
- **Mô tả:** Website portfolio tĩnh giới thiệu cá nhân, kỹ năng, dự án và lộ trình học tập. Có bố cục responsive, điều hướng theo mục, trạng thái focus cho bàn phím và form kiểm tra dữ liệu ở phía trình duyệt.

## Liên kết

- **Mã nguồn:** [GitHub repository](https://github.com/LeVanAnh1905/K20_Porforlio_CNTT_04)
- **Website:** [GitHub Pages](https://levananh1905.github.io/K20_Porforlio_CNTT_04/)
- **Hồ sơ trên sản phẩm:** [Giới thiệu](https://levananh1905.github.io/K20_Porforlio_CNTT_04/#gioi-thieu)
- **Minh chứng Lab 5:** [kiem-tra-lab5.txt](kiem-tra-lab5.txt)
- **Nhật ký AI:** [AI_LOG.md](AI_LOG.md)
- **Ghi chú bàn giao:** [RELEASE_NOTES.md](RELEASE_NOTES.md)

GitHub Pages đã được mở kiểm tra ngày 2026-10-30. Trang web là bản đã xuất bản; thay đổi đang có trong máy nhưng chưa commit/push có thể chưa xuất hiện trên Pages.

## Cấu trúc

```text
.
|-- index.html          # Portfolio và form liên hệ mô phỏng
|-- ket-qua.html        # Trang kết quả sau khi gửi form
|-- css/
|   `-- style.css       # Giao diện responsive và trạng thái tương tác
|-- kiem-tra-lab5.txt   # Ghi chú kiểm tra/minh chứng hiện có
|-- README.md
|-- AI_LOG.md
`-- RELEASE_NOTES.md
```

## Chạy local

Không cần cài thư viện hoặc build. Từ thư mục dự án, có thể mở `index.html` trực tiếp; hoặc chạy server tĩnh bằng Python:

```powershell
py -m http.server 8000
```

Sau đó mở <http://localhost:8000/>. Dừng server bằng `Ctrl+C`.

## Cách kiểm tra

1. Mở `index.html` hoặc URL Pages; kiểm tra các liên kết Giới thiệu, Kỹ năng, Dự án, Lộ trình và Liên hệ.
2. Thu/phóng cửa sổ để xem lưới dự án đổi từ một cột sang hai hoặc ba cột theo chiều rộng màn hình.
3. Dùng `Tab` và `Shift+Tab` để đi qua liên kết, trường nhập và nút; kiểm tra viền focus nhìn thấy được.
4. Trong form, thử gửi khi để trống, nhập email sai định dạng, hoặc nội dung ngắn hơn 10 ký tự; trình duyệt sẽ kiểm tra các thuộc tính `required`, `type=email` và `minlength`.
5. Gửi dữ liệu giả hợp lệ để mở `ket-qua.html`. Form dùng `GET`, nên dữ liệu nằm trên URL; không có email được gửi và không có dữ liệu lưu ở máy chủ. Không nhập thông tin thật hoặc nhạy cảm.

## Xuất bản và trạng thái bàn giao

Trang được xuất bản bằng GitHub Pages từ repository trên. Mã nguồn hiện có trên GitHub tại commit [`97f4d22`](https://github.com/LeVanAnh1905/K20_Porforlio_CNTT_04/commit/97f4d22d8e8057d9446db4e22959ce984d3fb57c). Các chỉnh sửa tài liệu trong bản làm việc này chưa nằm trong commit đó; hãy cập nhật liên kết commit sau khi commit/push bản bàn giao cuối.

**Lưu ý hồ sơ:** Trang và tài khoản GitHub xác định tác giả là Lê Vân Anh, nhưng `kiem-tra-lab5.txt` hiện ghi tên Bùi Đức Duy và mã sinh viên 2071020057. Hãy xác nhận/đính chính tệp minh chứng trước khi nộp để hồ sơ nhất quán.
