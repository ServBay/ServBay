# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## イントロダクション

開発環境の管理に時間を浪費するのはもうやめましょう！

ServBayは、プロのWeb開発者向けに設計された、強力で包括的なローカルWeb開発環境管理ツールで、現在**macOSとWindows**の両方で利用可能です。ServBayは、さまざまな開発言語、データベース、Webサーバー、メールサーバー、DNSサーバー、リバースプロキシをサポートしています。さらに、Ollamaによる統合AI開発機能、MinIOによるオブジェクトストレージ、TypesenseとMeilisearchによる強力な検索機能、そして堅牢なバックアップシステムも搭載しています。Web開発に必要なすべてがここにあります。わずか3分でプロフェッショナルなローカル開発環境をセットアップできます。

![ServBay Dashboard](/images/dashboard.png)

## 機能

### マルチサイト管理

複数のウェブサイトを同時に管理していますか？ServBayなら簡単です。ローカルマシン上で多数のウェブサイトを簡単に設定・実行でき、それぞれに固有の設定、ドメイン、開発環境を持たせることができます。ServBayの直感的なインターフェースはプロセスを簡素化し、複雑な設定や競合なしにプロジェクト間を素早く切り替え、その設定を管理することができます。

![Multi-site Management](/images/website.png)

### Webサーバー

ServBayには、最も人気のあるWebサーバーである**Caddy、NGINX、Apache**が含まれており、HTTP/3とCORSをサポートしています。また、カスタムドメインと自動SSL設定もサポートしており、ドメインやSSL証明書を購入する必要がなく、開発中のコストを大幅に削減します。

![Web Servers](/images/web-servers.png)

### Web開発言語

ServBayには、**PHP** (5.6-8.5)、**Node.js** (12-24)、**Python** (2.7, 3.5-3.14)、**Go** (1.11-1.24)、**Java** (OpenJDK 7-24)、**Ruby** (2.4-3.4)、**Rust**、さらには**.NET** (2.0-10.0) & **Mono**など、膨大な数の開発言語が付属しています。開発者は異なるバージョン間をシームレスに切り替え、異なるプロジェクトに異なるバージョンを使用できます。この絶大な柔軟性は、開発者に強い自信を与えます。

![Web Development Languages](/images/languages.png)

### データベース

データベースはWeb開発に不可欠です。ServBayには、**MySQL**、**MariaDB**、そしてますます人気が高まっている**PostgreSQL**が含まれています。NoSQLデータベースもカバーしており、**Redis**、**Memcached**、**MongoDB**が設定不要ですぐに使用できます。ServBayは、簡単なデータベース管理のために**phpMyAdmin**と**Adminer**も統合しています。

![Databases](/images/databases.png)

### OllamaによるAI開発

統合されたAI機能で開発の未来を受け入れましょう。ServBayはOllamaを組み込んでおり、Llama 3、Mistral、Gemmaなどの強力な大規模言語モデル（LLM）をローカルで実行できます。ServBayの直感的なインターフェースを通じて、ゼロレイテンシーと完全なデータプライバシーでAI駆動のアプリケーションを構築・テストできます。

![AI Development with Ollama](/images/ai.png)

### Typesense & Meilisearchによる強力な検索

モダンで高速な検索エンジンでアプリケーションを強化しましょう。ServBayには、**Typesense**と**Meilisearch**の両方が含まれており、これらは主要なオープンソース検索ソリューションであり、ワンクリックでプロジェクトに追加できます。

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### MinIOによるオブジェクトストレージ

ServBayに含まれるようになった、高性能でS3互換のオブジェクトストレージサービスであるMinIOを使用して、非構造化データを簡単に管理できます。バックアップやログからメディアファイルやアーティファクトまで、あらゆるものを保存するのに最適で、ローカル開発のニーズに堅牢なストレージソリューションを提供します。

![Object Storage with MinIO](/images/minio.png)

### ドメインとDNSサービス

ドメインはWeb開発ライフサイクルにおける消耗品です。ServBayにはDNSサーバーが含まれており、開発者は存在しないドメインやTLDを登録なしで使用でき、それらにSSL証明書を発行することもできます。これにより、開発者のコストを大幅に節約するだけでなく、セキュリティも向上します。ハッカーは存在しないドメインにアクセスできません。さらに、ServBayはhostsファイルを便利に管理するためのグラフィカルインターフェースを提供します。

![Domain and DNS Services](/images/dns.png)

### PKIとSSL証明書の管理

ServBayはPKIシステムを提供します。開発者は独自の認証局（CA）を作成し、SSL証明書を発行できます。これは特に小規模な開発チームに役立ちます。プライベートCAを使用することで、小規模チームはデータ転送を暗号化し、開発環境内で内部的な信頼を確立できます。これはWebサービスだけでなく、データベース、SMTP、その他のサービスにも適用されます。ServBayは、メール暗号化用のS/MIME証明書、コード署名証明書、PDF文書署名証明書もサポートしています。

