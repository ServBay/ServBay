# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## 简介

别再浪费时间管理您的开发环境了！

ServBay 是一款功能强大且全面的本地 Web 开发环境管理工具，专为专业 Web 开发人员设计，现已支持 **macOS 和 Windows**。ServBay 支持多种开发语言、数据库、Web 服务器、邮件服务器、DNS 服务器和反向代理。现在，它还集成了 Ollama 的 AI 开发功能、MinIO 的对象存储、Typesense 和 Meilisearch 的强大搜索功能，以及一个健壮的备份系统。您进行 Web 开发所需的一切都在这里。只需 3 分钟即可搭建专业的本地开发环境。

![ServBay Dashboard](/images/dashboard.png)

## 功能特性

### 多站点管理

同时管理多个网站？ServBay 让这一切变得简单。您可以在本地轻松配置和运行多个网站，每个网站都有其独特的设置、域名和开发环境。ServBay 直观的界面简化了这一过程，让您可以快速在项目之间切换并管理它们的配置，而无需复杂的设置或担心冲突。

![Multi-site Management](/images/website.png)

### Web 服务器

ServBay 包含了最流行的 Web 服务器——**Caddy、NGINX 和 Apache**——并支持 HTTP/3 和 CORS。它还支持自定义域名和自动 SSL 配置，无需购买域名和 SSL 证书，从而在开发过程中节省大量成本。

![Web Servers](/images/web-servers.png)

### Web 开发语言

ServBay 提供了海量的开发语言，包括 **PHP** (5.6-8.5)、**Node.js** (12-24)、**Python** (2.7, 3.5-3.14)、**Go** (1.11-1.24)、**Java** (OpenJDK 7-24)、**Ruby** (2.4-3.4)、**Rust**，甚至还有 **.NET** (2.0-10.0) 和 **Mono**。开发人员可以在不同版本之间无缝切换，并为不同项目使用不同版本。这种巨大的灵活性为开发人员带来了强大的信心。

![Web Development Languages](/images/languages.png)

### 数据库

数据库对于 Web 开发至关重要。ServBay 包含了 **MySQL**、**MariaDB** 以及日益流行的 **PostgreSQL**。NoSQL 数据库也一应俱全，**Redis**、**Memcached** 和 **MongoDB** 开箱即用，无需任何配置。ServBay 还集成了 **phpMyAdmin** 和 **Adminer**，方便数据库管理。

![Databases](/images/databases.png)

### 使用 Ollama 进行 AI 开发

通过集成的 AI 功能拥抱开发的未来。ServBay 整合了 Ollama，让您可以在本地运行强大的大语言模型 (LLM)，如 Llama 3、Mistral 和 Gemma。构建和测试 AI 驱动的应用程序，实现零延迟和完全的数据隐私，所有这一切都通过 ServBay 直观的界面进行管理。

![AI Development with Ollama](/images/ai.png)

### 使用 Typesense & Meilisearch 实现强大搜索

使用现代、快速的搜索引擎为您的应用程序赋能。ServBay 同时包含了 **Typesense** 和 **Meilisearch**，这是两个领先的开源搜索解决方案，您只需一键即可将其添加到您的项目中。

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### 使用 MinIO 进行对象存储

通过 MinIO 轻松管理非结构化数据，这是一种高性能、与 S3 兼容的对象存储服务，现已包含在 ServBay 中。它非常适合存储从备份、日志到媒体文件和工件的所有内容，为您的本地开发需求提供了强大的存储解决方案。

![Object Storage with MinIO](/images/minio.png)

### 域名和 DNS 服务

域名是 Web 开发生命周期中的一种消耗性资源。ServBay 包含一个 DNS 服务器，允许开发人员使用不存在的域名和顶级域名 (TLD) 而无需注册，甚至可以为它们颁发 SSL 证书。这不仅为开发人员节省了大量成本，还增强了安全性——黑客无法访问一个不存在的域名。此外，ServBay 还提供了一个图形化界面，方便您管理 hosts 文件。

![Domain and DNS Services](/images/dns.png)

### PKI 和 SSL 证书管理

ServBay 提供了一个 PKI 系统。开发人员可以创建自己的证书颁发机构 (CA) 并颁发 SSL 证书——这对于小型开发团队尤其有用。通过使用私有 CA，小团队可以在其开发环境中加密数据传输并建立内部信任。这不仅适用于 Web 服务，也适用于数据库、SMTP 和其他服务。ServBay 甚至支持用于邮件加密的 S/MIME 证书、代码签名证书和 PDF 文档签名证书。

