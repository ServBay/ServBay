# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Giriş

Geliştirme ortamınızı yönetmekle zaman kaybetmeyi bırakın!

ServBay, profesyonel web geliştiricileri için tasarlanmış, hem **macOS hem de Windows** için mevcut olan güçlü ve kapsamlı bir yerel web geliştirme ortamı yönetim aracıdır. ServBay, çeşitli geliştirme dilleri, veritabanları, web sunucuları, posta sunucuları, DNS sunucuları ve ters proxy'ler için destek içerir. Şimdi ayrıca Ollama ile entegre yapay zeka geliştirme yetenekleri, MinIO ile nesne depolama, Typesense ve Meilisearch ile güçlü arama ve sağlam bir yedekleme sistemi sunmaktadır. Web geliştirme için ihtiyacınız olan her şey burada. Sadece 3 dakika içinde profesyonel bir yerel geliştirme ortamı kurun.

![ServBay Dashboard](/images/dashboard.png)

## Özellikler

### Çoklu Site Yönetimi

Aynı anda birden fazla web sitesini mi yönetiyorsunuz? ServBay bunu kolaylaştırır. Yerel makinenizde, her biri kendi benzersiz ayarlarına, alan adına ve geliştirme ortamına sahip çok sayıda web sitesini zahmetsizce yapılandırın ve çalıştırın. ServBay'in sezgisel arayüzü süreci basitleştirir, projeler arasında hızla geçiş yapmanıza ve karmaşık kurulum veya çakışmalar olmadan yapılandırmalarını yönetmenize olanak tanır.

![Multi-site Management](/images/website.png)

### Web Sunucuları

ServBay, HTTP/3 ve CORS desteğiyle en popüler web sunucularını—**Caddy, NGINX ve Apache**—içerir. Ayrıca özel alan adlarını ve otomatik SSL yapılandırmasını destekler, alan adı ve SSL sertifikası satın alma ihtiyacını ortadan kaldırarak geliştirme sırasında önemli maliyet tasarrufu sağlar.

![Web Servers](/images/web-servers.png)

### Web Geliştirme Dilleri

ServBay, **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust** ve hatta **.NET** (2.0-10.0) & **Mono** dahil olmak üzere geniş bir geliştirme dili yelpazesiyle birlikte gelir. Geliştiriciler, farklı sürümler arasında sorunsuzca geçiş yapabilir ve farklı projeler için farklı sürümler kullanabilirler. Bu muazzam esneklik, geliştiricilere güçlü bir güven verir.

![Web Development Languages](/images/languages.png)

### Veritabanları

Veritabanları web geliştirme için esastır. ServBay, **MySQL**, **MariaDB** ve giderek popülerleşen **PostgreSQL**'i içerir. NoSQL veritabanları da kapsanmaktadır; **Redis**, **Memcached** ve **MongoDB** kutudan çıktığı gibi kullanıma hazırdır ve yapılandırma gerektirmez. ServBay ayrıca kolay veritabanı yönetimi için **phpMyAdmin** ve **Adminer**'ı entegre eder.

![Databases](/images/databases.png)

### Ollama ile Yapay Zeka Geliştirme

