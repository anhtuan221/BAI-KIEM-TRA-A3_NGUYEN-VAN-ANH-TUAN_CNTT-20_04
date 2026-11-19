### 2. Tệp `CHANGELOG.md` (tạo ở thư mục gốc)

```markdown
# Nhật Ký Thay Đổi (CHANGELOG)

## V8 — Release Note (Phiên bản bàn giao hiện tại)
- **Thay đổi chính:**
  - Hoàn thiện giao diện trang dịch vụ cài đặt phần mềm cơ bản (`index.html`, `css/style.css`) với thông tin tác giả Nguyễn Văn Anh Tuấn.
  - Bổ sung 3 hình ảnh minh họa gói dịch vụ vào thư mục `assets/images/` và định dạng khung ảnh `.card-img`.
  - Bổ sung thuộc tính `data-package` và đoạn script xử lý sự kiện click để tự động chọn đúng gói dịch vụ trong biểu mẫu tư vấn khi người dùng bấm nút **Chọn gói này**.
  - Triển khai website công khai lên GitHub Pages và hoàn thiện bộ 4 tài liệu bàn giao V8 (`README.MD`, `CHANGELOG.MD`, `docs/evidence-index.MD`, `docs/AI_LOG.MD`).
- **Đã kiểm tra:**
  - Bấm kiểm tra toàn bộ liên kết điều hướng và nút chọn gói trên URL GitHub Pages công khai.
  - Kiểm tra hiển thị 3 ảnh minh họa trên URL GitHub Pages (đảm bảo đúng chữ hoa/thường và đường dẫn tương đối).
  - Kiểm tra bố cục responsive ở kích thước màn hình rộng (> 768px) và màn hình hẹp (< 768px).
- **Chưa kiểm tra / Giới hạn:**
  - Chưa có chức năng lưu trữ hoặc gửi dữ liệu biểu mẫu lên máy chủ (ngoài phạm vi website tĩnh).
  - Chưa kiểm tra trực tiếp trên thiết bị iPhone / trình duyệt Safari thật.

## V7 — Phiên bản phát triển trước đó
- Khởi tạo cấu trúc thư mục dự án, khung giao diện HTML5/CSS3 nháp ban đầu cho các khu vực Giới thiệu, Gói dịch vụ, Quy trình và Liên hệ.