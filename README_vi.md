# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Giới thiệu

Đừng lãng phí thời gian vào việc quản lý môi trường phát triển của bạn nữa!

ServBay là một công cụ quản lý môi trường phát triển web cục bộ mạnh mẽ và toàn diện, được thiết kế cho các nhà phát triển web chuyên nghiệp, hiện đã có sẵn cho cả **macOS và Windows**. ServBay bao gồm hỗ trợ cho nhiều ngôn ngữ phát triển, cơ sở dữ liệu, máy chủ web, máy chủ mail, máy chủ DNS và proxy ngược. Hiện tại, nó còn tích hợp các khả năng phát triển AI với Ollama, lưu trữ đối tượng với MinIO, tìm kiếm mạnh mẽ với Typesense và Meilisearch, và một hệ thống sao lưu mạnh mẽ. Mọi thứ bạn cần cho việc phát triển web đều có ở đây. Thiết lập một môi trường phát triển cục bộ chuyên nghiệp chỉ trong 3 phút.

![ServBay Dashboard](/images/dashboard.png)

## Tính năng

### Quản lý đa trang web

Quản lý nhiều trang web cùng một lúc? ServBay giúp việc này trở nên dễ dàng. Dễ dàng cấu hình và chạy nhiều trang web trên máy cục bộ của bạn, mỗi trang có cài đặt, tên miền và môi trường phát triển riêng. Giao diện trực quan của ServBay đơn giản hóa quy trình, cho phép bạn nhanh chóng chuyển đổi giữa các dự án và quản lý cấu hình của chúng mà không cần thiết lập phức tạp hay xung đột.

![Multi-site Management](/images/website.png)

### Máy chủ Web

ServBay bao gồm các máy chủ web phổ biến nhất—**Caddy, NGINX, và Apache**—với hỗ trợ HTTP/3 và CORS. Nó cũng hỗ trợ tên miền tùy chỉnh và cấu hình SSL tự động, loại bỏ nhu cầu mua tên miền và chứng chỉ SSL, tiết kiệm chi phí đáng kể trong quá trình phát triển.

![Web Servers](/images/web-servers.png)

### Ngôn ngữ phát triển Web

ServBay đi kèm với một loạt các ngôn ngữ phát triển, bao gồm **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, và thậm chí cả **.NET** (2.0-10.0) & **Mono**. Các nhà phát triển có thể chuyển đổi liền mạch giữa các phiên bản khác nhau và sử dụng các phiên bản khác nhau cho các dự án khác nhau. Sự linh hoạt to lớn này mang lại cho các nhà phát triển sự tự tin mạnh mẽ.

![Web Development Languages](/images/languages.png)

### Cơ sở dữ liệu

Cơ sở dữ liệu là yếu tố cần thiết cho việc phát triển web. ServBay bao gồm **MySQL**, **MariaDB**, và **PostgreSQL** ngày càng phổ biến. Các cơ sở dữ liệu NoSQL cũng được hỗ trợ, với **Redis**, **Memcached**, và **MongoDB** sẵn sàng sử dụng ngay lập tức mà không cần cấu hình. ServBay cũng tích hợp **phpMyAdmin** và **Adminer** để quản lý cơ sở dữ liệu dễ dàng.

![Databases](/images/databases.png)

### Phát triển AI với Ollama

Nắm bắt tương lai của phát triển với các khả năng AI tích hợp. ServBay tích hợp Ollama, cho phép bạn chạy các Mô hình Ngôn ngữ Lớn (LLM) mạnh mẽ như Llama 3, Mistral và Gemma ngay trên máy cục bộ. Xây dựng và thử nghiệm các ứng dụng dựa trên AI với độ trễ bằng không và bảo mật dữ liệu hoàn toàn, tất cả đều được quản lý thông qua giao diện trực quan của ServBay.

![AI Development with Ollama](/images/ai.png)

### Tìm kiếm mạnh mẽ với Typesense & Meilisearch

