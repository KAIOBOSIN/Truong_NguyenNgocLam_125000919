# NHẬT KÝ PROMPT ENGINEERING (VIBE CODING LOG)

- **Họ và tên:** Nguyễn Ngọc Lam Trường
- **MSSV:** 125000919
- **Tên đề tài Website:** Portfolio cá nhân
- **Công cụ AI đã sử dụng:** ChatGPT

## 1. Yêu cầu ban đầu (System/Initial Prompt)

> Hãy xây dựng một website Portfolio cá nhân cho Nguyễn Ngọc Lam Trường, sinh viên ngành Công nghệ thông tin. Website có giao diện hiện đại, chuyên nghiệp, tông màu tối kết hợp xanh ngọc và tím. Nội dung gồm trang chủ, giới thiệu bản thân, kỹ năng, dự án tiêu biểu, định hướng học tập và thông tin liên hệ. Sử dụng HTML5 Semantic với các thẻ header, nav, main, section, article và footer. Tách mã nguồn thành index.html, style.css và script.js. Sử dụng CSS Variables trong :root, bố cục Flexbox/Grid và thiết kế responsive. Tích hợp Animate.css, AOS, hiệu ứng :hover và :focus bằng CSS. Tạo thêm PROMPT_LOG.md ghi lại quá trình sử dụng AI.

## 2. Quá trình tinh chỉnh & Giải quyết sự cố (Iteration Iterations)

### Lần 1: Dựng khung Semantic HTML & CSS Variable
- **Prompt đã dùng:** Xây dựng cấu trúc bằng HTML5 Semantic, sử dụng header, nav, main, section, article và footer đúng ngữ nghĩa. Khai báo CSS Variables trong :root để quản lý màu sắc, font chữ và spacing.
- **Kết quả AI tạo ra:** Website được chia thành các khu vực giới thiệu, kỹ năng, dự án, định hướng và liên hệ; màu sắc và khoảng cách được quản lý bằng biến CSS.
- **Nhận xét & Tinh chỉnh của SV:** Kiểm tra các liên kết điều hướng và nội dung section. Ưu tiên dùng thẻ semantic phù hợp, tránh lạm dụng div không có ý nghĩa.

### Lần 2: Tích hợp thư viện Animate.css & AOS
- **Prompt đã dùng:** Tích hợp Animate.css cho tiêu đề và phần Hero. Dùng AOS để tạo hiệu ứng khi cuộn đến các section. Khởi tạo AOS bằng JavaScript sau khi DOM tải xong.
- **Kết quả AI tạo ra:** Animate.css được liên kết trong head và áp dụng cho phần Hero; các khu vực nội dung sử dụng thuộc tính data-aos.
- **Thách thức gặp phải:** Hiệu ứng phụ thuộc vào việc tải thư viện từ CDN và khởi tạo AOS đúng thời điểm.
- **Cách sửa prompt (Debug prompt):** Kiểm tra URL CDN, thứ tự tải script và chỉ gọi AOS.init khi thư viện tồn tại. Đảm bảo nội dung vẫn đọc được nếu hiệu ứng không hoạt động.

### Lần 3: Hoàn thiện responsive và tương tác
- **Prompt đã dùng:** Dùng CSS Grid, Flexbox và media queries để website hiển thị tốt trên máy tính, máy tính bảng và điện thoại. Thêm menu di động, hiệu ứng hover/focus và nút quay lại đầu trang.
- **Kết quả AI tạo ra:** Bố cục tự điều chỉnh theo chiều rộng màn hình, menu di động có thể mở/đóng và các nút có trạng thái tương tác rõ ràng.
- **Nhận xét & Tinh chỉnh của SV:** Cần chạy thử trên nhiều kích thước màn hình, kiểm tra liên kết và thay thông tin mẫu bằng thông tin thật.

## 3. Đánh giá cá nhân về quá trình Vibe Coding

- **AI đã giúp bạn tiết kiệm thời gian ở phần nào nhất?**

AI giúp em tiết kiệm thời gian khi dựng cấu trúc HTML, xây dựng giao diện CSS, thiết kế responsive và viết JavaScript cho các tương tác cơ bản. Nhờ đó, em có thể tập trung hơn vào việc kiểm tra và hoàn thiện sản phẩm.

- **Bài học rút ra khi đặt câu hỏi (Prompt) cho AI trong thiết kế web?**

Em nhận thấy prompt cần nêu rõ mục tiêu, phong cách giao diện, cấu trúc mã nguồn và yêu cầu kỹ thuật. Khi gặp lỗi, cần mô tả đúng biểu hiện để AI hỗ trợ kiểm tra phần liên quan. Sau khi nhận mã nguồn, em vẫn phải tự chạy thử, kiểm tra và chỉnh sửa thay vì phụ thuộc hoàn toàn vào AI.

> **Lưu ý:** Hãy điều chỉnh phần nhật ký để phản ánh đúng quá trình bạn thực sự thực hiện và kiểm thử website.
