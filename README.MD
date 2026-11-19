# TechSupport SV — Website Dịch Vụ Cài Đặt Phần Mềm Cơ Bản

## 1. Sản phẩm này là gì?
Website tĩnh (HTML5/CSS3) giới thiệu các gói dịch vụ cài đặt phần mềm học tập, văn phòng, công cụ lập trình cơ bản và quy trình hỗ trợ kỹ thuật dành cho sinh viên. Dự án được thực hiện bởi **Nguyễn Văn Anh Tuấn** phục vụ học phần **FIT4014 – Thiết kế web và triển khai hệ thống phần mềm**.

## 2. Demo
- **URL GitHub Pages:** `https://anhtuan221.github.io/BAI-KIEM-TRA-A3_NGUYEN-VAN-ANH-TUAN_CNTT-20_04/
- **Repository mã nguồn:** `https://github.com/anhtuan221/BAI-KIEM-TRA-A3_NGUYEN-VAN-ANH-TUAN_CNTT-20_04.git
- **Phiên bản bàn giao:** `v8` (Commit: `[7a2a99b]`)

## 3. Tính năng hiện có
- Xem thông tin chi tiết, hình ảnh minh họa và mức phí tham khảo của 3 gói dịch vụ (Học tập & Văn phòng, Môi trường Lập trình, Bảo trì & Tối ưu máy).
- Bấm điều hướng nhanh tới các khu vực (`Trang chủ`, `Gói dịch vụ`, `Quy trình`, `Liên hệ`) trên thanh menu đầu trang.
- Bấm nút **Chọn gói này** ở từng thẻ dịch vụ để cuộn xuống biểu mẫu tư vấn và tự động chọn đúng gói dịch vụ tương ứng.
- Tự động điều chỉnh bố cục hiển thị (responsive) từ lưới 3 cột trên màn hình rộng sang 1 cột dọc trên màn hình hẹp.

## 4. Cách mở hoặc chạy thử
- **Cách 1 — Xem trực tiếp trên web (Khuyên dùng):**
  1. Mở đường dẫn URL GitHub Pages ở Mục 2 bằng trình duyệt web (Chrome, Edge, Firefox).
  2. Bấm thử các liên kết trên thanh điều hướng hoặc nút **Chọn gói này** ở từng gói dịch vụ để kiểm tra tương tác.
- **Cách 2 — Chạy cục bộ trên máy cá nhân:**
  1. Tải hoặc clone repository về máy tính.
  2. Mở trực tiếp tệp `index.html` ở thư mục gốc bằng trình duyệt web (không cần cài đặt thêm máy chủ).

## 5. Cấu trúc thư mục
```text
dich-vu-cai-phan-mem/
├── index.html                  # Trang nội dung chính và script chọn gói dịch vụ
├── css/
│   └── style.css               # Tệp định dạng giao diện và quy tắc responsive
├── assets/
│   └── images/                 # Hình ảnh minh họa cho 3 gói dịch vụ
│       ├── hoc-tap.png
│       ├── lap-trinh.png
│       └── bao-tri.png
├── docs/
│   ├── evidence-index.MD       # Bảng đối chiếu tiêu chí và minh chứng kiểm thử
│   └── AI_LOG.MD               # Nhật ký khai báo việc sử dụng công cụ AI
├── README.MD                   # Tài liệu giới thiệu và hướng dẫn sử dụng dự án
└── CHANGELOG.MD                # Lịch sử thay đổi các phiên bản (V7 -> V8)
6. Đã kiểm tra
Mở URL GitHub Pages công khai trên trình duyệt máy tính: toàn bộ giao diện CSS và 3 hình ảnh minh họa hiển thị đầy đủ, không lỗi đường dẫn.

Bấm lần lượt 4 mục trên thanh điều hướng và 3 nút Chọn gói này: trang cuộn đúng khu vực và ô chọn Gói dịch vụ quan tâm tự cập nhật đúng gói đã bấm.

Thu hẹp cửa sổ trình duyệt xuống dưới 768px (chế độ màn hình hẹp): các thẻ dịch vụ xếp dọc 1 cột gọn gàng, không xuất hiện thanh cuộn ngang.

7. Giới hạn / Chưa kiểm tra
Biểu mẫu Gửi Yêu Cầu Tư Vấn mới dừng ở mức trình bày giao diện tĩnh (HTML5/CSS3), chưa kết nối cơ sở dữ liệu hoặc gửi email tự động.

Chưa kiểm tra hiển thị trực tiếp trên thiết bị di động thật sử dụng hệ điều hành iOS / trình duyệt Safari.

8. Nguồn và khai báo AI
Nguồn hình ảnh minh họa (Miễn phí bản quyền theo Unsplash License):

assets/images/hoc-tap.png: Ảnh của Nguyen Phan Nam Anh trên Unsplash (https://unsplash.com/photos/a-laptop-computer-sitting-on-top-of-a-wooden-desk-v6vxTvqeVuo).

assets/images/lap-trinh.png: Ảnh của Ilnur trên Unsplash (https://unsplash.com/photos/laptop-screen-displaying-lines-of-code-sxK8RUCpqoQ).

assets/images/bao-tri.png: Ảnh trên Unsplash (https://unsplash.com/photos/close-up-view-of-a-laptops-internal-components-and-fan-YunxbqyMGYo).
