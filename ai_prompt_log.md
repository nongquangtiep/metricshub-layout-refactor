# Nhật Ký Tương Tác AI (AI Prompt Log)

- **Prompt 1 (Audit Pain-points):** "Khi tôi cần một bố cục mà một phần tử con phải chiếm chính xác 2 hàng và 2 cột đan xen với các phần tử nhỏ khác, tại sao CSS Grid vượt trội hơn Flexbox và tại sao Flexbox lại tạo ra 'Div Soup'?"
  - *Ứng dụng:* Hiểu rõ cơ chế 2D của Grid giúp loại bỏ toàn bộ các thẻ `<div class="column">` lồng nhau.

- **Prompt 2 (Bootstrap Grid vs Pure Grid):** "Tại sao nên dùng Bootstrap 12 cột cho khu vực Pricing 3 thẻ thay vì tự viết CSS Grid hoặc Flexbox thuần?"
  - *Ứng dụng:* Tận dụng các lớp `row`, `col-12 col-md-4` và `h-100` để tự động hóa điểm ngắt Responsive mà không cần viết thêm dòng CSS nào.

- **Prompt 3 (Micro-layout & Gap):** "Làm thế nào để sử dụng thuộc tính `gap` đồng thời trong cả Flexbox (Navbar) và Grid (Dashboard) nhằm thay thế margin âm truyền thống?"
  - *Ứng dụng:* Dùng `gap: 16px` cho `.hub-navbar` và `.bento-dashboard` giúp code gọn sạch, không lo tràn viền ngoài.
