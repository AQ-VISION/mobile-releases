# AQPConnect Android releases

Repository này phân phối APK đã ký và thông tin cập nhật. Mã nguồn ứng dụng,
khóa ký, mật khẩu và thông tin đăng nhập được lưu riêng.

| Ứng dụng | Phiên bản hiện hành | Tải APK |
| --- | --- | --- |
| AQPConnect Dev (`com.example.mobile.dev`) | 1.1.15 — build 2028 | [Tải AQPConnect Dev](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.15-dev.2028/AQPConnect-1.1.15-dev.apk) |
| AQPConnect (`com.example.mobile`) | 1.1.10 — build 2023 | [Tải AQPConnect](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.10/AQPConnect-1.1.10.apk) |

AQPConnect 1.1.10 sửa danh sách camera/nhóm cho tài khoản ADMIN để khớp quyền
xem trên web Media, báo lỗi phiên đăng nhập và xóa dữ liệu camera cũ khi đổi
tài khoản. Quyền riêng của tài khoản khách hàng, máy chủ và chữ ký được giữ
nguyên. Từ AQPConnect 1.1.9, mở Cài đặt → Cập nhật ứng dụng để tải và cài
1.1.10; nếu phiên đăng nhập đã hết hạn, đăng nhập lại bằng tài khoản web Media.

Dev 1.1.15 và bản khách hàng 1.1.9 trước đó hiển thị tên khu vực máy chủ thay tên miền
ở màn hình đăng nhập và Cài đặt. Biểu tượng vị trí trung tính không thể hiện
trạng thái kết nối. Cấu hình Cloud/Local, package và chứng chỉ ký được giữ lại.

Nền Dev 1.1.14 trước đó bổ sung thiết lập Eyerus qua BLE có xác thực, đổi mật khẩu mặc định
trước WiFi/liên kết và điều khiển camera/luồng qua phiên BLE trên firmware tương thích.
Cải thiện thời hạn phản hồi và xử lý hộp thoại pairing/chuyển nền. Firmware cũ cần
được kiểm tra capability; đăng ký cloud mới qua BLE vẫn bị chặn khi chính sách
quyền riêng tư trên gateway còn là bản nháp. Chưa nghiệm thu BLE hoặc firmware
ARM trên thiết bị thật; đây là bản Dev thử nghiệm.
Bản khách hàng 1.1.9 — build 2022 chỉ nhận thay đổi hiển thị khu vực trên nền
1.1.8; các tính năng Dev đang chờ nghiệm thu chưa được chuyển sang khách hàng.
Từ AQPConnect 1.1.8 hoặc 1.1.9, mở Cài đặt → Cập nhật ứng dụng để tải và cài
AQPConnect 1.1.10 (2023). Android yêu cầu quyền cài đặt và xác nhận; không cần gỡ ứng dụng hiện có.

Bản khách hàng trước đó: [1.1.9 — build 2022](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.9/AQPConnect-1.1.9.apk).

Bản Dev trước đó: [1.1.14 — build 2027](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.14-dev.2027/AQPConnect-1.1.14-dev.apk).
Bản 1.1.13: [1.1.13 — build 2026](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.13-dev.2026/AQPConnect-1.1.13-dev.apk).
Bản 1.1.12: [1.1.12 — build 2025](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.12-dev.2025/AQPConnect-1.1.12-dev.apk).
Bản 1.1.11: [1.1.11 — build 2024](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.11-dev.2024/AQPConnect-1.1.11-dev.apk).
Bản 1.1.10: [1.1.10 — build 2023](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.10-dev.2023/AQPConnect-1.1.10-dev.apk).
Bản 1.1.9: [1.1.9 — build 2022](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.9-dev.2022/AQPConnect-1.1.9-dev.apk).

Trên Dev 1.1.8 (build 2020 hoặc 2021), Dev 1.1.9 (2022), Dev 1.1.10 (2023),
Dev 1.1.11 (2024), Dev 1.1.12 (2025), Dev 1.1.13 (2026) hoặc Dev 1.1.14
(2027), mở Cài đặt → Cập nhật ứng dụng → Kiểm tra cập nhật,
rồi tải và cài Dev 1.1.15 (2028). Có thể tải APK trong bảng và cài đè lên
AQPConnect Dev; giữ nguyên ứng dụng để giữ dữ liệu. Android yêu cầu cấp
quyền cài đặt và xác nhận. Nếu camera yêu cầu đăng nhập lại sau nâng cấp,
dùng tài khoản đang đăng nhập trên web Dev.

Các APK khởi tạo 1.1.8 build 2020 vẫn được giữ để kiểm tra đường cập nhật:
[Dev](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8-dev.apk)
và [AQPConnect](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8.apk).
Dev 1.1.6 chưa có bộ cập nhật hoạt động; cài đè APK Dev hiện hành một lần.

Khách hàng còn dùng AQPConnect đến 1.1.6 phải chuyển khóa ký một lần bằng cách
gỡ app cũ rồi cài mới; thao tác đó xóa dữ liệu/cài đặt trong app, không xóa dữ
liệu trên server. Hai ứng dụng Dev và AQPConnect có thể cùng tồn tại.

Các manifest trong channels/ độc lập theo package và môi trường. APK được
kiểm tra kích thước, SHA-256, package, build code và chữ ký trước khi cài.
Không đưa thông tin đăng nhập vào các manifest này.
