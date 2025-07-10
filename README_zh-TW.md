# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## 簡介

別再浪費時間管理您的開發環境了！

ServBay 是一款功能強大且全面的本地 Web 開發環境管理工具，專為專業 Web 開發人員設計，現已支援 **macOS 和 Windows**。ServBay 支援多種開發語言、資料庫、Web 伺服器、郵件伺服器、DNS 伺服器和反向代理。現在它還整合了 Ollama 的 AI 開發功能、MinIO 的物件儲存、Typesense 和 Meilisearch 的強大搜尋功能，以及一個健全的備份系統。您進行 Web 開發所需的一切都在這裡。只需 3 分鐘，即可建立一個專業的本地開發環境。

![ServBay Dashboard](/images/dashboard.png)

## 功能特性

### 多站點管理

同時管理多個網站？ServBay 讓這一切變得輕而易舉。您可以在本地機器上輕鬆設定並運行多個網站，每個網站都有其獨特的設定、網域和開發環境。ServBay 直觀的介面簡化了流程，讓您可以快速在專案之間切換並管理其設定，而不會出現複雜的設定或衝突。

![Multi-site Management](/images/website.png)

### Web 伺服器

ServBay 包含了最受歡迎的 Web 伺服器——**Caddy、NGINX 和 Apache**——並支援 HTTP/3 和 CORS。它還支援自訂網域和自動化 SSL 設定，無需購買網域和 SSL 憑證，在開發過程中節省大量成本。

![Web Servers](/images/web-servers.png)

### Web 開發語言

ServBay 附帶了大量的開發語言，包括 **PHP** (5.6-8.5)、**Node.js** (12-24)、**Python** (2.7, 3.5-3.14)、**Go** (1.11-1.24)、**Java** (OpenJDK 7-24)、**Ruby** (2.4-3.4)、**Rust**，甚至還有 **.NET** (2.0-10.0) 和 **Mono**。開發人員可以無縫切換不同版本，並為不同專案使用不同版本。這種巨大的靈活性給予開發人員強大的信心。

![Web Development Languages](/images/languages.png)

### 資料庫

資料庫對 Web 開發至關重要。ServBay 包含了 **MySQL**、**MariaDB** 和日益流行的 **PostgreSQL**。NoSQL 資料庫也涵蓋在內，**Redis**、**Memcached** 和 **MongoDB** 開箱即用，無需任何設定。ServBay 還整合了 **phpMyAdmin** 和 **Adminer**，方便資料庫管理。

![Databases](/images/databases.png)

### 使用 Ollama 進行 AI 開發

透過整合的 AI 功能，擁抱開發的未來。ServBay 整合了 Ollama，讓您可以在本地運行強大的大型語言模型（LLM），如 Llama 3、Mistral 和 Gemma。透過 ServBay 直觀的介面，您可以建立和測試 AI 驅動的應用程式，實現零延遲和完全的資料隱私。

![AI Development with Ollama](/images/ai.png)

### 使用 Typesense 和 Meilisearch 進行強大搜尋

用現代、快速的搜尋引擎為您的應用程式提供動力。ServBay 包含了 **Typesense** 和 **Meilisearch**，這兩個領先的開源搜尋解決方案，您可以一鍵將它們添加到您的專案中。

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### 使用 MinIO 進行物件儲存

使用 MinIO 輕鬆管理非結構化資料，這是一個高效能、與 S3 相容的物件儲存服務，現已包含在 ServBay 中。它非常適合儲存從備份和日誌到媒體檔案和成品等各種內容，為您的本地開發需求提供了一個健全的儲存解決方案。

![Object Storage with MinIO](/images/minio.png)

### 網域和 DNS 服務

網域是 Web 開發生命週期中的一種消耗性資源。ServBay 包含一個 DNS 伺服器，允許開發人員使用不存在的網域和 TLD，無需註冊，甚至可以為它們頒發 SSL 憑證。這不僅為開發人員節省了大量成本，還增強了安全性——駭客無法存取一個不存在的網域。此外，ServBay 還提供了一個圖形介面，方便管理您的 hosts 檔案。

![Domain and DNS Services](/images/dns.png)

### PKI 和 SSL 憑證管理

ServBay 提供了一個 PKI 系統。開發人員可以創建自己的憑證頒發機構（CA）並頒發 SSL 憑證——這對小型開發團隊特別有用。使用私有 CA，小型團隊可以加密資料傳輸並在他們的開發環境中建立內部信任。這不僅適用於 Web 服務，也適用於資料庫、SMTP 和其他服務。ServBay 甚至支援用於郵件加密的 S/MIME 憑證、程式碼簽章憑證和 PDF 文件簽章憑證。

