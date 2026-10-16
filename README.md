# AQPConnect Android releases

Repository này chỉ chứa APK đã ký và thông tin cập nhật. Mã nguồn ứng dụng,
khóa ký, mật khẩu và thông tin đăng nhập được lưu riêng.

| Ứng dụng | APK khởi tạo build 2020 | APK hiện hành build 2021 |
| --- | --- | --- |
| AQPConnect Dev (`com.example.mobile.dev`) | [Tải bản khởi tạo](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8-dev.apk) | [Tải bản hiện hành](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8/AQPConnect-1.1.8-dev.apk) |
| AQPConnect (`com.example.mobile`) | [Tải bản khởi tạo](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8.apk) | [Tải bản hiện hành](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8/AQPConnect-1.1.8.apk) |

Hai ứng dụng cùng phiên bản 1.1.8. Build 2020 là bản đầu tiên có bộ cập nhật;
build 2021 có cùng tính năng và dùng để thử nâng cấp từ trong ứng dụng.

Để thử nâng cấp trong ứng dụng, cài APK build 2020 trước: cài đè đúng môi trường
lên bản Dev 1.1.6 hoặc AQPConnect 1.1.7 đang dùng, giữ nguyên dữ liệu. Mở
Cài đặt → Cập nhật ứng dụng → Kiểm tra cập nhật. Khi kết quả hiện ra, xác nhận
bản đang dùng là 1.1.8 (2020) và bản được đề nghị là 1.1.8 (2021), rồi mới
bấm Tải bản cập nhật để tải và cài build 2021. Cài trực tiếp build 2021 sẽ
bỏ qua bước thử nâng cấp 2020 → 2021. Android vẫn yêu cầu cấp quyền và xác nhận.

Khách hàng còn dùng AQPConnect đến 1.1.6 phải chuyển khóa ký một lần bằng cách
gỡ app cũ rồi cài mới; thao tác đó xóa dữ liệu/cài đặt trong app, không xóa dữ
liệu trên server. Hai ứng dụng Dev và Customer có thể cùng tồn tại.

Các manifest trong channels/ độc lập theo package và môi trường. APK được
kiểm tra kích thước, SHA-256, package, build code và chữ ký trước khi cài.
Không đưa thông tin đăng nhập vào các manifest này.
