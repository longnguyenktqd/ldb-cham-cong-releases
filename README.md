# Chấm công cửa hàng LDB

Phần mềm chấm công tại máy cửa hàng, có ảnh đối chiếu, bảng công và báo cáo lương cho kế toán.

**Hotline / Zalo hỗ trợ: [0355636456](https://zalo.me/0355636456)**

## Tải bộ cài và hướng dẫn

- **[TẢI BỘ CÀI WINDOWS MỚI NHẤT](https://github.com/longnguyenktqd/ldb-cham-cong-releases/releases/latest)**
- **[XEM HƯỚNG DẪN SỬ DỤNG PDF - 13 TRANG](docs/LDB-Huong-Dan-Su-Dung.pdf)**
- **[TẢI FILE PDF VỀ MÁY](https://github.com/longnguyenktqd/ldb-cham-cong-releases/releases/latest/download/LDB-Huong-Dan-Su-Dung.pdf)**

Khách chỉ cần bộ cài `.exe`. Tài liệu PDF có thể mở trên máy tính hoặc điện thoại để xem từng bước.

## Cập nhật từ 1.0.7 lên 1.0.8

**[Xem hướng dẫn cập nhật giữ dữ liệu và mã kích hoạt](https://github.com/longnguyenktqd/ldb-cham-cong-releases/releases/latest/download/LDB-Huong-Dan-Cap-Nhat-1.0.8.txt).**

Tạo và tải thêm bản sao lưu, dùng đúng tài khoản Windows cũ, thoát LDB ở khay hệ thống rồi chạy bộ cài 1.0.8 bằng quyền quản trị Windows. Bộ cài chuyển dữ liệu sang dịch vụ bảo vệ riêng và giữ mã kích hoạt cùng thời hạn gói cũ. Mở biểu tượng Desktop để kiểm tra lại nhân viên, công và lương.

Khách dùng bản có kiểm tra cập nhật có thể bấm **Kiểm tra bản mới** trong phần mềm. Khi bật kiểm tra tự động, thông báo xuất hiện ở lần kiểm tra tiếp theo; quản lý vẫn cần tải và chạy bộ cài. Máy đã dùng 1.0.8 sẽ tự tạm dừng dịch vụ khi cài cập nhật sau này.

## 1. Chuẩn bị trước khi cài

- Một máy tính Windows 64 bit dùng chấm công tại cửa hàng; nên dùng Windows 10/11 đã cập nhật.
- Có Internet khi tải bộ cài, đồng bộ Google Drive và kiểm tra phiên bản mới. Sau khi thiết lập, chấm công có thể hoạt động khi mất mạng.
- Webcam USB hoặc camera laptop nếu muốn chụp ảnh đối chiếu. Khi camera lỗi, phần mềm vẫn cho ghi công và ghi chú thiếu ảnh.
- Chủ cửa hàng chuẩn bị quyền quản trị Windows nếu bộ cài yêu cầu.

**Đang dùng bản cũ?** Trước tiên tải thêm một bản sao lưu, đăng nhập đúng tài khoản Windows đã dùng chấm công và thoát bản LDB cũ ở khay gần đồng hồ nếu đang chạy. Giữ nguyên dữ liệu và mã kích hoạt hiện có.

## 2. Tải đúng file bộ cài

1. Bấm **TẢI BỘ CÀI WINDOWS MỚI NHẤT** ở đầu trang.
2. Tại trang phát hành, tìm phần **Assets**; bấm để mở danh sách nếu đang thu gọn.
3. Bấm file có tên dạng **`LDB-Cai-Dat-Cham-Cong-X.Y.Z.exe`**. `X.Y.Z` là số phiên bản, ví dụ `1.0.8`.
4. Chờ trình duyệt tải xong, rồi mở thư mục **Downloads / Tải xuống**.

Để cài phần mềm, chọn đúng file **`.exe`**. Các mục **Source code (zip)**, **Source code (tar.gz)** và **`ldb-update.json`** phục vụ mục đích khác; khách không cần mở chúng để cài.

## 3. Chạy bộ cài

1. Nhấp đúp file `.exe` vừa tải.
2. Nếu Windows hỏi quyền quản trị, nhờ chủ cửa hàng xác nhận hoặc nhập tài khoản quản trị Windows.
3. Bấm **Cài đặt** hoặc **Cài đặt / Cập nhật**, theo nút hiển thị trong phiên bản đang dùng.
4. Chờ thông báo cài đặt thành công. Giữ máy bật trong lúc cài hoặc chuyển dữ liệu.
5. Nhấp biểu tượng **Chấm công cửa hàng LDB** trên **Desktop / Màn hình nền**. Một số phiên bản tự mở ngay sau khi cài.

**Nếu trình duyệt hoặc Windows chặn:** kiểm tra đã tải từ đúng kho GitHub này, giữ lại thông báo và liên hệ hotline/Zalo để LDB kiểm tra. Không tắt antivirus chỉ để cài. Bộ cài chưa có chứng thư nhà phát hành Windows có thể xuất hiện cảnh báo chưa xác minh nhà phát hành.

## 4. Kích hoạt và thiết lập cửa hàng

Với máy chưa kích hoạt:

1. Trên màn hình bản quyền, bấm **Sao chép mã máy**.
2. Gửi mã máy cho LDB qua Zalo **0355636456** để được cấp mã theo gói đã thỏa thuận.
3. Dán nguyên mã kích hoạt được cấp, bấm **Kích hoạt / Gia hạn** và mở phần mềm chấm công.

Sau khi kích hoạt lần đầu:

1. Bấm **Thiết lập cửa hàng**.
2. Nhập tên cửa hàng, tạo mật khẩu quản lý từ **10 ký tự** và nhập lại để xác nhận.
3. Bấm **Tạo cửa hàng**.
4. Vào **Nhân viên**, bấm **Thêm nhân viên**; nhập mã, họ tên và PIN riêng cho từng người.
5. Bấm **Khóa quản lý** để về màn hình nhân viên.

Máy đã có cửa hàng dùng lại tài khoản quản lý và dữ liệu hiện có. Nếu sau cập nhật thấy bảng công trống ngoài dự kiến, liên hệ LDB trước khi tạo lại nhân viên hoặc khôi phục dữ liệu.

## 5. Kiểm tra đã cài và mở thành công

- Có biểu tượng **Chấm công cửa hàng LDB** trên Desktop.
- Mở biểu tượng thấy màn hình kích hoạt, màn hình chào mừng hoặc màn hình chấm công nếu máy đã thiết lập.
- Sau khi thêm nhân viên, màn hình chấm công có ô **Mã nhân viên**, **Mã PIN**, nút **Vào ca** và **Tan ca**.
- Quản lý đăng nhập xem được nhân viên và bảng công. Chỉ thử ghi nhận một ca khi đã thống nhất đây là dữ liệu thử hoặc lượt chấm thực tế.

Phần mềm chạy tại máy cửa hàng. Địa chỉ `127.0.0.1` là địa chỉ trên chính máy đã cài; điện thoại cùng WiFi không dùng địa chỉ đó để chấm công.

## 6. Hướng dẫn sử dụng bằng PDF

**[Mở bản PDF đầy đủ](docs/LDB-Huong-Dan-Su-Dung.pdf)** hoặc **[tải PDF về máy](https://github.com/longnguyenktqd/ldb-cham-cong-releases/raw/refs/heads/main/docs/LDB-Huong-Dan-Su-Dung.pdf)**.

**Đã bổ sung 3 trang Google Drive chi tiết (trang 10-12):** cài Drive, chọn đúng thư mục báo cáo, kiểm tra đồng bộ, chia sẻ cho kế toán và xử lý lỗi thường gặp.

Tài liệu có hình minh họa và hướng dẫn:

| Trang | Nội dung |
|---|---|
| 1 | Tải bộ cài và cài đặt thành công |
| 2 | Kích hoạt, tạo tài khoản quản trị |
| 3 | Làm quen giao diện quản trị |
| 4 | Tạo nhân viên, đổi PIN, khóa người nghỉ việc |
| 5 | Nhân viên tự check-in / check-out |
| 6 | Quản lý kiểm tra, bổ sung và điều chỉnh công |
| 7 | Thiết lập lương cố định, thưởng, điều chỉnh, chốt tháng |
| 8 | Xuất Excel theo tháng/ngày và báo cáo cho kế toán |
| 9 | Xem báo cáo từ xa qua Google Drive, sao lưu và tự mở cùng Windows |
| 10 | Google Drive: cài đặt, đăng nhập Gmail và chọn thư mục đồng bộ |
| 11 | Google Drive: xem từ xa, chia sẻ cho kế toán và kiểm tra bản mới |
| 12 | Google Drive: xử lý lỗi, hết dung lượng, file bị khóa và sai tài khoản |
| 13 | Cập nhật an toàn và xử lý sự cố thường gặp |

## Lưu ý khi vận hành

- Giữ riêng mật khẩu quản lý và quyền quản trị Windows. Nhân viên nên dùng tài khoản Windows **Standard**.
- Khóa quản lý trước khi giao máy cho nhân viên; mỗi người giữ kín mã/PIN cá nhân.
- Ảnh dùng để đối chiếu thủ công, chưa có nhận diện khuôn mặt. Camera lỗi vẫn có thể ghi công với ghi chú thiếu ảnh.
- Cất thêm bản sao lưu ngoài máy. File sao lưu và báo cáo có thông tin nhân sự/lương, cần quản lý quyền truy cập.
- Khi dùng Google Drive, kiểm tra trạng thái đồng bộ trong ứng dụng Drive. Thời điểm xuất Excel chỉ xác nhận file đã ghi tại máy.

**Cần hỗ trợ? [Nhắn Zalo 0355636456](https://zalo.me/0355636456).** Gửi phiên bản đang dùng và ảnh thông báo lỗi; giữ nguyên dữ liệu trước khi được hướng dẫn xử lý.

---

Tài liệu cập nhật ngày **26/11/2026**. Kho này cung cấp bộ cài, thông báo cập nhật và hướng dẫn công khai của LDB.
