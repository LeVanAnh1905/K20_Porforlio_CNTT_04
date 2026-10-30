# AI_LOG - Portfolio cá nhân Lab 5

Ngày ghi: 2026-10-30

## Hiện tượng và dữ kiện ban đầu

Tệp nhật ký cũ chỉ ghi các dòng: "Không hiện ảnh", "Không hiện đúng đường dẫn", "Lỗi trang", "Lỗi sever 404". Tệp không có bước tái hiện, URL cụ thể, ảnh chụp, trình duyệt hoặc kết quả kiểm tra lại. Đây là ghi chú được giữ nguyên từ bản cũ, không phải kết luận rằng các lỗi đó vẫn còn hoặc đã được sửa.

Khi đối chiếu mã nguồn: dự án là HTML/CSS tĩnh gồm `index.html`, `ket-qua.html` và `css/style.css`; cấu trúc hiện tại không có tệp ảnh. Form liên hệ gửi bằng `GET` tới trang kết quả và ghi rõ không gửi email/lưu dữ liệu. Repository công khai và URL GitHub Pages đã mở được ngày 2026-10-30. Git cho thấy commit mới nhất là `97f4d22` (`sửa 2 lỗi`), còn `index.html` trong máy có chỉnh sửa chưa commit.

## Nhận định ban đầu trước khi nhận gợi ý

Các mô tả lỗi quá ngắn để xác định nguyên nhân hoặc khẳng định đã khắc phục. Cần kiểm tra trực tiếp cấu trúc, đường dẫn, trạng thái repo và trang xuất bản; không nên đưa vào tài liệu lời khẳng định kiểm thử nếu chưa chạy. Đây là nhận định của Copilot khi bắt đầu phiên cập nhật, không phải lời trích dẫn từ sinh viên.

## Công cụ, prompt và gợi ý

- **Công cụ:** GitHub Copilot trong VS Code; đọc tệp dự án, kiểm tra trạng thái/commit Git và mở URL repo/Pages.
- **Prompt (tóm tắt):** Cập nhật README, AI log và release notes theo yêu cầu bàn giao; đối chiếu sản phẩm thực tế; không tạo URL hoặc kết quả kiểm chứng chưa có.
- **Gợi ý của AI:** Mô tả đúng trang tĩnh và hành vi form; hướng dẫn cách chạy/kiểm tra; xác minh liên kết và commit; ghi rõ các điểm chưa kiểm tra hoặc chưa nhất quán.

## Quyết định và lý do

Quyết định biên tập được áp dụng trong phiên này: dùng mã nguồn, Git và URL công khai làm căn cứ; không kết luận các lỗi ảnh/đường dẫn/404 đã được sửa vì không có bước tái hiện hay bằng chứng kiểm tra lại; nêu rõ form chỉ mô phỏng và đánh dấu mâu thuẫn tên tác giả thay vì tự sửa nội dung minh chứng. Đây là lựa chọn của Copilot khi soạn bản nháp; sinh viên cần đọc, xác nhận hoặc điều chỉnh trước khi nộp để nhật ký thể hiện đúng quyết định của mình.

## Phần cập nhật

- Viết lại `README.md` theo chức năng, cấu trúc, chạy local, xuất bản và các bước kiểm tra hiện có.
- Đổi tên nhật ký thành `AI_LOG.md` và ghi lại nguồn gốc quan sát ban đầu cùng quyết định có căn cứ.
- Tạo `RELEASE_NOTES.md` cho bản v7; nêu phạm vi commit `97f4d22` theo diff thực tế và tình trạng thay đổi chưa commit.
- Không sửa HTML/CSS trong lần cập nhật tài liệu này. Thay đổi chưa commit có sẵn trong `index.html` được giữ nguyên.

## Thử lại và kết quả

- Đã mở repository GitHub và URL Pages ngày 2026-10-30; cả hai trả về nội dung tương ứng.
- Đã đọc mã nguồn, commit `97f4d22` và diff `index.html`; việc này xác nhận nội dung tài liệu, không thay thế kiểm thử tương tác.
- Chưa chạy website local, chưa gửi thử form trên trình duyệt và chưa kiểm tra từng kích thước màn hình. Vì vậy không ghi nhận các kiểm tra đó là đạt.
- Để kiểm tra tiếp: chạy `py -m http.server 8000`, thực hiện các bước trong README, rồi ghi lại trình duyệt, dữ liệu thử và kết quả thực tế tại đây.