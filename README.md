# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introduction

Stop wasting time on managing your development environment!

ServBay is a powerful and comprehensive local web development environment management tool designed for professional web developers, now available for both **macOS and Windows**. ServBay includes support for a variety of development languages, databases, web servers, mail servers, DNS servers, and reverse proxies. It now also features integrated AI development capabilities with Ollama, object storage with MinIO, powerful search with Typesense and Meilisearch, and a robust backup system. Everything you need for web development is here. Get a professional local development environment set up in just 3 minutes.

![ServBay Dashboard](/images/dashboard.png)

## Features

### Multi-site Management

Managing multiple websites simultaneously? ServBay makes it easy. Effortlessly configure and run numerous websites on your local machine, each with its own unique settings, domain, and development environment. ServBay's intuitive interface simplifies the process, allowing you to quickly switch between projects and manage their configurations without complex setup or conflicts.

![Multi-site Management](/images/website.png)

### Web Servers

ServBay includes the most popular web servers—**Caddy, NGINX, and Apache**—with support for HTTP/3 and CORS. It also supports custom domains and automated SSL configuration, eliminating the need to purchase domains and SSL certificates, saving significant costs during development.

![Web Servers](/images/web-servers.png)

### Web Development Languages

ServBay comes with a vast array of development languages, including **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, and even **.NET** (2.0-10.0) & **Mono**. Developers can seamlessly switch between different versions and use different versions for different projects. This immense flexibility gives developers strong confidence.

![Web Development Languages](/images/languages.png)

### Databases

Databases are essential for web development. ServBay includes **MySQL**, **MariaDB**, and the increasingly popular **PostgreSQL**. NoSQL databases are also covered, with **Redis**, **Memcached**, and **MongoDB** ready to use out-of-the-box, requiring no configuration. ServBay also integrates **phpMyAdmin** and **Adminer** for easy database management.

![Databases](/images/databases.png)

### AI Development with Ollama

Embrace the future of development with integrated AI capabilities. ServBay incorporates Ollama, allowing you to run powerful Large Language Models (LLMs) like Llama 3, Mistral, and Gemma locally. Build and test AI-driven applications with zero latency and complete data privacy, all managed through ServBay's intuitive interface.

![AI Development with Ollama](/images/ai.png)

### Powerful Search with Typesense & Meilisearch

Power your applications with modern, fast search engines. ServBay includes both **Typesense** and **Meilisearch**, two of the leading open-source search solutions that you can add to your projects with one click.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Object Storage with MinIO

Manage unstructured data with ease using MinIO, a high-performance, S3-compatible object storage service now included with ServBay. It's perfect for storing everything from backups and logs to media files and artifacts, providing a robust storage solution for your local development needs.

![Object Storage with MinIO](/images/minio.png)

### Domain and DNS Services

Domains are a consumable resource in the web development lifecycle. ServBay includes a DNS server, allowing developers to use non-existent domains and TLDs without registration, and even issue SSL certificates for them. This not only saves developers significant costs but also enhances security—hackers cannot access a non-existent domain. Additionally, ServBay provides a graphical interface for conveniently managing your hosts file.

![Domain and DNS Services](/images/dns.png)

### PKI and SSL Certificate Management

ServBay provides a PKI system. Developers can create their own Certificate Authority (CA) and issue SSL certificates—particularly useful for small development teams. Using a private CA, small teams can encrypt data transmission and establish internal trust within their development environment. This applies not just to web services, but also to databases, SMTP, and other services. ServBay even supports S/MIME certificates for email encryption, code signing certificates, and PDF document signing certificates.

Of course, ServBay also supports obtaining and automatically renewing SSL certificates from Let's Encrypt, ZeroSSL, and Google Trust Services via ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Mail Server

Want to use SMTP/POP3 in your local development? No problem! ServBay includes a built-in mail server with **Mailpit** for local email testing. Integrated with the PKI system, the mail server supports STARTTLS and SSL/TLS without configuration. Need to relay mail to an external SMTP server? ServBay's mail server supports relaying. We also support SpamAssassin, allowing you to score each outgoing email and reduce the chances of it being marked as spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Reverse Proxy

Need to temporarily share your project with users? Want to host a server at home but don't have a public IP address? ServBay has you covered. It supports **ngrok, frp, Cloudflared, and Pinggy** for quickly sharing your website publicly.

![Reverse Proxy](/images/tunnel.png)

### Project-Level Runtime Environments

ServBay offers project-level runtime environment configuration. You can configure and lock the required PHP and Node.js versions for different projects, making your project development more flexible and controllable.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Powerful Backup & Restore

Data security and environment recovery are crucial. ServBay features a comprehensive backup and restore system to give you peace of mind.
*   **One-Click & Scheduled Backups**: Configure automatic, scheduled backups or trigger manual backups of your databases, website files, service configurations, and SSL certificates.
*   **Easy Restore & Migration**: Quickly restore your environment to a previous state in case of a problem, or use the backups to easily migrate your entire ServBay setup to a new machine.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Bundled Packages

ServBay comes with a variety of essential packages to streamline your development process:

-   **Web Servers**: Caddy, Nginx, Apache
-   **Programming Languages**: PHP (5.6 to 8.5-Alpha), Node.js (12 to 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **SQL Databases**: MySQL (5.1 to 9.3), MariaDB (10.4 to 12.0), PostgreSQL (10 to 17)
-   **NoSQL Databases**: Redis, Memcached, MongoDB (5.0 to 8.0) & MongoSH 2
-   **AI / LLM**: Ollama
-   **Search Engines**: Typesense, Meilisearch
-   **Object Storage**: MinIO
-   **DNS**: Built-in DNS server (dnsmasq)
-   **Email**: Mailpit for local email testing
-   **Tunnel/Reverse Proxy**: Cloudflared, frp, Ngrok, Pinggy
-   **Other Tools**: phpMyAdmin, Adminer, Composer, and more

![ServBay Bundled Packages](/images/services.png)

## Installation

ServBay is available for both macOS and Windows.

### macOS

1.  Download the latest version of ServBay for macOS from the [official website](https://www.servbay.com/download).
2.  Open the installer and follow the prompts to complete the installation.
3.  Launch ServBay and follow the initial setup wizard to configure it.

### Windows

1.  Download the latest version of ServBay for Windows from the [official download page](https://www.servbay.com/download) or directly from the [Windows release repository](https://github.com/ServBay/ServBay-Windows-Release).
2.  Run the installer and follow the on-screen instructions.
3.  Launch ServBay to begin configuring your local development environment.

## Documentation

For detailed documentation and usage guides, visit the [ServBay Documentation Center](https://support.servbay.com).

## Support

If you encounter any issues while using ServBay, you can get support through the following channels:

-   [Help Center](https://support.servbay.com)
-   [Discord Community](https://talk.servbay.com)
-   [Telegram Community](https://telegram.servbay.dev)
-   [WhatsApp Community](https://wa.servbay.dev)
-   [WeChat Community](https://wechat-group.servbay.dev)
-   [Submit an Issue](https://github.com/ServBay/ServBay/issues)

## Community

Join our community to exchange experiences with other developers and get the latest updates:

-   [ServBay Blog](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Thank you for using ServBay! If you have any questions or suggestions, please feel free to reach out to us.