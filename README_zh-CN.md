# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## 简介

告别管理开发环境的繁琐！

ServBay 是一款功能强大且全面的[本地 Web 开发环境管理工具](https://www.servbay.com)，专为专业 Web 开发人员设计。ServBay 支持各种开发语言、数据库、Web 服务器、邮件服务器、DNS 服务器、对象存储、反向代理，甚至还包括专业的 SSL 证书管理平台。Web 开发所需的一切，这里应有尽有。只需 3 分钟即可搭建专业的本地开发环境。

![ServBay 仪表板](/images/dashboard.png)

## 功能

### 多站点管理

需要[同时管理多个网站](https://support.servbay.com/basic-usage/websites/adding-first-website)？ServBay 让这变得轻而易举。在本地轻松配置和运行多个网站，每个网站都有其独特的设置、域名和开发环境。ServBay 直观的界面简化了流程，让您无需复杂的设置或担心冲突即可快速切换项目并管理其配置。

![多站点管理](/images/hosts.png)

### Web 服务器

ServBay 包含最流行的[Web 服务器](https://www.servbay.com/features/web-server) Caddy 和 NGINX，并支持 HTTP/3 和 CORS。它还支持自定义域名和[自动 SSL 配置](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website)，无需购买域名和 SSL 证书，从而节省了大量的开发成本。

![Web 服务器](/images/web-servers.png)

### Web 开发语言

ServBay 预装了[Node.js](https://www.servbay.com/features/nodejs)（版本 12-23）和[PHP](https://www.servbay.com/features/php)（版本 5.6-8.5），涵盖了 Web 开发人员在整个开发周期中的需求。开发人员可以无缝切换不同版本，并为不同项目使用不同版本。这种极大的灵活性为开发人员提供了强大的信心。ServBay 还包含 Python 和 Golang。

![Web 开发语言](/images/languages.png)

### 数据库

[数据库](https://www.servbay.com/features/database)是 Web 开发必不可少的组成部分。ServBay 包含[MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage)、[MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage)和日益流行的[PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage)。NoSQL 数据库也涵盖在内，[Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage)、[Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage)和[MongoDB](https://www.servbay.com/features/database) 开箱即用，无需任何配置。ServBay 还集成了[phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database)和[Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database)，方便数据库管理。

![数据库](/images/databases.png)

### 域名和 DNS 服务

[域名](https://www.servbay.com/features/dns-server)是 Web 开发生命周期中的消耗性资源。ServBay 包含一个[DNS 服务器](https://www.servbay.com/features/dns-server)，允许开发人员使用未注册的域名和顶级域名，甚至可以为它们颁发 SSL 证书。这不仅为开发人员节省了大量成本，还增强了安全性——黑客无法访问不存在的域名。此外，ServBay 提供了图形界面，方便管理您的 /etc/hosts 文件。

![域名和 DNS 服务](/images/dns.png)

### PKI 和 SSL 证书管理

ServBay 提供了一个[PKI 系统](https://www.servbay.com/features/ssl)。开发人员可以创建自己的证书颁发机构 (CA) 并颁发 SSL 证书——这对于小型开发团队尤其有用。使用[私有 CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management)，小型团队可以加密数据传输并在其开发环境中建立内部信任。这不仅适用于 Web 服务，还适用于数据库、SMTP 和其他服务。ServBay 甚至支持用于电子邮件加密的[S/MIME 证书](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate)、[代码签名证书](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate)和[PDF 文档签名证书](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate)。

当然，ServBay 也支持通过 [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate) 从 Let's Encrypt、ZeroSSL 和 Google Trust Services 获取和自动续订 SSL 证书。


![PKI 和 SSL 证书管理](/images/ssl-pki.png)

### 邮件服务器

想在本地开发中使用 SMTP/POP3？没问题！ServBay 包含一个[内置邮件服务器](https://www.servbay.com/features/email-server)。该邮件服务器与 PKI 系统集成，无需配置即可支持 [STARTTLS 和 SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings)。需要将邮件转发到外部 [SMTP 服务器](https://www.servbay.com/features/email-server)？ServBay 的邮件服务器支持转发。我们还支持 SpamAssassin，允许您对每封外发电子邮件进行评分，降低其被标记为垃圾邮件的可能性。

![邮件服务器](/images/email-server.png)

![邮件服务器网页邮箱](/images/email-server-webmail.png)

### 反向代理

需要临时与用户共享您的项目？想在家托管服务器但没有公网 IP 地址？ServBay 可以帮您解决。它支持 [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok)、frp 和 Cloudflared，可以快速公开分享您的网站。不信任第三方服务？ServBay 还提供公共反向代理服务，无缝集成，一键共享。

*(即将推出)*

### 项目级运行时环境

ServBay 提供项目级运行时环境配置。您可以为不同的项目配置和锁定所需的 PHP 和 Node.js 版本，使您的项目开发更加灵活可控。

![项目级运行时环境](/images/project-level-runtime.png)

### 干净且易于备份

ServBay 是一个可移植的安装程序，不会在您的系统上留下任何残留，不像 Homebrew 等工具会使您的系统文件混乱。您可以使用 Time Machine 或 rsync 轻松备份数据，确保数据安全。

![干净且易于备份](/images/easy-to-backup.png)

## 附带软件包

ServBay 附带各种必要的软件包，以简化您的开发流程：

- **Web 服务器**: Caddy (2.8), Nginx (1.27) 和 Apache *(2.4, 即将推出)*
- **编程语言**: PHP (从 PHP 5.6 到 PHP 8.5-Dev), Node.js (从 Node.js 12 到 Node.js 23), Python *(即将推出)*, Golang *(即将推出)*
- **SQL 数据库**: MySQL (从 MySQL 5.1 到 MySQL 9.1), MariaDB (从 MariaDB 10.4 到 MariaDB 11.8), PostgreSQL (从 PostgreSQL 10 到 PostgreSQL 17)
- **NoSQL 数据库**: Redis (7.2), Memcached (1.6), MongoDB (从 MongoDB 5.0 到 MongoDB 8.0) & MongoSH 2
- **DNS**: 用于本地开发的内置 DNS 服务器 (dnsmasq 2.9)
- **电子邮件**: Mailpit 用于本地电子邮件测试
- **隧道/反向代理**: Cloudflared, frp, Ngrok, Oray 花生壳
- **其他工具**: phpMyAdmin, Adminer, 等等

![ServBay 附带软件包](/images/services.png)

## 安装

按照以下步骤安装 ServBay：

1. 从[官方网站](https://www.servbay.com)下载最新版本的 ServBay。
2. 打开安装程序并按照提示完成安装。
3. 启动 ServBay 并按照初始设置向导进行配置。

## 文档

有关详细的文档和使用指南，请访问 [ServBay 文档中心](https://support.servbay.com)。

## 支持

如果您在使用 ServBay 时遇到任何问题，可以通过以下渠道获得支持：

- [帮助中心](https://support.servbay.com)
- [Discord 社区](https://talk.servbay.com)
- [Telegram 社区](https://telegram.servbay.dev)
- [WhatsApp 社区](https://wa.servbay.dev)
- [微信社区](https://wechat-group.servbay.dev)
- [提交问题](https://github.com/ServBay/ServBay/issues)


## 社区

加入我们的社区，与其他开发者交流经验并获取最新动态：

- [ServBay 博客](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [微博](https://weibo.com/ServBay)
- [微信](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

感谢您使用 ServBay！如果您有任何问题或建议，请随时联系我们。