當然，ServBay 也支援透過 ACME 從 Let's Encrypt、ZeroSSL 和 Google Trust Services 獲取並自動續訂 SSL 憑證。

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### 郵件伺服器

想在本地開發中使用 SMTP/POP3 嗎？沒問題！ServBay 包含一個內建的郵件伺服器，並附帶 **Mailpit** 用於本地郵件測試。與 PKI 系統整合，郵件伺服器無需設定即可支援 STARTTLS 和 SSL/TLS。需要將郵件轉發到外部 SMTP 伺服器嗎？ServBay 的郵件伺服器支援轉發。我們還支援 SpamAssassin，讓您為每封外寄郵件評分，減少其被標記為垃圾郵件的機會。

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### 反向代理

需要臨時將您的專案分享給用戶嗎？想在家裡託管伺服器但沒有公用 IP 位址？ServBay 為您解決了這些問題。它支援 **ngrok、frp、Cloudflared 和 Pinggy**，可以快速將您的網站公開分享。

![Reverse Proxy](/images/tunnel.png)

### 專案級運行環境

ServBay 提供專案級的運行環境設定。您可以為不同專案設定並鎖定所需的 PHP 和 Node.js 版本，使您的專案開發更加靈活和可控。

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### 強大的備份與還原

資料安全和環境恢復至關重要。ServBay 具有全面的備份和還原系統，讓您高枕無憂。
*   **一鍵與排程備份**：設定自動、排程備份，或手動觸發資料庫、網站檔案、服務設定和 SSL 憑證的備份。
*   **輕鬆還原與遷移**：在出現問題時快速將您的環境還原到先前的狀態，或使用備份輕鬆將您的整個 ServBay 設定遷移到新機器上。

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## 捆綁套件

ServBay 附帶多種必要的套件，以簡化您的開發流程：

-   **Web 伺服器**：Caddy、Nginx、Apache
-   **程式語言**：PHP (5.6 至 8.5-Alpha)、Node.js (12 至 24)、Python (2.7, 3.5-3.14)、Golang (1.11-1.24)、Java (OpenJDK 7-24)、.NET (2.0-10.0)、Mono (6.14)、Ruby (2.4-3.4)、Rust
-   **SQL 資料庫**：MySQL (5.1 至 9.3)、MariaDB (10.4 至 12.0)、PostgreSQL (10 至 17)
-   **NoSQL 資料庫**：Redis、Memcached、MongoDB (5.0 至 8.0) 和 MongoSH 2
-   **AI / LLM**：Ollama
-   **搜尋引擎**：Typesense、Meilisearch
-   **物件儲存**：MinIO
-   **DNS**：內建 DNS 伺服器 (dnsmasq)
-   **郵件**：用於本地郵件測試的 Mailpit
-   **隧道/反向代理**：Cloudflared、frp、Ngrok、Pinggy
-   **其他工具**：phpMyAdmin、Adminer、Composer 等等

![ServBay Bundled Packages](/images/services.png)

## 安裝

ServBay 適用於 macOS 和 Windows。

### macOS

1.  從[官方網站](https://www.servbay.com/download)下載最新版本的 ServBay for macOS。
2.  打開安裝程式並按照提示完成安裝。
3.  啟動 ServBay 並按照初始設定精靈進行設定。

### Windows

1.  從[官方下載頁面](https://www.servbay.com/download)或直接從 [Windows 發行版本庫](https://github.com/ServBay/ServBay-Windows-Release)下載最新版本的 ServBay for Windows。
2.  運行安裝程式並按照螢幕上的說明操作。
3.  啟動 ServBay 開始設定您的本地開發環境。

## 文件

有關詳細的文件和使用指南，請訪問 [ServBay 文件中心](https://support.servbay.com)。

## 支援

如果您在使用 ServBay 時遇到任何問題，可以透過以下管道獲得支援：

-   [幫助中心](https://support.servbay.com)
-   [Discord 社群](https://talk.servbay.com)
-   [Telegram 社群](https://telegram.servbay.dev)
-   [WhatsApp 社群](https://wa.servbay.dev)
-   [WeChat 社群](https://wechat-group.servbay.dev)
-   [提交問題](https://github.com/ServBay/ServBay/issues)

## 社群

加入我們的社群，與其他開發人員交流經驗並獲取最新更新：

-   [ServBay 部落格](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [微博](https://weibo.com/ServBay)
-   [微信](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

感謝您使用 ServBay！如果您有任何問題或建議，請隨時與我們聯繫。
