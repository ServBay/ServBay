# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Logo ServBay](/images/logo.png)

## Giới thiệu

Ngừng lãng phí thời gian quản lý môi trường phát triển của bạn!

ServBay là một [công cụ quản lý môi trường phát triển web cục bộ](https://www.servbay.com) mạnh mẽ và toàn diện được thiết kế cho các nhà phát triển web chuyên nghiệp. ServBay bao gồm hỗ trợ cho nhiều ngôn ngữ phát triển, cơ sở dữ liệu, máy chủ web, máy chủ thư, máy chủ DNS, bộ nhớ đối tượng, proxy ngược và thậm chí cả một nền tảng quản lý chứng chỉ SSL chuyên nghiệp. Tất cả mọi thứ bạn cần cho phát triển web đều có ở đây. Thiết lập môi trường phát triển cục bộ chuyên nghiệp chỉ trong 3 phút.

![Bảng điều khiển ServBay](/images/dashboard.png)

## Tính năng

### Quản lý nhiều trang web

[Quản lý nhiều trang web](https://support.servbay.com/basic-usage/websites/adding-first-website) cùng lúc? ServBay giúp việc này trở nên dễ dàng.  Dễ dàng cấu hình và chạy nhiều trang web trên máy cục bộ của bạn, mỗi trang web có cài đặt, miền và môi trường phát triển riêng. Giao diện trực quan của ServBay đơn giản hóa quy trình, cho phép bạn nhanh chóng chuyển đổi giữa các dự án và quản lý cấu hình của chúng mà không cần thiết lập phức tạp hoặc xung đột.

![Quản lý nhiều trang web](/images/hosts.png)

### Máy chủ web

ServBay bao gồm các [máy chủ web](https://www.servbay.com/features/web-server) phổ biến nhất, Caddy và NGINX, với hỗ trợ HTTP/3 và CORS.  Nó cũng hỗ trợ các miền tùy chỉnh và [cấu hình SSL tự động](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), loại bỏ nhu cầu mua miền và chứng chỉ SSL, tiết kiệm chi phí đáng kể trong quá trình phát triển.

![Máy chủ web](/images/web-servers.png)

### Ngôn ngữ phát triển web

ServBay đi kèm với [Node.js](https://www.servbay.com/features/nodejs) (phiên bản 12-23) và [PHP](https://www.servbay.com/features/php) (phiên bản 5.6-8.5), đáp ứng nhu cầu của các nhà phát triển trong suốt vòng đời phát triển web. Các nhà phát triển có thể chuyển đổi liền mạch giữa các phiên bản khác nhau và sử dụng các phiên bản khác nhau cho các dự án khác nhau. Sự linh hoạt to lớn này mang lại cho các nhà phát triển sự tự tin mạnh mẽ.  ServBay cũng bao gồm Python và Golang.

![Ngôn ngữ phát triển web](/images/languages.png)

### Cơ sở dữ liệu

[Cơ sở dữ liệu](https://www.servbay.com/features/database) là điều cần thiết cho phát triển web. ServBay bao gồm [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) và [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage) ngày càng phổ biến.  Cơ sở dữ liệu NoSQL cũng được hỗ trợ, với [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) và [MongoDB](https://www.servbay.com/features/database) sẵn sàng để sử dụng ngay lập tức, không yêu cầu cấu hình.  ServBay cũng tích hợp [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) và [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) để quản lý cơ sở dữ liệu dễ dàng.

![Cơ sở dữ liệu](/images/databases.png)

### Dịch vụ miền và DNS

[Tên miền](https://www.servbay.com/features/dns-server) là một tài nguyên tiêu hao trong vòng đời phát triển web. ServBay bao gồm một [máy chủ DNS](https://www.servbay.com/features/dns-server), cho phép các nhà phát triển sử dụng các miền và TLD không tồn tại mà không cần đăng ký và thậm chí cấp chứng chỉ SSL cho chúng. Điều này không chỉ tiết kiệm chi phí đáng kể cho các nhà phát triển mà còn tăng cường bảo mật - tin tặc không thể truy cập vào một miền không tồn tại. Ngoài ra, ServBay cung cấp giao diện đồ họa để quản lý tệp /etc/hosts của bạn một cách thuận tiện.

![Dịch vụ miền và DNS](/images/dns.png)

### Quản lý chứng chỉ PKI và SSL

ServBay cung cấp một [hệ thống PKI](https://www.servbay.com/features/ssl). Các nhà phát triển có thể tạo Cơ quan cấp chứng chỉ (CA) của riêng họ và cấp chứng chỉ SSL - đặc biệt hữu ích cho các nhóm phát triển nhỏ.  Việc sử dụng [CA riêng](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management) cho phép các nhóm nhỏ mã hóa việc truyền dữ liệu và thiết lập niềm tin nội bộ trong môi trường phát triển của họ. Điều này không chỉ áp dụng cho các dịch vụ web mà còn cho cơ sở dữ liệu, SMTP và các dịch vụ khác. ServBay thậm chí còn hỗ trợ [chứng chỉ S/MIME](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) để mã hóa email, [chứng chỉ ký mã](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) và [chứng chỉ ký tài liệu PDF](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Tất nhiên, ServBay cũng hỗ trợ việc lấy và tự động gia hạn chứng chỉ SSL từ Let's Encrypt, ZeroSSL và Google Trust Services thông qua [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Quản lý chứng chỉ PKI và SSL](/images/ssl-pki.png)

### Máy chủ thư

Bạn muốn sử dụng SMTP/POP3 trong quá trình phát triển cục bộ của mình? Không vấn đề gì! ServBay bao gồm một [máy chủ thư tích hợp](https://www.servbay.com/features/email-server).  Được tích hợp với hệ thống PKI, máy chủ thư hỗ trợ [STARTTLS và SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) mà không cần cấu hình.  Cần chuyển tiếp thư đến [máy chủ SMTP](https://www.servbay.com/features/email-server) bên ngoài?  Máy chủ thư của ServBay hỗ trợ chuyển tiếp.  Chúng tôi cũng hỗ trợ SpamAssassin, cho phép bạn chấm điểm từng email gửi đi và giảm khả năng email bị đánh dấu là spam.


![Máy chủ thư](/images/email-server.png)

![Webmail máy chủ thư](/images/email-server-webmail.png)

### Proxy ngược

Bạn cần chia sẻ dự án của mình tạm thời với người dùng? Bạn muốn lưu trữ máy chủ tại nhà nhưng không có địa chỉ IP công cộng? ServBay sẽ hỗ trợ bạn.  Nó hỗ trợ [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp và Cloudflared để nhanh chóng chia sẻ trang web của bạn công khai.  Bạn không tin tưởng các dịch vụ của bên thứ ba? ServBay cũng cung cấp dịch vụ proxy ngược công cộng, được tích hợp liền mạch để chia sẻ chỉ bằng một cú nhấp chuột.


*(Sắp ra mắt)*

### Môi trường chạy ở cấp độ dự án

ServBay cung cấp cấu hình môi trường chạy ở cấp độ dự án. Bạn có thể cấu hình và khóa các phiên bản PHP và Node.js bắt buộc cho các dự án khác nhau, giúp việc phát triển dự án của bạn linh hoạt và có thể kiểm soát hơn.

![Môi trường chạy ở cấp độ dự án](/images/project-level-runtime.png)

### Sạch sẽ và dễ sao lưu

ServBay là một bản cài đặt di động, không để lại dư lượng trên hệ thống của bạn, không giống như các công cụ như Homebrew có thể làm lộn xộn các tệp hệ thống của bạn.  Bạn có thể dễ dàng sao lưu dữ liệu của mình bằng Time Machine hoặc rsync, đảm bảo an toàn dữ liệu.

![Sạch sẽ và dễ sao lưu](/images/easy-to-backup.png)

## Các gói đi kèm

ServBay đi kèm với nhiều gói cần thiết để sắp xếp hợp lý quy trình phát triển của bạn:

- **Máy chủ web**: Caddy (2.8), Nginx (1.27) và Apache *(2.4, sắp ra mắt)*
- **Ngôn ngữ lập trình**: PHP (Từ PHP 5.6 đến PHP 8.5-Dev), Node.js (Từ Node.js 12 đến Node.js 23), Python *(sắp ra mắt)*, Golang *(sắp ra mắt)*
- **Cơ sở dữ liệu SQL**: MySQL (Từ MySQL 5.1 đến MySQL 9.1), MariaDB (Từ MariaDB 10.4 đến MariaDB 11.8), PostgreSQL (Từ PostgreSQL 10 đến PostgreSQL 17)
- **Cơ sở dữ liệu NoSQL**: Redis (7.2), Memcached (1.6), MongoDB (Từ MongoDB 5.0 đến MongoDB 8.0) & MongoSH 2
- **DNS**: Máy chủ DNS tích hợp để phát triển cục bộ (dnsmasq 2.9)
- **Email**: Mailpit để kiểm tra email cục bộ
- **Đường hầm/Proxy ngược**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Các công cụ khác**: phpMyAdmin, Adminer, v.v.

![Các gói đi kèm ServBay](/images/services.png)

## Cài đặt

Làm theo các bước sau để cài đặt ServBay:

1. Tải xuống phiên bản ServBay mới nhất từ [trang web chính thức](https://www.servbay.com).
2. Mở trình cài đặt và làm theo lời nhắc để hoàn tất cài đặt.
3. Khởi chạy ServBay và làm theo trình hướng dẫn thiết lập ban đầu để cấu hình nó.


## Tài liệu

Để biết tài liệu chi tiết và hướng dẫn sử dụng, hãy truy cập [Trung tâm tài liệu ServBay](https://support.servbay.com).

## Hỗ trợ

Nếu bạn gặp bất kỳ sự cố nào khi sử dụng ServBay, bạn có thể nhận hỗ trợ thông qua các kênh sau:

- [Trung tâm trợ giúp](https://support.servbay.com)
- [Cộng đồng Discord](https://talk.servbay.com)
- [Cộng đồng Telegram](https://telegram.servbay.dev)
- [Cộng đồng WhatsApp](https://wa.servbay.dev)
- [Cộng đồng WeChat](https://wechat-group.servbay.dev)
- [Gửi sự cố](https://github.com/ServBay/ServBay/issues)


## Cộng đồng

Tham gia cộng đồng của chúng tôi để trao đổi kinh nghiệm với các nhà phát triển khác và nhận các bản cập nhật mới nhất:

- [Blog ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Cảm ơn bạn đã sử dụng ServBay! Nếu bạn có bất kỳ câu hỏi hoặc đề xuất nào, vui lòng liên hệ với chúng tôi.
