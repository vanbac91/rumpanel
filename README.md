# RumPanel


> The goal of this project is to make the easiest, fastest, and most painless way of Linux VPS management. This project has been forked from VPSMate since 11 Jan 2017 but changed a lot.

Official Website: [rumpanel.org](https://rumpane.org "rumpanel")

Developer: [vanbac91](https://github.com/vanbac91 "vanbac91")

#### Installation

```shell
# stable version
curl -O https://raw.githubusercontent.com/vanbac91/rumpanel/master/install.py
python install.py

# beta version
curl -O https://raw.githubusercontent.com/vanbac91/rumpanel/dev/install.py
python install.py --dev
```

#### Uninstall

```shell
service rumpanel stop
rm -rf /usr/local/rumpane
rm -f /etc/init.d/rumpane
```

#### Username and Password

```shell
/usr/local/rumpane/config.py username 'your-username'
/usr/local/rumpane/config.py password 'your-password'
```

#### Features

-Miễn phí, đơn giản và mã nguồn mở
-Nhấp cài đặt trực tuyến, nhỏ và tiết kiệm tài nguyên
-Cung cấp hỗ trợ CentOS / Redhat 5.4+, 6.x, 7.x, 8.x
-Cơ chế quản lý phần mềm dựa trên nguồn phần mềm phân phối
-Hãy xây dựng môi trường Linux + Nginx + MySQL + PHP
-Quản lý tập tin và tái chế tập tin trực tuyến mạnh mẽ
-Nhanh chóng tạo và cài đặt nhiều trang web
-Rich và các công cụ hệ thống thực tế

#### from VPSMate to rumpanel

Bảng quản lý này chỉ quản lý và định cấu hình các dịch vụ và chức năng của hệ thống ở cấp UI và không tạo ra các tệp phụ thuộc và cấu hình dự phòng trong hệ thống. Không quan trọng VPSMate hay rumpane, nó chỉ là một công cụ, gỡ cài đặt hoặc cài đặt và định cấu hình dịch vụ cho hệ thống. Không có tác dụng

~ ~ Ở giai đoạn này, cả hai đều sử dụng cùng một tệp dịch vụ xử lý, vì vậy ** chỉ cần gỡ cài đặt VPSMate và cài đặt rumpane ** ~ ~

Bắt đầu từ phiên bản v1.1.1b16, tên quy trình vpsmate không còn được sử dụng và tên quy trình được đổi thành mạng nội bộ. Trong quá trình cài đặt bảng điều khiển mới, VPSMate đã cài đặt có thể được giữ lại (hoặc xóa).

Bắt đầu từ phiên bản v1.1.1b18, tên quy trình mạng nội bộ không còn được sử dụng, tên quy trình là rumpane và nhận dạng hợp nhất là "rumpane"

> Tôi hy vọng bạn có một thời gian tốt!