Entegre yapay zeka yetenekleriyle geliştirmenin geleceğini kucaklayın. ServBay, Llama 3, Mistral ve Gemma gibi güçlü Büyük Dil Modellerini (LLM'ler) yerel olarak çalıştırmanıza olanak tanıyan Ollama'yı içerir. Sıfır gecikme ve tam veri gizliliği ile yapay zeka destekli uygulamalar oluşturun ve test edin, hepsi ServBay'in sezgisel arayüzü aracılığıyla yönetilir.

![AI Development with Ollama](/images/ai.png)

### Typesense & Meilisearch ile Güçlü Arama

Uygulamalarınızı modern, hızlı arama motorlarıyla güçlendirin. ServBay, projelerinize tek bir tıklamayla ekleyebileceğiniz önde gelen açık kaynaklı arama çözümlerinden ikisi olan **Typesense** ve **Meilisearch**'ü içerir.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### MinIO ile Nesne Depolama

Artık ServBay ile birlikte gelen yüksek performanslı, S3 uyumlu bir nesne depolama hizmeti olan MinIO'yu kullanarak yapılandırılmamış verileri kolayca yönetin. Yedeklemeler ve günlüklerden medya dosyalarına ve eserlere kadar her şeyi depolamak için mükemmeldir ve yerel geliştirme ihtiyaçlarınız için sağlam bir depolama çözümü sunar.

![Object Storage with MinIO](/images/minio.png)

### Alan Adı ve DNS Hizmetleri

Alan adları, web geliştirme yaşam döngüsünde tüketilebilir bir kaynaktır. ServBay, geliştiricilerin kayıt olmadan var olmayan alan adlarını ve TLD'leri kullanmalarına ve hatta bunlar için SSL sertifikaları düzenlemelerine olanak tanıyan bir DNS sunucusu içerir. Bu, geliştiricilere önemli maliyet tasarrufu sağlamakla kalmaz, aynı zamanda güvenliği de artırır—bilgisayar korsanları var olmayan bir alan adına erişemez. Ayrıca, ServBay, hosts dosyanızı rahatça yönetmeniz için bir grafik arayüz sağlar.

![Domain and DNS Services](/images/dns.png)

### PKI ve SSL Sertifika Yönetimi

ServBay bir PKI sistemi sağlar. Geliştiriciler kendi Sertifika Yetkililerini (CA) oluşturabilir ve SSL sertifikaları düzenleyebilirler—bu, özellikle küçük geliştirme ekipleri için kullanışlıdır. Özel bir CA kullanarak, küçük ekipler veri iletimini şifreleyebilir ve geliştirme ortamlarında dahili güven oluşturabilirler. Bu, yalnızca web hizmetleri için değil, aynı zamanda veritabanları, SMTP ve diğer hizmetler için de geçerlidir. ServBay, e-posta şifrelemesi için S/MIME sertifikalarını, kod imzalama sertifikalarını ve PDF belge imzalama sertifikalarını bile destekler.

Elbette, ServBay ayrıca Let's Encrypt, ZeroSSL ve Google Trust Services'den ACME aracılığıyla SSL sertifikaları almayı ve otomatik olarak yenilemeyi de destekler.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Posta Sunucusu

Yerel geliştirmenizde SMTP/POP3 kullanmak ister misiniz? Sorun değil! ServBay, yerel e-posta testi için **Mailpit** içeren yerleşik bir posta sunucusu içerir. PKI sistemiyle entegre olan posta sunucusu, yapılandırma olmadan STARTTLS ve SSL/TLS'yi destekler. Postayı harici bir SMTP sunucusuna yönlendirmeniz mi gerekiyor? ServBay'in posta sunucusu yönlendirmeyi destekler. Ayrıca, her giden e-postayı puanlamanıza ve spam olarak işaretlenme olasılığını azaltmanıza olanak tanıyan SpamAssassin'i de destekliyoruz.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Ters Proxy

Projenizi geçici olarak kullanıcılarla paylaşmanız mı gerekiyor? Evde bir sunucu barındırmak istiyor ancak genel bir IP adresiniz mi yok? ServBay sizi korur. Web sitenizi hızlı bir şekilde halka açık olarak paylaşmak için **ngrok, frp, Cloudflared ve Pinggy**'yi destekler.

![Reverse Proxy](/images/tunnel.png)

### Proje Düzeyinde Çalışma Zamanı Ortamları

ServBay, proje düzeyinde çalışma zamanı ortamı yapılandırması sunar. Farklı projeler için gerekli PHP ve Node.js sürümlerini yapılandırabilir ve kilitleyebilirsiniz, bu da proje geliştirmenizi daha esnek ve kontrol edilebilir hale getirir.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Güçlü Yedekleme ve Geri Yükleme

Veri güvenliği ve ortam kurtarma çok önemlidir. ServBay, size huzur vermek için kapsamlı bir yedekleme ve geri yükleme sistemine sahiptir.
*   **Tek Tıkla ve Zamanlanmış Yedeklemeler**: Veritabanlarınızın, web sitesi dosyalarınızın, hizmet yapılandırmalarınızın ve SSL sertifikalarınızın otomatik, zamanlanmış yedeklemelerini yapılandırın veya manuel yedeklemeleri tetikleyin.
*   **Kolay Geri Yükleme ve Taşıma**: Bir sorun olması durumunda ortamınızı hızla önceki bir duruma geri yükleyin veya tüm ServBay kurulumunuzu yeni bir makineye kolayca taşımak için yedekleri kullanın.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Birlikte Gelen Paketler

ServBay, geliştirme sürecinizi kolaylaştırmak için çeşitli temel paketlerle birlikte gelir:

-   **Web Sunucuları**: Caddy, Nginx, Apache
-   **Programlama Dilleri**: PHP (5.6 - 8.5-Alpha), Node.js (12 - 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **SQL Veritabanları**: MySQL (5.1 - 9.3), MariaDB (10.4 - 12.0), PostgreSQL (10 - 17)
-   **NoSQL Veritabanları**: Redis, Memcached, MongoDB (5.0 - 8.0) & MongoSH 2
-   **Yapay Zeka / LLM**: Ollama
-   **Arama Motorları**: Typesense, Meilisearch
-   **Nesne Depolama**: MinIO
-   **DNS**: Dahili DNS sunucusu (dnsmasq)
-   **E-posta**: Yerel e-posta testi için Mailpit
-   **Tünel/Ters Proxy**: Cloudflared, frp, Ngrok, Pinggy
-   **Diğer Araçlar**: phpMyAdmin, Adminer, Composer ve daha fazlası

![ServBay Bundled Packages](/images/services.png)

## Kurulum

ServBay hem macOS hem de Windows için mevcuttur.

### macOS

1.  ServBay'in macOS için en son sürümünü [resmi web sitesinden](https://www.servbay.com/download) indirin.
2.  Yükleyiciyi açın ve kurulumu tamamlamak için talimatları izleyin.
3.  ServBay'i başlatın ve yapılandırmak için ilk kurulum sihirbazını izleyin.

### Windows

1.  ServBay'in Windows için en son sürümünü [resmi indirme sayfasından](https://www.servbay.com/download) veya doğrudan [Windows sürüm deposundan](https://github.com/ServBay/ServBay-Windows-Release) indirin.
2.  Yükleyiciyi çalıştırın ve ekrandaki talimatları izleyin.
3.  Yerel geliştirme ortamınızı yapılandırmaya başlamak için ServBay'i başlatın.

## Dokümantasyon

Ayrıntılı dokümantasyon ve kullanım kılavuzları için [ServBay Dokümantasyon Merkezi](https://support.servbay.com)'ni ziyaret edin.

## Destek

ServBay'i kullanırken herhangi bir sorunla karşılaşırsanız, aşağıdaki kanallardan destek alabilirsiniz:

-   [Yardım Merkezi](https://support.servbay.com)
-   [Discord Topluluğu](https://talk.servbay.com)
-   [Telegram Topluluğu](https://telegram.servbay.dev)
-   [WhatsApp Topluluğu](https://wa.servbay.dev)
-   [WeChat Topluluğu](https://wechat-group.servbay.dev)
-   [Sorun Bildir](https://github.com/ServBay/ServBay/issues)

## Topluluk

Diğer geliştiricilerle deneyim alışverişinde bulunmak ve en son güncellemeleri almak için topluluğumuza katılın:

-   [ServBay Blogu](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

ServBay'i kullandığınız için teşekkür ederiz! Herhangi bir sorunuz veya öneriniz varsa, lütfen bizimle iletişime geçmekten çekinmeyin.