もちろん、ServBayはACMEを介してLet's Encrypt、ZeroSSL、Google Trust ServicesからSSL証明書を取得し、自動更新することもサポートしています。

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### メールサーバー

ローカル開発でSMTP/POP3を使用したいですか？問題ありません！ServBayには、ローカルでのメールテスト用に**Mailpit**を備えた内蔵メールサーバーが含まれています。PKIシステムと統合されており、メールサーバーは設定なしでSTARTTLSとSSL/TLSをサポートします。外部のSMTPサーバーにメールをリレーする必要がありますか？ServBayのメールサーバーはリレーをサポートしています。また、SpamAssassinもサポートしており、各送信メールにスコアを付け、スパムとしてマークされる可能性を減らすことができます。

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### リバースプロキシ

プロジェクトを一時的にユーザーと共有する必要がありますか？自宅でサーバーをホストしたいが、パブリックIPアドレスがありませんか？ServBayが対応します。**ngrok、frp、Cloudflared、Pinggy**をサポートしており、ウェブサイトを迅速に公開できます。

![Reverse Proxy](/images/tunnel.png)

### プロジェクトレベルのランタイム環境

ServBayはプロジェクトレベルのランタイム環境設定を提供します。異なるプロジェクトに必要なPHPとNode.jsのバージョンを設定・ロックすることができ、プロジェクト開発をより柔軟かつ制御可能にします。

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### 強力なバックアップと復元

データのセキュリティと環境の回復は非常に重要です。ServBayは、安心を提供するための包括的なバックアップと復元システムを備えています。
*   **ワンクリック＆スケジュールバックアップ**：データベース、ウェブサイトファイル、サービス設定、SSL証明書の自動、スケジュールバックアップを設定したり、手動でバックアップをトリガーしたりできます。
*   **簡単な復元と移行**：問題が発生した場合に環境を以前の状態に迅速に復元したり、バックアップを使用してServBayのセットアップ全体を新しいマシンに簡単に移行したりできます。

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## バンドルパッケージ

ServBayには、開発プロセスを効率化するためのさまざまな必須パッケージが付属しています。

-   **Webサーバー**：Caddy, Nginx, Apache
-   **プログラミング言語**：PHP (5.6から8.5-Alpha), Node.js (12から24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **SQLデータベース**：MySQL (5.1から9.3), MariaDB (10.4から12.0), PostgreSQL (10から17)
-   **NoSQLデータベース**：Redis, Memcached, MongoDB (5.0から8.0) & MongoSH 2
-   **AI / LLM**：Ollama
-   **検索エンジン**：Typesense, Meilisearch
-   **オブジェクトストレージ**：MinIO
-   **DNS**：内蔵DNSサーバー (dnsmasq)
-   **メール**：ローカルメールテスト用のMailpit
-   **トンネル/リバースプロキシ**：Cloudflared, frp, Ngrok, Pinggy
-   **その他のツール**：phpMyAdmin, Adminer, Composer, など

![ServBay Bundled Packages](/images/services.png)

## インストール

ServBayはmacOSとWindowsの両方で利用できます。

### macOS

1.  [公式サイト](https://www.servbay.com/download)からmacOS用のServBayの最新バージョンをダウンロードします。
2.  インストーラーを開き、プロンプトに従ってインストールを完了します。
3.  ServBayを起動し、初期設定ウィザードに従って設定します。

### Windows

1.  [公式ダウンロードページ](https://www.servbay.com/download)または直接[Windowsリリースリポジトリ](https://github.com/ServBay/ServBay-Windows-Release)からWindows用のServBayの最新バージョンをダウンロードします。
2.  インストーラーを実行し、画面の指示に従います。
3.  ServBayを起動して、ローカル開発環境の設定を開始します。

## ドキュメンテーション

詳細なドキュメンテーションと使用ガイドについては、[ServBayドキュメンテーションセンター](https://support.servbay.com)をご覧ください。

## サポート

ServBayの使用中に問題が発生した場合は、以下のチャネルを通じてサポートを受けることができます。

-   [ヘルプセンター](https://support.servbay.com)
-   [Discordコミュニティ](https://talk.servbay.com)
-   [Telegramコミュニティ](https://telegram.servbay.dev)
-   [WhatsAppコミュニティ](https://wa.servbay.dev)
-   [WeChatコミュニティ](https://wechat-group.servbay.dev)
-   [問題を報告](https://github.com/ServBay/ServBay/issues)

## コミュニティ

私たちのコミュニティに参加して、他の開発者と経験を交換し、最新のアップデートを入手してください。

-   [ServBayブログ](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

ServBayをご利用いただきありがとうございます！ご質問やご提案がございましたら、お気軽にお問い合わせください。