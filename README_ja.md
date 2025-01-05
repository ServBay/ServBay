# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## はじめに

開発環境の管理に時間を浪費するのはもうやめましょう！

ServBayは、プロのWeb開発者向けに設計された、強力で包括的な[ローカルWeb開発環境管理ツール](https://www.servbay.com)です。ServBayは、さまざまな開発言語、データベース、Webサーバー、メールサーバー、DNSサーバー、オブジェクトストレージ、リバースプロキシ、さらにはプロフェッショナルなSSL証明書管理プラットフォームをサポートしています。Web開発に必要なものはすべてここにあります。わずか3分でプロフェッショナルなローカル開発環境をセットアップできます。

![ServBay ダッシュボード](/images/dashboard.png)

## 機能

### マルチサイト管理

[複数のWebサイトを同時に管理](https://support.servbay.com/basic-usage/websites/adding-first-website)する必要がありますか？ServBayなら簡単です。ローカルマシンで、それぞれ独自の固有の設定、ドメイン、開発環境を持つ多数のWebサイトを簡単に設定して実行できます。ServBayの直感的なインターフェースにより、複雑な設定や競合なしにプロジェクトをすばやく切り替え、構成を管理できます。

![マルチサイト管理](/images/hosts.png)

### Webサーバー

ServBayには、HTTP/3とCORSをサポートする、最も人気のある[Webサーバー](https://www.servbay.com/features/web-server)であるCaddyとNGINXが含まれています。また、カスタムドメインと[自動SSL構成](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website)もサポートしているため、ドメインとSSL証明書を購入する必要がなく、開発中のコストを大幅に節約できます。

![Webサーバー](/images/web-servers.png)

### Web開発言語

ServBayには、[Node.js](https://www.servbay.com/features/nodejs)（バージョン12〜23）と[PHP](https://www.servbay.com/features/php)（バージョン5.6〜8.5）が付属しており、Web開発ライフサイクル全体を通して開発者のニーズを満たします。開発者は、異なるバージョン間をシームレスに切り替えたり、異なるプロジェクトに異なるバージョンを使用したりできます。この大きな柔軟性は、開発者に強い自信を与えます。ServBayには、PythonとGolangも含まれています。

![Web開発言語](/images/languages.png)

### データベース

[データベース](https://www.servbay.com/features/database)は、Web開発に不可欠です。ServBayには、[MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage)、[MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage)、そしてますます人気が高まっている[PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage)が含まれています。NoSQLデータベースもカバーされており、[Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage)、[Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage)、[MongoDB](https://www.servbay.com/features/database)は設定不要ですぐに使用できます。ServBayは、データベース管理を容易にするために、[phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database)と[Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database)も統合しています。

![データベース](/images/databases.png)

### ドメインとDNSサービス

[ドメイン](https://www.servbay.com/features/dns-server)は、Web開発ライフサイクルにおける消耗性のリソースです。ServBayには[DNSサーバー](https://www.servbay.com/features/dns-server)が含まれているため、開発者は登録されていないドメインやTLDを使用でき、それらにSSL証明書を発行することもできます。これにより、開発者のコストを大幅に節約できるだけでなく、セキュリティも強化されます。ハッカーは存在しないドメインにアクセスできません。さらに、ServBayは、/etc/hostsファイルを便利に管理するためのグラフィカルインターフェースを提供します。

![ドメインとDNSサービス](/images/dns.png)

### PKIとSSL証明書管理

ServBayは、[PKIシステム](https://www.servbay.com/features/ssl)を提供します。開発者は独自の認証局（CA）を作成し、SSL証明書を発行できます。これは、小規模の開発チームにとって特に便利です。[プライベートCA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management)を使用することで、小規模チームはデータ転送を暗号化し、開発環境内で内部信頼を確立できます。これは、Webサービスだけでなく、データベース、SMTP、その他のサービスにも適用されます。ServBayは、電子メールの暗号化用の[S/MIME証明書](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate)、[コード署名証明書](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate)、および[PDFドキュメント署名証明書](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate)もサポートしています。

もちろん、ServBayは、[ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate)を介してLet's Encrypt、ZeroSSL、およびGoogle Trust ServicesからSSL証明書を取得し、自動的に更新することもサポートしています。

![PKIとSSL証明書管理](/images/ssl-pki.png)

### メールサーバー

ローカル開発でSMTP/POP3を使用したいですか？問題ありません！ServBayには、[組み込みメールサーバー](https://www.servbay.com/features/email-server)が含まれています。PKIシステムと統合されたメールサーバーは、構成なしで[STARTTLSとSSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings)をサポートします。外部の[SMTPサーバー](https://www.servbay.com/features/email-server)にメールをリレーする必要がありますか？ServBayのメールサーバーはリレーをサポートしています。また、SpamAssassinもサポートしているため、送信メールごとにスコアを付け、スパムとしてマークされる可能性を減らすことができます。


![メールサーバー](/images/email-server.png)

![メールサーバーWebメール](/images/email-server-webmail.png)

### リバースプロキシ

プロジェクトを一時的にユーザーと共有する必要がありますか？自宅でサーバーをホストしたいが、パブリックIPアドレスがありませんか？ServBayが対応します。Webサイトを迅速に公開するために、[ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok)、frp、Cloudflaredをサポートしています。サードパーティサービスを信頼していませんか？ServBayは、パブリックリバースプロキシサービスも提供しており、ワンクリック共有のためにシームレスに統合されています。

*(近日公開)*

### プロジェクトレベルのランタイム環境

ServBayは、プロジェクトレベルのランタイム環境設定を提供します。異なるプロジェクトに必要なPHPとNode.jsのバージョンを設定してロックできるため、プロジェクト開発の柔軟性と制御性を高めることができます。

![プロジェクトレベルのランタイム環境](/images/project-level-runtime.png)

### クリーンで簡単なバックアップ

ServBayはポータブルインストールであるため、システムファイルが乱雑になるHomebrewなどのツールとは異なり、システムに痕跡を残しません。Time Machineまたはrsyncを使用してデータを簡単にバックアップできるため、データセキュリティが確保されます。

![クリーンで簡単なバックアップ](/images/easy-to-backup.png)

## バンドルされたパッケージ

ServBayには、開発プロセスを合理化するためのさまざまな必須パッケージが付属しています。

- **Webサーバー**: Caddy (2.8)、Nginx (1.27)、Apache *(2.4、近日公開)*
- **プログラミング言語**: PHP (PHP 5.6からPHP 8.5-Devまで)、Node.js (Node.js 12からNode.js 23まで)、Python *(近日公開)*、Golang *(近日公開)*
- **SQLデータベース**: MySQL (MySQL 5.1からMySQL 9.1まで)、MariaDB (MariaDB 10.4からMariaDB 11.8まで)、PostgreSQL (PostgreSQL 10からPostgreSQL 17まで)
- **NoSQLデータベース**: Redis (7.2)、Memcached (1.6)、MongoDB (MongoDB 5.0からMongoDB 8.0まで) & MongoSH 2
- **DNS**: ローカル開発用の組み込みDNSサーバー (dnsmasq 2.9)
- **電子メール**: ローカル電子メールテスト用のMailpit
- **トンネル/リバースプロキシ**: Cloudflared、frp、Ngrok、Oray 花生殼
- **その他のツール**: phpMyAdmin、Adminerなど

![ServBay バンドルされたパッケージ](/images/services.png)

## インストール

ServBayをインストールするには、次の手順に従います。

1. [公式サイト](https://www.servbay.com)からServBayの最新バージョンをダウンロードします。
2. インストーラーを開き、プロンプトに従ってインストールを完了します。
3. ServBayを起動し、初期設定ウィザードに従って構成します。

## ドキュメント

詳細なドキュメントと使用ガイドについては、[ServBayドキュメントセンター](https://support.servbay.com)をご覧ください。

## サポート

ServBayの使用中に問題が発生した場合は、次のチャネルからサポートを受けることができます。

- [ヘルプセンター](https://support.servbay.com)
- [Discordコミュニティ](https://talk.servbay.com)
- [Telegramコミュニティ](https://telegram.servbay.dev)
- [WhatsAppコミュニティ](https://wa.servbay.dev)
- [WeChatコミュニティ](https://wechat-group.servbay.dev)
- [問題を提出する](https://github.com/ServBay/ServBay/issues)

## コミュニティ

コミュニティに参加して、他の開発者と経験を交換し、最新のアップデートを入手してください。

- [ServBayブログ](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [微博](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

ServBayをご利用いただきありがとうございます！ご質問やご提案がございましたら、お気軽にお問い合わせください。