Tăng cường sức mạnh cho ứng dụng của bạn với các công cụ tìm kiếm hiện đại, nhanh chóng. ServBay bao gồm cả **Typesense** và **Meilisearch**, hai trong số các giải pháp tìm kiếm mã nguồn mở hàng đầu mà bạn có thể thêm vào dự án của mình chỉ bằng một cú nhấp chuột.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Lưu trữ đối tượng với MinIO

Quản lý dữ liệu phi cấu trúc một cách dễ dàng bằng MinIO, một dịch vụ lưu trữ đối tượng hiệu suất cao, tương thích S3 hiện đã được tích hợp trong ServBay. Nó hoàn hảo để lưu trữ mọi thứ từ bản sao lưu và nhật ký đến các tệp phương tiện và tạo phẩm, cung cấp một giải pháp lưu trữ mạnh mẽ cho nhu cầu phát triển cục bộ của bạn.

![Object Storage with MinIO](/images/minio.png)

### Dịch vụ tên miền và DNS

Tên miền là một tài nguyên tiêu hao trong vòng đời phát triển web. ServBay bao gồm một máy chủ DNS, cho phép các nhà phát triển sử dụng các tên miền và TLD không tồn tại mà không cần đăng ký, và thậm chí cấp chứng chỉ SSL cho chúng. Điều này không chỉ giúp các nhà phát triển tiết kiệm chi phí đáng kể mà còn tăng cường bảo mật—tin tặc không thể truy cập vào một tên miền không tồn tại. Ngoài ra, ServBay cung cấp một giao diện đồ họa để quản lý tệp hosts của bạn một cách thuận tiện.

![Domain and DNS Services](/images/dns.png)

### Quản lý PKI và Chứng chỉ SSL

ServBay cung cấp một hệ thống PKI. Các nhà phát triển có thể tạo Cơ quan Chứng thực (CA) của riêng mình và cấp chứng chỉ SSL—điều này đặc biệt hữu ích cho các nhóm phát triển nhỏ. Sử dụng CA riêng, các nhóm nhỏ có thể mã hóa việc truyền dữ liệu và thiết lập sự tin cậy nội bộ trong môi trường phát triển của họ. Điều này không chỉ áp dụng cho các dịch vụ web, mà còn cho cơ sở dữ liệu, SMTP và các dịch vụ khác. ServBay thậm chí còn hỗ trợ chứng chỉ S/MIME để mã hóa email, chứng chỉ ký mã và chứng chỉ ký tài liệu PDF.

Tất nhiên, ServBay cũng hỗ trợ lấy và tự động gia hạn chứng chỉ SSL từ Let's Encrypt, ZeroSSL và Google Trust Services thông qua ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Máy chủ Mail

Bạn muốn sử dụng SMTP/POP3 trong quá trình phát triển cục bộ? Không vấn đề gì! ServBay bao gồm một máy chủ mail tích hợp với **Mailpit** để kiểm tra email cục bộ. Tích hợp với hệ thống PKI, máy chủ mail hỗ trợ STARTTLS và SSL/TLS mà không cần cấu hình. Cần chuyển tiếp mail đến một máy chủ SMTP bên ngoài? Máy chủ mail của ServBay hỗ trợ chuyển tiếp. Chúng tôi cũng hỗ trợ SpamAssassin, cho phép bạn chấm điểm mỗi email gửi đi và giảm khả năng nó bị đánh dấu là thư rác.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Proxy ngược

Cần chia sẻ tạm thời dự án của bạn với người dùng? Muốn lưu trữ một máy chủ tại nhà nhưng không có địa chỉ IP công cộng? ServBay đã có giải pháp cho bạn. Nó hỗ trợ **ngrok, frp, Cloudflared, và Pinggy** để nhanh chóng chia sẻ trang web của bạn công khai.

![Reverse Proxy](/images/tunnel.png)

### Môi trường chạy cấp dự án

ServBay cung cấp cấu hình môi trường chạy cấp dự án. Bạn có thể cấu hình và khóa các phiên bản PHP và Node.js cần thiết cho các dự án khác nhau, giúp việc phát triển dự án của bạn linh hoạt và dễ kiểm soát hơn.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Sao lưu & Khôi phục mạnh mẽ

