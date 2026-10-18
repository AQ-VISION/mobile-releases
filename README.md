# AQPConnect Android releases

Repository này phân phối APK đã ký và thông tin cập nhật. Mã nguồn ứng dụng,
khóa ký, mật khẩu và thông tin đăng nhập được lưu riêng.

| Ứng dụng | Phiên bản hiện hành | Tải APK |
| --- | --- | --- |
| AQPConnect Dev (`com.example.mobile.dev`) | 1.1.12 — build 2025 | [Tải AQPConnect Dev](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.12-dev.2025/AQPConnect-1.1.12-dev.apk) |
| AQPConnect (`com.example.mobile`) | 1.1.8 — build 2021 | [Tải AQPConnect](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8/AQPConnect-1.1.8.apk) |

Dev 1.1.12 cho phép các ô xem trước tắt tiếng phát đồng thời mà không
tranh quyền phát âm thanh; bổ sung khôi phục khi video bị tạm dừng ngoài ý muốn.
Bản Dev có thông tin chẩn đoán và nút sao chép để kiểm tra trường hợp lưới
camera bị đen trên thiết bị. Giữ các sửa lỗi phát lại, gateway, phiên đăng
nhập và cập nhật của những bản Dev trước.
Bản khách hàng tiếp tục giữ 1.1.8 — build 2021.

Bản Dev trước đó: [1.1.11 — build 2024](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.11-dev.2024/AQPConnect-1.1.11-dev.apk).
Bản 1.1.10: [1.1.10 — build 2023](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.10-dev.2023/AQPConnect-1.1.10-dev.apk).
Bản 1.1.9: [1.1.9 — build 2022](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.9-dev.2022/AQPConnect-1.1.9-dev.apk).

Trên Dev 1.1.8 (build 2020 hoặc 2021), Dev 1.1.9 (2022), Dev 1.1.10 (2023)
hoặc Dev 1.1.11 (2024), mở Cài đặt → Cập nhật ứng dụng → Kiểm tra cập nhật,
rồi tải và cài Dev 1.1.12 (2025). Có thể tải APK trong bảng và cài đè lên
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
