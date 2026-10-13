# Landing Page CodeGym Career — Material Design

Bài thực hành HTML/CSS/JS xây dựng lại giao diện dựa trên nội dung:
https://codegym.vn/codegym-career/

## Mở bài
Mở index.html bằng Chrome hoặc Edge. Ba file index.html, style.css và script.js phải nằm cùng thư mục.
Cần Internet để tải Bootstrap, MDBootstrap, Font Awesome và Roboto từ CDN theo đề.
CSS tùy chỉnh và menu JavaScript có phương án hoạt động khi CDN không tải được.

## Thư viện
- Bootstrap 4.5.0
- MDBootstrap 4.19.1
- jQuery 3.5.1, Popper 1.14.4
- Font Awesome 5.11.2, Roboto

## Phân tích nội dung và lựa chọn component
| Nội dung | Component / thiết kế |
|---|---|
| Menu và thương hiệu | Navbar responsive, sticky |
| Giới thiệu chương trình | Grid hai cột, CTA, hình minh họa HTML/CSS |
| Lợi ích | Card, icon, bóng đổ |
| Java / PHP | Card, chip, List Group |
| Đánh giá / dự án / nghề nghiệp | Danh sách các chặng |
| Sản phẩm học viên | Card, liên kết video từ trang nguồn |
| Câu hỏi thường gặp | details / summary |
| Liên hệ | CTA đến trang chính thức và liên kết gọi |
| Chân trang | Page footer và nguồn |

Bố cục ưu tiên thông tin từ trên xuống, tiêu đề và phần nội dung chính ở bên trái; CTA đầu trang và cuối trang dẫn đến các bước tiếp theo.
Các chặng là cách nhóm nội dung phục vụ trình bày, không phải lịch học chính thức.
Dùng placeholder CSS thay ảnh dự án. Không tự tạo lời chứng thực hoặc số liệu việc làm.
Nội dung khóa học được tóm lược từ trang nguồn ngày 13/10/2026; cần xác nhận thông tin tuyển sinh với CodeGym.
Logo chữ là bản dựng cho bài tập. Footer xác định đây không phải website chính thức.

## Tương tác
- Menu nhỏ: mở/đóng, chọn liên kết để đóng, Escape để đóng và đưa focus về nút.
- Liên kết nội bộ đến đúng phần.
- Hai thẻ dự án dẫn đến URL video được dẫn trên trang nguồn.
- CTA tư vấn mở trang CodeGym; nút hotline dùng tel.
- Trang không nhận hoặc gửi dữ liệu đăng ký.
- FAQ hỗ trợ bàn phím bằng phần tử HTML details.
- Có skip link, focus rõ ràng và prefers-reduced-motion.

## Kiểm tra đã thực hiện
- JavaScript: node --check.
- Mô phỏng hành vi menu: mở/đóng, Escape, chọn liên kết, click bên ngoài, đổi kích thước sang desktop.
- Kiểm tra cấu trúc: ID duy nhất, đích liên kết nội bộ, file CSS/JS tồn tại.
- Kiểm tra cân bằng dấu ngoặc CSS; chưa chạy bộ phân tích CSS chuyên dụng.
- Tính tương phản các cặp chữ/nền chính bằng công thức sRGB.
- Có breakpoint 575px, 768px, 992px; grid chuyển về một cột trên màn hình nhỏ.

Chưa kiểm tra trực quan trong trình duyệt hoặc kiểm tra tải CDN/video tại môi trường tạo file. Trước khi nộp, mở ở kích thước khoảng 390px và 1366px, kiểm tra tràn ngang, menu và CTA.

## Nộp bài
Tạo repository Public, tải index.html, style.css, script.js và README.md lên cùng cấp.
Dán link repository vào mục nộp bài.
