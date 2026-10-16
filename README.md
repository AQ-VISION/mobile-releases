# AQPConnect Android releases

Repository này chỉ chứa APK đã ký và metadata cập nhật. Mã nguồn ứng dụng,
khóa ký, mật khẩu và token truy cập được giữ riêng.

| Ứng dụng | APK có bộ cập nhật — build 2020 |
| --- | --- |
| AQPConnect Dev | [Tải APK](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8-dev.apk) |
| AQPConnect | [Tải APK](https://github.com/AQ-VISION/mobile-releases/releases/download/v1.1.8-bootstrap.2020/AQPConnect-1.1.8.apk) |

Hai ứng dụng cùng phiên bản 1.1.8. Cài đè build 2020 đúng môi trường lên Dev
1.1.6 hoặc AQPConnect 1.1.7 đang dùng để giữ dữ liệu và có bộ cập nhật.
Build 2021 với cùng tính năng sẽ được phát hành để thử bước nâng cấp trong app.
Mở Cài đặt → Cập nhật ứng dụng để kiểm tra; Android yêu cầu quyền và xác nhận cài.

Khách hàng còn dùng bản đến 1.1.6 có khóa cũ khác: cần gỡ app cũ một lần để
chuyển khóa. Thao tác đó xóa dữ liệu/cài đặt trong app, không xóa dữ liệu server.

Hai manifest độc lập trong channels/ chọn đúng package và môi trường. Trước
khi cài, app kiểm tra build code, HTTPS, kích thước, SHA-256 và danh tính ký.
