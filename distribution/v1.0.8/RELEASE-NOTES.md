# Chấm công cửa hàng LDB 1.0.8

Bản cập nhật miễn phí trong dòng 1.x, giữ nhân viên, PIN, mật khẩu quản lý, giờ công, ảnh, lương và mã kích hoạt trên cùng máy/Windows. Thời hạn gói đang dùng được giữ nguyên.

## Khách đang dùng 1.0.7: cập nhật theo các bước này

1. Đăng nhập đúng tài khoản Windows đã dùng chấm công. Hoàn tất lượt chấm đang thao tác, tạo và tải thêm một bản sao lưu ra nơi riêng.
2. Trong LDB, mở **Sao lưu & Thiết lập > Phiên bản & Cập nhật > Kiểm tra bản mới**, rồi chọn tải bản cập nhật. Cũng có thể tải bộ cài trong **Assets** bên dưới.
3. Sau khi tải xong, thoát bản LDB cũ từ biểu tượng ở khay gần đồng hồ Windows.
4. Mở **LDB-Cai-Dat-Cham-Cong-1.0.8.exe**. Chủ cửa hàng cho phép quyền quản trị Windows hoặc nhập tài khoản quản trị khi Windows hỏi. Bấm **Cài đặt / Cập nhật** và chờ hoàn tất; không tắt máy khi đang chuyển dữ liệu.
5. Mở biểu tượng **Chấm công cửa hàng LDB** trên Desktop, kiểm tra lại nhân viên và bảng công/lương gần nhất. Không cần mua hay cấp lại mã chỉ vì cập nhật 1.0.8.

Bộ cài sao lưu trước khi thay chương trình, đối chiếu dữ liệu khi chuyển sang vùng bảo vệ và giữ bản gốc. Nếu phát hiện dữ liệu không hợp lệ, thiếu dữ liệu hoặc sai tài khoản Windows, bộ cài dừng để hỗ trợ đối chiếu. Giữ nguyên các thư mục và liên hệ LDB; tránh tạo lại nhân viên vào bảng trống ngoài dự kiến.

## Những thay đổi chính

- Tách lưu dữ liệu/bản quyền sang dịch vụ Windows riêng; tài khoản nhân viên Standard không sửa trực tiếp được vùng dữ liệu bảo vệ.
- Sửa khôi phục nhận nhầm file SQLite sai cấu trúc và cài sửa chữa khi chương trình thiếu file.
- Sao lưu hoàn chỉnh được công bố sau kiểm tra; thêm chính sách giữ bản sao theo lịch/dung lượng.
- Mặc định giữ toàn bộ ảnh cũ. Quản lý chủ động xác nhận thời gian lưu nếu muốn dọn ảnh, giữ nguyên giờ công/lương.
- Ổ gần đầy có thể bỏ ảnh kèm ghi chú để ưu tiên ghi công; camera lỗi vẫn được chấm theo thiết kế.
- Giữ/cập nhật biểu tượng Desktop và đăng ký khởi động Windows; nâng runtime lên bản đã vá bảo mật.

## Tài liệu

- [Hướng dẫn tải và cài đặt trên GitHub](https://github.com/longnguyenktqd/ldb-cham-cong-releases#2-tải-đúng-file-bộ-cài)
- [Tải PDF sử dụng có hình minh họa - 10 trang](https://github.com/longnguyenktqd/ldb-cham-cong-releases/releases/download/v1.0.8/LDB-Huong-Dan-Su-Dung.pdf)
- [Hướng dẫn cập nhật chi tiết cho khách cũ](https://github.com/longnguyenktqd/ldb-cham-cong-releases/releases/download/v1.0.8/LDB-Huong-Dan-Cap-Nhat-1.0.8.txt)

Nhân viên nên dùng **Windows Standard**; chủ cửa hàng giữ riêng tài khoản quản trị Windows. Sau khi đổi tài khoản Windows, kiểm tra lại Google Drive có chạy và đồng bộ đúng thư mục báo cáo. Dịch vụ dữ liệu chạy nền; đóng trình duyệt không tắt dịch vụ.

Bộ cài chưa có chứng thư nhà phát hành Windows và có thể gặp cảnh báo chưa xác minh. Chỉ tải đúng kênh LDB, giữ Windows Defender hoạt động; gửi thông báo lỗi để được kiểm tra. Lần quét Defender ngày 25/11/2026 không ghi nhận phát hiện, không phải cam kết mọi antivirus đều không cảnh báo.

**Hotline / Zalo hỗ trợ: 0355636456.**
