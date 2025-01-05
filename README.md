# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introduction

Stop wasting time on managing your development environment!

ServBay is a powerful and comprehensive [local web development environment management tool](https://www.servbay.com) designed for professional web developers. ServBay includes support for a variety of development languages, databases, web servers, mail servers, DNS servers, object storage, reverse proxies, and even a professional SSL certificate management platform. Everything you need for web development is here. Get a professional local development environment set up in just 3 minutes.

![ServBay Dashboard](/images/dashboard.png)

## Features

### Multi-site Management

[Managing multiple websites](https://support.servbay.com/basic-usage/websites/adding-first-website) simultaneously? ServBay makes it easy.  Effortlessly configure and run numerous websites on your local machine, each with its own unique settings, domain, and development environment. ServBay's intuitive interface simplifies the process, allowing you to quickly switch between projects and manage their configurations without complex setup or conflicts.

![Multi-site Management](/images/hosts.png)

### Web Servers

ServBay includes the most popular [web servers](https://www.servbay.com/features/web-server), Caddy and NGINX, with support for HTTP/3 and CORS.  It also supports custom domains and [automated SSL configuration](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), eliminating the need to purchase domains and SSL certificates, saving significant costs during development.

![Web Servers](/images/web-servers.png)

### Web Development Languages

ServBay comes with [Node.js](https://www.servbay.com/features/nodejs) (versions 12-23) and [PHP](https://www.servbay.com/features/php) (versions 5.6-8.5), covering the needs of developers throughout the web development lifecycle. Developers can seamlessly switch between different versions and use different versions for different projects. This immense flexibility gives developers strong confidence.  ServBay also includes Python and Golang.

![Web Development Languages](/images/languages.png)

### Databases

[Databases](https://www.servbay.com/features/database) are essential for web development. ServBay includes [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage), and the increasingly popular [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage).  NoSQL databases are also covered, with [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage), and [MongoDB](https://www.servbay.com/features/database) ready to use out-of-the-box, requiring no configuration.  ServBay also integrates [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) and [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) for easy database management.

![Databases](/images/databases.png)

### Domain and DNS Services

[Domains](https://www.servbay.com/features/dns-server) are a consumable resource in the web development lifecycle. ServBay includes a [DNS server](https://www.servbay.com/features/dns-server), allowing developers to use non-existent domains and TLDs without registration, and even issue SSL certificates for them. This not only saves developers significant costs but also enhances security—hackers cannot access a non-existent domain. Additionally, ServBay provides a graphical interface for conveniently managing your /etc/hosts file.

![Domain and DNS Services](/images/dns.png)

### PKI and SSL Certificate Management

ServBay provides a [PKI system](https://www.servbay.com/features/ssl). Developers can create their own Certificate Authority (CA) and issue SSL certificates—particularly useful for small development teams.  Using a [private CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management), small teams can encrypt data transmission and establish internal trust within their development environment. This applies not just to web services, but also to databases, SMTP, and other services. ServBay even supports [S/MIME certificates](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) for email encryption, [code signing certificates](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate), and [PDF document signing certificates](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Of course, ServBay also supports obtaining and automatically renewing SSL certificates from Let's Encrypt, ZeroSSL, and Google Trust Services via [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Mail Server

Want to use SMTP/POP3 in your local development? No problem! ServBay includes a [built-in mail server](https://www.servbay.com/features/email-server).  Integrated with the PKI system, the mail server supports [STARTTLS and SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) without configuration.  Need to relay mail to an external [SMTP server](https://www.servbay.com/features/email-server)?  ServBay's mail server supports relaying.  We also support SpamAssassin, allowing you to score each outgoing email and reduce the chances of it being marked as spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Reverse Proxy

Need to temporarily share your project with users? Want to host a server at home but don't have a public IP address? ServBay has you covered.  It supports [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp, and Cloudflared for quickly sharing your website publicly.  Don't trust third-party services? ServBay also provides a public reverse proxy service, seamlessly integrated for one-click sharing.

*(Coming soon)*

### Project-Level Runtime Environments

ServBay offers project-level runtime environment configuration. You can configure and lock the required PHP and Node.js versions for different projects, making your project development more flexible and controllable.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Clean and Easy to Back Up

ServBay is a portable installation, leaving no residue on your system, unlike tools like Homebrew that can clutter your system files.  You can easily back up your data using Time Machine or rsync, ensuring data security.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

## Bundled Packages

ServBay comes with a variety of essential packages to streamline your development process:

- **Web Servers**: Caddy (2.8), Nginx (1.27) and Apache *(2.4, coming soon)*
- **Programming Languages**: PHP (From PHP 5.6 to PHP 8.5-Dev), Node.js (From Node.js 12 to Node.js 23), Python *(coming soon)*, Golang *(coming soon)*
- **SQL Databases**: MySQL (From MySQL 5.1 to MySQL 9.1), MariaDB (From MariaDB 10.4 to MariaDB 11.8), PostgreSQL (From PostgreSQL 10 to PostgreSQL 17)
- **NoSQL Databases**: Redis (7.2), Memcached (1.6), MongoDB (From MongoDB 5.0 to MongoDB 8.0) & MongoSH 2
- **DNS**: Built-in DNS server for local development (dnsmasq 2.9)
- **Email**: Mailpit for local email testing
- **Tunnel/Reverse Proxy**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Other Tools**: phpMyAdmin, Adminer, and more

![ServBay Bundled Packages](/images/services.png)

## Installation

Follow these steps to install ServBay:

1. Download the latest version of ServBay from the [official website](https://www.servbay.com).
2. Open the installer and follow the prompts to complete the installation.
3. Launch ServBay and follow the initial setup wizard to configure it.

## Documentation

For detailed documentation and usage guides, visit the [ServBay Documentation Center](https://support.servbay.com).

## Support

If you encounter any issues while using ServBay, you can get support through the following channels:

- [Help Center](https://support.servbay.com)
- [Discord Community](https://talk.servbay.com)
- [Telegram Community](https://telegram.servbay.dev)
- [WhatsApp Community](https://wa.servbay.dev)
- [WeChat Community](https://wechat-group.servbay.dev)
- [Submit an Issue](https://github.com/ServBay/ServBay/issues)

## Community

Join our community to exchange experiences with other developers and get the latest updates:

- [ServBay Blog](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Thank you for using ServBay! If you have any questions or suggestions, please feel free to reach out to us.
