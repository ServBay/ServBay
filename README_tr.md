# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logosu](/images/logo.png)

## Giriş

Geliştirme ortamınızı yönetmek için zaman kaybetmeyi bırakın!

ServBay, profesyonel web geliştiricileri için tasarlanmış güçlü ve kapsamlı bir [yerel web geliştirme ortamı yönetim aracıdır](https://www.servbay.com). ServBay, çeşitli geliştirme dilleri, veritabanları, web sunucuları, posta sunucuları, DNS sunucuları, nesne depolama, ters proxy'ler ve hatta profesyonel bir SSL sertifikası yönetim platformu için destek içerir. Web geliştirme için ihtiyacınız olan her şey burada. Sadece 3 dakikada profesyonel bir yerel geliştirme ortamı kurun.

![ServBay Gösterge Paneli](/images/dashboard.png)

## Özellikler

### Çoklu Site Yönetimi

[Aynı anda birden fazla web sitesini mi yönetiyorsunuz?](https://support.servbay.com/basic-usage/websites/adding-first-website) ServBay bunu kolaylaştırır. Yerel makinenizde, her biri kendi benzersiz ayarlarına, alan adına ve geliştirme ortamına sahip çok sayıda web sitesini zahmetsizce yapılandırın ve çalıştırın. ServBay'in sezgisel arayüzü, karmaşık kurulum veya çakışmalar olmadan projeler arasında hızlıca geçiş yapmanıza ve yapılandırmalarını yönetmenize olanak tanıyarak süreci basitleştirir.

![Çoklu Site Yönetimi](/images/hosts.png)

### Web Sunucuları

ServBay, HTTP/3 ve CORS desteğiyle en popüler [web sunucularını](https://www.servbay.com/features/web-server), Caddy ve NGINX'i içerir. Ayrıca, özel alan adlarını ve [otomatik SSL yapılandırmasını](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website) destekler, bu da alan adları ve SSL sertifikaları satın alma ihtiyacını ortadan kaldırarak geliştirme sırasında önemli maliyet tasarrufu sağlar.

![Web Sunucuları](/images/web-servers.png)

### Web Geliştirme Dilleri

ServBay, web geliştirme yaşam döngüsü boyunca geliştiricilerin ihtiyaçlarını karşılayan [Node.js](https://www.servbay.com/features/nodejs) (12-23 sürümleri) ve [PHP](https://www.servbay.com/features/php) (5.6-8.5 sürümleri) ile birlikte gelir. Geliştiriciler, farklı sürümler arasında sorunsuz bir şekilde geçiş yapabilir ve farklı projeler için farklı sürümler kullanabilir. Bu muazzam esneklik, geliştiricilere güçlü bir güven verir. ServBay ayrıca Python ve Golang'ı da içerir.

![Web Geliştirme Dilleri](/images/languages.png)

### Veritabanları

[Veritabanları](https://www.servbay.com/features/database), web geliştirme için olmazsa olmazdır. ServBay, [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) ve giderek daha popüler hale gelen [PostgreSQL'i](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage) içerir. NoSQL veritabanları da kapsanmaktadır, [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) ve [MongoDB](https://www.servbay.com/features/database) kullanıma hazırdır, herhangi bir yapılandırma gerektirmez. ServBay ayrıca, kolay veritabanı yönetimi için [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) ve [Adminer'ı](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) da entegre eder.

![Veritabanları](/images/databases.png)

### Alan Adı ve DNS Hizmetleri

[Alan adları](https://www.servbay.com/features/dns-server), web geliştirme yaşam döngüsünde tüketilebilir bir kaynaktır. ServBay, geliştiricilerin kayıt olmadan mevcut olmayan alan adlarını ve TLD'leri kullanmalarına ve hatta onlar için SSL sertifikaları yayınlamalarına olanak tanıyan bir [DNS sunucusu](https://www.servbay.com/features/dns-server) içerir. Bu, geliştiricilere önemli ölçüde maliyet tasarrufu sağlamakla kalmaz, aynı zamanda güvenliği de artırır - bilgisayar korsanları mevcut olmayan bir alan adına erişemez. Ek olarak, ServBay, /etc/hosts dosyanızı kolayca yönetmek için grafiksel bir arayüz sağlar.

![Alan Adı ve DNS Hizmetleri](/images/dns.png)

### PKI ve SSL Sertifikası Yönetimi

ServBay bir [PKI sistemi](https://www.servbay.com/features/ssl) sağlar. Geliştiriciler kendi Sertifika Yetkililerini (CA) oluşturabilir ve SSL sertifikaları yayınlayabilirler - bu özellikle küçük geliştirme ekipleri için kullanışlıdır. [Özel bir CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management) kullanarak, küçük ekipler veri iletimini şifreleyebilir ve geliştirme ortamlarında dahili güven oluşturabilir. Bu sadece web hizmetleri için değil, aynı zamanda veritabanları, SMTP ve diğer hizmetler için de geçerlidir. ServBay, e-posta şifreleme için [S/MIME sertifikalarını](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate), [kod imzalama sertifikalarını](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) ve [PDF belge imzalama sertifikalarını](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate) bile destekler.

Elbette ServBay, [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate) aracılığıyla Let's Encrypt, ZeroSSL ve Google Trust Services'den SSL sertifikaları almayı ve otomatik olarak yenilemeyi de destekler.

![PKI ve SSL Sertifikası Yönetimi](/images/ssl-pki.png)

### Posta Sunucusu

Yerel geliştirmenizde SMTP/POP3 kullanmak mı istiyorsunuz? Sorun değil! ServBay [yerleşik bir posta sunucusu](https://www.servbay.com/features/email-server) içerir. PKI sistemiyle entegre olan posta sunucusu, yapılandırma olmadan [STARTTLS ve SSL/TLS'yi](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) destekler. Postayı harici bir [SMTP sunucusuna](https://www.servbay.com/features/email-server) iletmeniz mi gerekiyor? ServBay'in posta sunucusu iletmeyi destekler. Ayrıca, her giden e-postayı puanlamanıza ve spam olarak işaretlenme olasılığını azaltmanıza olanak tanıyan SpamAssassin'i de destekliyoruz.

![Posta Sunucusu](/images/email-server.png)

![Posta Sunucusu Web Postası](/images/email-server-webmail.png)

### Ters Proxy

Projenizi geçici olarak kullanıcılarla paylaşmanız mı gerekiyor? Evde bir sunucu barındırmak istiyorsunuz ancak genel bir IP adresiniz yok mu? ServBay sizi korur. Web sitenizi hızlı bir şekilde herkese açık olarak paylaşmak için [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp ve Cloudflared'ı destekler. Üçüncü taraf hizmetlere güvenmiyor musunuz? ServBay ayrıca, tek tıkla paylaşım için sorunsuz bir şekilde entegre edilmiş genel bir ters proxy hizmeti de sağlar.

*(Yakında)*

### Proje Düzeyinde Çalışma Zamanı Ortamları

ServBay, proje düzeyinde çalışma zamanı ortamı yapılandırması sunar. Farklı projeler için gerekli PHP ve Node.js sürümlerini yapılandırabilir ve kilitleyebilir, böylece proje geliştirmenizi daha esnek ve kontrol edilebilir hale getirebilirsiniz.

![Proje Düzeyinde Çalışma Zamanı Ortamları](/images/project-level-runtime.png)

### Temiz ve Yedeklenmesi Kolay

ServBay, sistem dosyalarınızı karıştırabilen Homebrew gibi araçların aksine, sisteminizde kalıntı bırakmayan taşınabilir bir kurulumdur. Verilerinizi Time Machine veya rsync kullanarak kolayca yedekleyebilir, böylece veri güvenliğini sağlayabilirsiniz.

![Temiz ve Yedeklenmesi Kolay](/images/easy-to-backup.png)

## Birlikte Verilen Paketler

ServBay, geliştirme sürecinizi kolaylaştırmak için çeşitli temel paketlerle birlikte gelir:

- **Web Sunucuları**: Caddy (2.8), Nginx (1.27) ve Apache *(2.4, yakında)*
- **Programlama Dilleri**: PHP (PHP 5.6'dan PHP 8.5-Dev'e kadar), Node.js (Node.js 12'den Node.js 23'e kadar), Python *(yakında)*, Golang *(yakında)*
- **SQL Veritabanları**: MySQL (MySQL 5.1'den MySQL 9.1'e kadar), MariaDB (MariaDB 10.4'ten MariaDB 11.8'e kadar), PostgreSQL (PostgreSQL 10'dan PostgreSQL 17'ye kadar)
- **NoSQL Veritabanları**: Redis (7.2), Memcached (1.6), MongoDB (MongoDB 5.0'dan MongoDB 8.0'a kadar) ve MongoSH 2
- **DNS**: Yerel geliştirme için yerleşik DNS sunucusu (dnsmasq 2.9)
- **E-posta**: Yerel e-posta testi için Mailpit
- **Tünel/Ters Proxy**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Diğer Araçlar**: phpMyAdmin, Adminer ve daha fazlası

![ServBay Birlikte Verilen Paketler](/images/services.png)

## Kurulum

ServBay'i kurmak için şu adımları izleyin:

1. ServBay'in en son sürümünü [resmi web sitesinden](https://www.servbay.com) indirin.
2. Yükleyiciyi açın ve kurulumu tamamlamak için istemleri izleyin.
3. ServBay'i başlatın ve yapılandırmak için ilk kurulum sihirbazını izleyin.

## Belgeler

Ayrıntılı belgeler ve kullanım kılavuzları için [ServBay Dokümantasyon Merkezini](https://support.servbay.com) ziyaret edin.

## Destek

ServBay'i kullanırken herhangi bir sorunla karşılaşırsanız, aşağıdaki kanallar aracılığıyla destek alabilirsiniz:

- [Yardım Merkezi](https://support.servbay.com)
- [Discord Topluluğu](https://talk.servbay.com)
- [Telegram Topluluğu](https://telegram.servbay.dev)
- [WhatsApp Topluluğu](https://wa.servbay.dev)
- [WeChat Topluluğu](https://wechat-group.servbay.dev)
- [Bir Sorun Bildirin](https://github.com/ServBay/ServBay/issues)


## Topluluk

Diğer geliştiricilerle deneyim alışverişinde bulunmak ve en son güncellemeleri almak için topluluğumuza katılın:

- [ServBay Blogu](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

ServBay'i kullandığınız için teşekkür ederiz! Herhangi bir sorunuz veya öneriniz varsa, lütfen bizimle iletişime geçmekten çekinmeyin.
