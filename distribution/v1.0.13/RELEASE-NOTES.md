# Chấm công cửa hàng LDB 1.0.13

- **Mẫu lịch tuần và sao chép 7 ngày:** chuẩn bị ca cho nhiều nhân viên, xem trước rồi xác nhận. Ca trùng và ca thuộc tháng đã chốt được bỏ qua, không ghi đè. Sửa mẫu không sửa lịch đã áp dụng. Hỗ trợ ca qua đêm.
- **Công của tôi:** nhân viên nhập mã/PIN riêng để xem công và lịch cá nhân tại máy cửa hàng. Không hiển thị lương hoặc dữ liệu người khác. Tự đóng sau 2 phút không thao tác, tối đa 5 phút; chuyển sang tab khác sẽ đóng thông tin. Đổi PIN hoặc khóa tài khoản thu hồi phiên cũ.
- **Yêu cầu bổ sung công:** nhân viên xin bổ sung cả ca hoặc giờ tan ca đang mở, ghi lý do. Chờ/từ chối không cộng giờ. Quản lý đối soát rồi duyệt/từ chối và ghi lý do; chống duyệt lặp, trùng công hoặc duyệt vào tháng đã chốt. Giữ lượt chấm gốc và lịch sử.
- **Theo dõi trả lương:** ghi nhận trả từng phần sau khi chốt, xem còn phải trả, ngày/phương thức/ghi chú và xuất CSV. Không tính lại tạm ứng đã trừ trong lương, không tự chuyển tiền. Hủy ghi nhận sai cần mật khẩu quản lý và lý do, giữ lịch sử. Mở/chốt lại tháng giữ khoản trả cũ và cảnh báo nếu trả vượt.
- **Báo cáo theo khoảng ngày:** tuần, nửa tháng hoặc kỳ 26–25, tối đa 366 ngày; lọc nhân viên, xem tổng hợp/chi tiết và xuất CSV để mở Excel hoặc Google Sheets. Chỉ tổng hợp công, không quy đổi ra lương hoặc thay bảng lương tháng đã chốt.

## Cài đặt và cập nhật
Tải thêm bản sao lưu, chạy **LDB-Cai-Dat-Cham-Cong-1.0.13.exe** trên cùng máy/Windows, xác nhận quyền quản trị và chờ hoàn tất. Mở LDB trên Desktop rồi kiểm tra dữ liệu.

**Giữ nguyên dữ liệu, mã kích hoạt, thời hạn, cách tính lương cũ và tháng đã chốt.** Không cần cấp lại mã chỉ vì lên 1.0.13. Các phần tính lương, tạo báo cáo lương và xác minh bản quyền giữ nguyên so với 1.0.12; chức năng mới chỉ ghi thay đổi khi người dùng chủ động xác nhận.

PDF **LDB-Huong-Dan-Su-Dung.pdf** có **21 trang**: 10–12 Google Drive; 14 dùng thử; 15–16 tính lương; 17–18 thiết lập/lịch ca/in bộ phiếu; 19–21 các chức năng mới. Có thêm file **LDB-Huong-Dan-Cap-Nhat-1.0.13.txt**.

Dùng thử 7 ngày. Gói mới **300.000đ/năm** hoặc **500.000đ/trọn đời phiên bản đã mua**, hỗ trợ 12 tháng; nâng cấp lớn tính riêng. Bản thử giữ giới hạn tự xuất Drive, chốt/mở lương và xuất/in phiếu lương. Hết thử vẫn xem và xuất dữ liệu cơ bản; không ghi/sửa công hoặc thêm thanh toán mới.

Đã qua 87 kiểm tra tự động, kiểm tra giao diện toàn bộ quy trình mới, quyền xem công cá nhân, thu hồi phiên, chống công/thanh toán trùng và kiểm tra nâng cấp từ 1.0.12 trong môi trường riêng. Lần quét Defender ngày 27/11/2026 không ghi nhận mối đe dọa; bộ cài chưa có chứng thư nhà phát hành Windows.

**Hotline / Zalo: 0355636456**