An toàn dữ liệu và phục hồi môi trường là rất quan trọng. ServBay có một hệ thống sao lưu và khôi phục toàn diện để bạn yên tâm.
*   **Sao lưu một cú nhấp chuột & theo lịch trình**: Cấu hình sao lưu tự động, theo lịch trình, hoặc kích hoạt sao lưu thủ công cho cơ sở dữ liệu, tệp trang web, cấu hình dịch vụ và chứng chỉ SSL của bạn.
*   **Khôi phục & Di chuyển dễ dàng**: Nhanh chóng khôi phục môi trường của bạn về trạng thái trước đó trong trường hợp có sự cố, hoặc sử dụng các bản sao lưu để dễ dàng di chuyển toàn bộ thiết lập ServBay của bạn sang một máy mới.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Gói đi kèm

ServBay đi kèm với nhiều gói cần thiết để hợp lý hóa quy trình phát triển của bạn:

-   **Máy chủ Web**: Caddy, Nginx, Apache
-   **Ngôn ngữ lập trình**: PHP (5.6 đến 8.5-Alpha), Node.js (12 đến 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **Cơ sở dữ liệu SQL**: MySQL (5.1 đến 9.3), MariaDB (10.4 đến 12.0), PostgreSQL (10 đến 17)
-   **Cơ sở dữ liệu NoSQL**: Redis, Memcached, MongoDB (5.0 đến 8.0) & MongoSH 2
-   **AI / LLM**: Ollama
-   **Công cụ tìm kiếm**: Typesense, Meilisearch
-   **Lưu trữ đối tượng**: MinIO
-   **DNS**: Máy chủ DNS tích hợp (dnsmasq)
-   **Email**: Mailpit để kiểm tra email cục bộ
-   **Tunnel/Proxy ngược**: Cloudflared, frp, Ngrok, Pinggy
-   **Các công cụ khác**: phpMyAdmin, Adminer, Composer, và nhiều hơn nữa

![ServBay Bundled Packages](/images/services.png)

## Cài đặt

ServBay có sẵn cho cả macOS và Windows.

### macOS

1.  Tải xuống phiên bản mới nhất của ServBay cho macOS từ [trang web chính thức](https://www.servbay.com/download).
2.  Mở trình cài đặt và làm theo hướng dẫn để hoàn tất quá trình cài đặt.
3.  Khởi chạy ServBay và làm theo trình hướng dẫn thiết lập ban đầu để cấu hình nó.

### Windows

1.  Tải xuống phiên bản mới nhất của ServBay cho Windows từ [trang tải xuống chính thức](https://www.servbay.com/download) hoặc trực tiếp từ [kho lưu trữ phiên bản Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  Chạy trình cài đặt và làm theo hướng dẫn trên màn hình.
3.  Khởi chạy ServBay để bắt đầu cấu hình môi trường phát triển cục bộ của bạn.

## Tài liệu

Để có tài liệu chi tiết và hướng dẫn sử dụng, hãy truy cập [Trung tâm Tài liệu ServBay](https://support.servbay.com).

## Hỗ trợ

Nếu bạn gặp bất kỳ vấn đề nào khi sử dụng ServBay, bạn có thể nhận hỗ trợ qua các kênh sau:

-   [Trung tâm Trợ giúp](https://support.servbay.com)
-   [Cộng đồng Discord](https://talk.servbay.com)
-   [Cộng đồng Telegram](https://telegram.servbay.dev)
-   [Cộng đồng WhatsApp](https://wa.servbay.dev)
-   [Cộng đồng WeChat](https://wechat-group.servbay.dev)
-   [Gửi vấn đề](https://github.com/ServBay/ServBay/issues)

## Cộng đồng

Tham gia cộng đồng của chúng tôi để trao đổi kinh nghiệm với các nhà phát triển khác và nhận các bản cập nhật mới nhất:

-   [Blog của ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Cảm ơn bạn đã sử dụng ServBay! Nếu bạn có bất kỳ câu hỏi hoặc đề xuất nào, xin vui lòng liên hệ với chúng tôi.