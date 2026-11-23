# Bảng Minh Chứng Kiểm Thử (Evidence Index)

| Tiêu chí / Tuyên bố | Phép thử thực hiện | Kết quả thật |
| :--- | :--- | :--- | :--- |
| **TC3a / R1:** Website hiển thị đầy đủ 3 gói dịch vụ kèm hình ảnh và giá tham khảo | Mở URL GitHub Pages trên trình duyệt màn hình rộng, kiểm tra hiển thị nội dung và tải ảnh của 3 thẻ gói dịch vụ | Cả 3 thẻ gói dịch vụ hiển thị đầy đủ tên gói, hình ảnh minh họa rõ nét, danh sách phần mềm và mức phí tham khảo | 
| **TC3a / R2:** Thanh điều hướng và nút chọn gói hoạt động chính xác | Bấm lần lượt 4 mục trên menu (`Trang chủ`, `Gói dịch vụ`, `Quy trình`, `Liên hệ`) và bấm nút **Chọn gói này** ở Gói 2, Gói 3 trên URL Pages | Menu cuộn mượt tới đúng từng phần; bấm **Chọn gói này** ở gói nào thì ô chọn trong form tự động chuyển sang đúng gói đó | 
| **TC2a / R3:** Giao diện hiển thị tương thích (Responsive) trên màn hình hẹp | Thu hẹp cửa sổ trình duyệt xuống chiều rộng `< 768px` (hoặc bật chế độ điện thoại trong DevTools) | Lưới 3 cột tự chuyển thành 1 cột dọc, thanh menu xếp gọn, chữ dễ đọc và không bị tràn ngang | 
| **TC4b:** Sửa lỗi nút **Chọn gói này** không tự đổi gói trong biểu mẫu | Phát hiện lỗi ở bản nháp (bấm Gói 2 vẫn giữ Gói 1) → thêm `data-package` và script trong `index.html` → đẩy lên Pages và bấm thử lại | Sau khi sửa và push lại, bấm nút **Chọn gói này** ở Gói 2 và Gói 3 đều tự động chọn đúng giá trị tương ứng | 
| **TC3b:** URL GitHub Pages hoạt động công khai và khớp phiên bản `v8` | Mở URL GitHub Pages bằng cửa sổ ẩn danh của trình duyệt và đối chiếu với trạng thái deploy của commit gắn tag `v8` | Trang web tải thành công ở chế độ ẩn danh, nội dung hiển thị trùng khớp với mã nguồn của tag `v8` 
