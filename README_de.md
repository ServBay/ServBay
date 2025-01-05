# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Einleitung

Verschwenden Sie keine Zeit mehr mit der Verwaltung Ihrer Entwicklungsumgebung!

ServBay ist ein leistungsstarkes und umfassendes [lokales Webentwicklungs-Umgebungsverwaltungstool](https://www.servbay.com), das für professionelle Webentwickler entwickelt wurde. ServBay bietet Unterstützung für eine Vielzahl von Entwicklungssprachen, Datenbanken, Webservern, Mailservern, DNS-Servern, Objektspeicher, Reverse-Proxys und sogar eine professionelle SSL-Zertifikatsverwaltungsplattform. Alles, was Sie für die Webentwicklung benötigen, ist hier. Richten Sie in nur 3 Minuten eine professionelle lokale Entwicklungsumgebung ein.

![ServBay Dashboard](/images/dashboard.png)

## Funktionen

### Multi-Site-Verwaltung

[Verwalten Sie mehrere Websites](https://support.servbay.com/basic-usage/websites/adding-first-website) gleichzeitig? ServBay macht es Ihnen leicht.  Konfigurieren und betreiben Sie mühelos zahlreiche Websites auf Ihrem lokalen Rechner, jede mit ihren eigenen einzigartigen Einstellungen, Domain und Entwicklungsumgebung. Die intuitive Benutzeroberfläche von ServBay vereinfacht den Prozess und ermöglicht Ihnen, schnell zwischen Projekten zu wechseln und deren Konfigurationen ohne komplexe Einrichtung oder Konflikte zu verwalten.

![Multi-Site-Verwaltung](/images/hosts.png)

### Webserver

ServBay enthält die beliebtesten [Webserver](https://www.servbay.com/features/web-server), Caddy und NGINX, mit Unterstützung für HTTP/3 und CORS.  Es unterstützt auch benutzerdefinierte Domains und die [automatische SSL-Konfiguration](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), wodurch die Notwendigkeit entfällt, Domains und SSL-Zertifikate zu kaufen, was erhebliche Kosten während der Entwicklung spart.

![Webserver](/images/web-servers.png)

### Webentwicklungssprachen

ServBay wird mit [Node.js](https://www.servbay.com/features/nodejs) (Versionen 12-23) und [PHP](https://www.servbay.com/features/php) (Versionen 5.6-8.5) geliefert und deckt die Bedürfnisse von Entwicklern während des gesamten Webentwicklungslebenszyklus ab. Entwickler können nahtlos zwischen verschiedenen Versionen wechseln und verschiedene Versionen für verschiedene Projekte verwenden. Diese immense Flexibilität gibt Entwicklern starkes Vertrauen.  ServBay enthält auch Python und Golang.

![Webentwicklungssprachen](/images/languages.png)

### Datenbanken

[Datenbanken](https://www.servbay.com/features/database) sind für die Webentwicklung unerlässlich. ServBay enthält [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) und das immer beliebter werdende [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage).  NoSQL-Datenbanken werden ebenfalls abgedeckt, mit [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) und [MongoDB](https://www.servbay.com/features/database) sofort einsatzbereit, ohne dass eine Konfiguration erforderlich ist.  ServBay integriert auch [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) und [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) für eine einfache Datenbankverwaltung.

![Datenbanken](/images/databases.png)

### Domain- und DNS-Dienste

[Domains](https://www.servbay.com/features/dns-server) sind eine verbrauchsintensive Ressource im Webentwicklungslebenszyklus. ServBay enthält einen [DNS-Server](https://www.servbay.com/features/dns-server), der es Entwicklern ermöglicht, nicht vorhandene Domains und TLDs ohne Registrierung zu verwenden und sogar SSL-Zertifikate für sie auszustellen. Dies spart Entwicklern nicht nur erhebliche Kosten, sondern erhöht auch die Sicherheit – Hacker können nicht auf eine nicht vorhandene Domain zugreifen. Darüber hinaus bietet ServBay eine grafische Oberfläche zur bequemen Verwaltung Ihrer /etc/hosts-Datei.

![Domain- und DNS-Dienste](/images/dns.png)

### PKI- und SSL-Zertifikatsverwaltung

ServBay bietet ein [PKI-System](https://www.servbay.com/features/ssl). Entwickler können ihre eigene Zertifizierungsstelle (CA) erstellen und SSL-Zertifikate ausstellen – besonders nützlich für kleine Entwicklungsteams.  Die Verwendung einer [privaten CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management) ermöglicht es kleinen Teams, die Datenübertragung zu verschlüsseln und internes Vertrauen innerhalb ihrer Entwicklungsumgebung aufzubauen. Dies gilt nicht nur für Webdienste, sondern auch für Datenbanken, SMTP und andere Dienste. ServBay unterstützt sogar [S/MIME-Zertifikate](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) für die E-Mail-Verschlüsselung, [Code-Signaturzertifikate](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) und [PDF-Dokumentensignaturzertifikate](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Natürlich unterstützt ServBay auch das Abrufen und automatische Erneuern von SSL-Zertifikaten von Let's Encrypt, ZeroSSL und Google Trust Services über [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).


![PKI- und SSL-Zertifikatsverwaltung](/images/ssl-pki.png)

### Mailserver

Möchten Sie SMTP/POP3 in Ihrer lokalen Entwicklung verwenden? Kein Problem! ServBay enthält einen [integrierten Mailserver](https://www.servbay.com/features/email-server).  Integriert mit dem PKI-System, unterstützt der Mailserver [STARTTLS und SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) ohne Konfiguration.  Müssen Sie E-Mails an einen externen [SMTP-Server](https://www.servbay.com/features/email-server) weiterleiten?  Der Mailserver von ServBay unterstützt die Weiterleitung.  Wir unterstützen auch SpamAssassin, wodurch Sie jede ausgehende E-Mail bewerten und die Wahrscheinlichkeit reduzieren können, dass sie als Spam markiert wird.

![Mailserver](/images/email-server.png)

![Mailserver Webmail](/images/email-server-webmail.png)

### Reverse-Proxy

Müssen Sie Ihr Projekt vorübergehend mit Benutzern teilen? Möchten Sie einen Server zu Hause hosten, haben aber keine öffentliche IP-Adresse? ServBay bietet Ihnen die Lösung.  Es unterstützt [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp und Cloudflared, um Ihre Website schnell öffentlich freizugeben.  Vertrauen Sie keinen Drittanbieterdiensten? ServBay bietet auch einen öffentlichen Reverse-Proxy-Dienst, der nahtlos für die Freigabe mit einem Klick integriert ist.

*(In Kürze verfügbar)*


### Projektbezogene Laufzeitumgebungen

ServBay bietet eine projektbezogene Konfiguration der Laufzeitumgebung. Sie können die erforderlichen PHP- und Node.js-Versionen für verschiedene Projekte konfigurieren und sperren, wodurch Ihre Projektentwicklung flexibler und kontrollierbarer wird.

![Projektbezogene Laufzeitumgebungen](/images/project-level-runtime.png)

### Sauber und einfach zu sichern

ServBay ist eine portable Installation, die im Gegensatz zu Tools wie Homebrew, die Ihre Systemdateien überladen können, keine Rückstände auf Ihrem System hinterlässt.  Sie können Ihre Daten ganz einfach mit Time Machine oder rsync sichern und so die Datensicherheit gewährleisten.

![Sauber und einfach zu sichern](/images/easy-to-backup.png)

## Enthaltene Pakete

ServBay wird mit einer Vielzahl wichtiger Pakete geliefert, um Ihren Entwicklungsprozess zu optimieren:

- **Webserver**: Caddy (2.8), Nginx (1.27) und Apache *(2.4, in Kürze verfügbar)*
- **Programmiersprachen**: PHP (von PHP 5.6 bis PHP 8.5-Dev), Node.js (von Node.js 12 bis Node.js 23), Python *(in Kürze verfügbar)*, Golang *(in Kürze verfügbar)*
- **SQL-Datenbanken**: MySQL (von MySQL 5.1 bis MySQL 9.1), MariaDB (von MariaDB 10.4 bis MariaDB 11.8), PostgreSQL (von PostgreSQL 10 bis PostgreSQL 17)
- **NoSQL-Datenbanken**: Redis (7.2), Memcached (1.6), MongoDB (von MongoDB 5.0 bis MongoDB 8.0) & MongoSH 2
- **DNS**: Eingebauter DNS-Server für die lokale Entwicklung (dnsmasq 2.9)
- **E-Mail**: Mailpit für lokale E-Mail-Tests
- **Tunnel/Reverse-Proxy**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Weitere Tools**: phpMyAdmin, Adminer und mehr

![ServBay Enthaltene Pakete](/images/services.png)


## Installation

Führen Sie die folgenden Schritte aus, um ServBay zu installieren:

1. Laden Sie die neueste Version von ServBay von der [offiziellen Website](https://www.servbay.com) herunter.
2. Öffnen Sie das Installationsprogramm und folgen Sie den Anweisungen, um die Installation abzuschließen.
3. Starten Sie ServBay und folgen Sie dem Assistenten für die Erstkonfiguration.


## Dokumentation

Detaillierte Dokumentation und Benutzerhandbücher finden Sie im [ServBay Dokumentationszentrum](https://support.servbay.com).

## Support

Wenn Sie bei der Verwendung von ServBay auf Probleme stoßen, können Sie über die folgenden Kanäle Support erhalten:

- [Hilfe-Center](https://support.servbay.com)
- [Discord-Community](https://talk.servbay.com)
- [Telegram-Community](https://telegram.servbay.dev)
- [WhatsApp-Community](https://wa.servbay.dev)
- [WeChat-Community](https://wechat-group.servbay.dev)
- [Ein Problem melden](https://github.com/ServBay/ServBay/issues)

## Community

Treten Sie unserer Community bei, um Erfahrungen mit anderen Entwicklern auszutauschen und die neuesten Updates zu erhalten:

- [ServBay Blog](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Vielen Dank, dass Sie ServBay verwenden! Wenn Sie Fragen oder Anregungen haben, können Sie sich gerne an uns wenden.
