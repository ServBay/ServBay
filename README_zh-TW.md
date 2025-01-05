# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## 簡介

告別管理開發環境的繁瑣！

ServBay 是一款功能強大且全面的[本地 Web 開發環境管理工具](https://www.servbay.com)，專為專業 Web 開發人員設計。ServBay 支援各種開發語言、資料庫、Web 伺服器、郵件伺服器、DNS 伺服器、物件儲存、反向代理，甚至還包括專業的 SSL 憑證管理平台。Web 開發所需的一切，這裡應有盡有。只需 3 分鐘即可搭建專業的本地開發環境。

![ServBay 儀表板](/images/dashboard.png)

## 功能

### 多站點管理

需要[同時管理多個網站](https://support.servbay.com/basic-usage/websites/adding-first-website)？ServBay 讓這變得輕而易舉。在本地輕鬆配置和運行多個網站，每個網站都有其獨特的設定、網域和開發環境。ServBay 直觀的介面簡化了流程，讓您無需複雜的設定或擔心衝突即可快速切換專案並管理其配置。

![多站點管理](/images/hosts.png)

### Web 伺服器

ServBay 包含最流行的[Web 伺服器](https://www.servbay.com/features/web-server) Caddy 和 NGINX，並支援 HTTP/3 和 CORS。它還支援自訂網域和[自動 SSL 配置](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website)，無需購買網域和 SSL 憑證，從而節省了大量的開發成本。

![Web 伺服器](/images/web-servers.png)

### Web 開發語言

ServBay 預裝了[Node.js](https://www.servbay.com/features/nodejs)（版本 12-23）和[PHP](https://www.servbay.com/features/php)（版本 5.6-8.5），涵蓋了 Web 開發人員在整個開發週期中的需求。開發人員可以無縫切換不同版本，並為不同專案使用不同版本。這種極大的靈活性為開發人員提供了強大的信心。ServBay 還包含 Python 和 Golang。

![Web 開發語言](/images/languages.png)

### 資料庫

[資料庫](https://www.servbay.com/features/database)是 Web 開發必不可少的組成部分。ServBay 包含[MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage)、[MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage)和日益流行的[PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage)。NoSQL 資料庫也涵蓋在內，[Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage)、[Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage)和[MongoDB](https://www.servbay.com/features/database) 開箱即用，無需任何配置。ServBay 還整合了[phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database)和[Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database)，方便資料庫管理。

![資料庫](/images/databases.png)

### 網域和 DNS 服務

[網域](https://www.servbay.com/features/dns-server)是 Web 開發生命週期中的消耗性資源。ServBay 包含一個[DNS 伺服器](https://www.servbay.com/features/dns-server)，允許開發人員使用未註冊的網域和頂級網域，甚至可以為它們頒發 SSL 憑證。這不僅為開發人員節省了大量成本，還增強了安全性——駭客無法存取不存在的網域。此外，ServBay 提供了圖形介面，方便管理您的 /etc/hosts 檔案。

![網域和 DNS 服務](/images/dns.png)

### PKI 和 SSL 憑證管理

ServBay 提供了一個[PKI 系統](https://www.servbay.com/features/ssl)。開發人員可以建立自己的憑證頒發機構 (CA) 並頒發 SSL 憑證——這對於小型開發團隊尤其有用。使用[私人 CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management)，小型團隊可以加密資料傳輸並在其開發環境中建立內部信任。這不僅適用於 Web 服務，還適用於資料庫、SMTP 和其他服務。ServBay 甚至支援用於電子郵件加密的[S/MIME 憑證](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate)、[程式碼簽章憑證](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate)和[PDF 文件簽章憑證](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate)。

當然，ServBay 也支援透過 [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate) 從 Let's Encrypt、ZeroSSL 和 Google Trust Services 取得和自動續訂 SSL 憑證。


![PKI 和 SSL 憑證管理](/images/ssl-pki.png)

### 郵件伺服器

想在本地開發中使用 SMTP/POP3？沒問題！ServBay 包含一個[內建郵件伺服器](https://www.servbay.com/features/email-server)。該郵件伺服器與 PKI 系統整合，無需配置即可支援 [STARTTLS 和 SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings)。需要將郵件轉發到外部 [SMTP 伺服器](https://www.servbay.com/features/email-server)？ServBay 的郵件伺服器支援轉發。我們還支援 SpamAssassin，允許您對每封外寄電子郵件進行評分，降低其被標記為垃圾郵件的可能性。

![郵件伺服器](/images/email-server.png)

![郵件伺服器網頁信箱](/images/email-server-webmail.png)

### 反向代理

需要臨時與使用者共用您的專案？想在家託管伺服器但沒有公網 IP 位址？ServBay 可以幫您解決。它支援 [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok)、frp 和 Cloudflared，可以快速公開分享您的網站。不信任第三方服務？ServBay 還提供公共反向代理服務，無縫整合，一鍵共用。

*(即將推出)*

### 專案級執行環境

ServBay 提供專案級執行環境配置。您可以為不同的專案配置和鎖定所需的 PHP 和 Node.js 版本，使您的專案開發更加彈性可控。

![專案級執行環境](/images/project-level-runtime.png)

### 乾淨且易於備份

ServBay 是一款可攜式的安裝程式，不會在您的系統上留下任何殘留，不像 Homebrew 等工具會使您的系統檔案混亂。您可以使用 Time Machine 或 rsync 輕鬆備份資料，確保資料安全。

![乾淨且易於備份](/images/easy-to-backup.png)

## 附帶軟體包

ServBay 附帶各種必要的軟體包，以簡化您的開發流程：

- **Web 伺服器**: Caddy (2.8), Nginx (1.27) 和 Apache *(2.4, 即將推出)*
- **程式語言**: PHP (從 PHP 5.6 到 PHP 8.5-Dev), Node.js (從 Node.js 12 到 Node.js 23), Python *(即將推出)*, Golang *(即將推出)*
- **SQL 資料庫**: MySQL (從 MySQL 5.1 到 MySQL 9.1), MariaDB (從 MariaDB 10.4 到 MariaDB 11.8), PostgreSQL (從 PostgreSQL 10 到 PostgreSQL 17)
- **NoSQL 資料庫**: Redis (7.2), Memcached (1.6), MongoDB (從 MongoDB 5.0 到 MongoDB 8.0) & MongoSH 2
- **DNS**: 用於本地開發的內建 DNS 伺服器 (dnsmasq 2.9)
- **電子郵件**: Mailpit 用於本地電子郵件測試
- **通道/反向代理**: Cloudflared, frp, Ngrok, Oray 花生殼
- **其他工具**: phpMyAdmin, Adminer, 等等

![ServBay 附帶軟體包](/images/services.png)

## 安裝

按照以下步驟安裝 ServBay：

1. 從[官方網站](https://www.servbay.com)下載最新版本的 ServBay。
2. 開啟安裝程式並按照提示完成安裝。
3. 啟動 ServBay 並按照初始設定精靈進行配置。

## 文件

有關詳細的文件和使用指南，請造訪 [ServBay 文件中心](https://support.servbay.com)。

## 支援

如果您在使用 ServBay 時遇到任何問題，可以透過以下管道獲得支援：

- [說明中心](https://support.servbay.com)
- [Discord 社群](https://talk.servbay.com)
- [Telegram 社群](https://telegram.servbay.dev)
- [WhatsApp 社群](https://wa.servbay.dev)
- [微信社群](https://wechat-group.servbay.dev)
- [提交問題](https://github.com/ServBay/ServBay/issues)


## 社群

加入我們的社群，與其他開發者交流經驗並取得最新動態：

- [ServBay 部落格](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [微博](https://weibo.com/ServBay)
- [微信](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

感謝您使用 ServBay！如果您有任何問題或建議，請隨時聯絡我們。