当然，ServBay 也支持通过 ACME 从 Let's Encrypt、ZeroSSL 和 Google Trust Services 获取并自动续订 SSL 证书。

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### 邮件服务器

想在本地开发中使用 SMTP/POP3 吗？没问题！ServBay 内置了一个邮件服务器，并配有 **Mailpit** 用于本地邮件测试。与 PKI 系统集成，该邮件服务器无需配置即可支持 STARTTLS 和 SSL/TLS。需要将邮件中继到外部 SMTP 服务器吗？ServBay 的邮件服务器支持中继功能。我们还支持 SpamAssassin，让您可以为每封外发邮件打分，降低其被标记为垃圾邮件的几率。

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### 反向代理

需要临时与用户分享您的项目吗？想在家里托管服务器但没有公网 IP 地址？ServBay 都为您考虑到了。它支持 **ngrok、frp、Cloudflared 和 Pinggy**，可快速将您的网站公开发布。

![Reverse Proxy](/images/tunnel.png)

### 项目级运行时环境

ServBay 提供项目级的运行时环境配置。您可以为不同项目配置并锁定所需的 PHP 和 Node.js 版本，使您的项目开发更加灵活可控。

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### 强大的备份与恢复

数据安全和环境恢复至关重要。ServBay 拥有全面的备份与恢复系统，让您高枕无忧。
*   **一键备份与计划备份**：配置自动、定时的备份，或手动触发对数据库、网站文件、服务配置和 SSL 证书的备份。
*   **轻松恢复与迁移**：在出现问题时快速将您的环境恢复到之前的状态，或使用备份轻松地将整个 ServBay 设置迁移到新机器上。

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## 内置软件包

ServBay 附带了多种必要的软件包，以简化您的开发流程：

-   **Web 服务器**: Caddy, Nginx, Apache
-   **编程语言**: PHP (5.6 ~ 8.5-Alpha), Node.js (12 ~ 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **SQL 数据库**: MySQL (5.1 ~ 9.3), MariaDB (10.4 ~ 12.0), PostgreSQL (10 ~ 17)
-   **NoSQL 数据库**: Redis, Memcached, MongoDB (5.0 ~ 8.0) & MongoSH 2
-   **AI / LLM**: Ollama
-   **搜索引擎**: Typesense, Meilisearch
-   **对象存储**: MinIO
-   **DNS**: 内置 DNS 服务器 (dnsmasq)
-   **邮件**: Mailpit 用于本地邮件测试
-   **隧道/反向代理**: Cloudflared, frp, Ngrok, Pinggy
-   **其他工具**: phpMyAdmin, Adminer, Composer 等

![ServBay Bundled Packages](/images/services.png)

## 安装

ServBay 支持 macOS 和 Windows。

### macOS

1.  从[官方网站](https://www.servbay.com/download)下载最新版本的 ServBay for macOS。
2.  打开安装程序并按照提示完成安装。
3.  启动 ServBay 并按照初始设置向导进行配置。

### Windows

1.  从[官方下载页面](https://www.servbay.com/download)或直接从 [Windows 版本仓库](https://github.com/ServBay/ServBay-Windows-Release)下载最新版本的 ServBay for Windows。
2.  运行安装程序并按照屏幕上的说明进行操作。
3.  启动 ServBay 开始配置您的本地开发环境。

## 文档

有关详细的文档和使用指南，请访问 [ServBay 文档中心](https://support.servbay.com)。

## 支持

如果您在使用 ServBay 过程中遇到任何问题，可以通过以下渠道获得支持：

-   [帮助中心](https://support.servbay.com)
-   [Discord 社区](https://talk.servbay.com)
-   [Telegram 社区](https://telegram.servbay.dev)
-   [WhatsApp 社区](https://wa.servbay.dev)
-   [微信社区](https://wechat-group.servbay.dev)
-   [提交问题 (Issue)](https://github.com/ServBay/ServBay/issues)

## 社区

加入我们的社区，与其他开发者交流经验并获取最新动态：

-   [ServBay 博客](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [微博](https://weibo.com/ServBay)
-   [微信公众号](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

感谢您使用 ServBay！如果您有任何问题或建议，请随时与我们联系。