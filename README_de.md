# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Einführung

Verschwenden Sie keine Zeit mehr mit der Verwaltung Ihrer Entwicklungsumgebung!

ServBay ist ein leistungsstarkes und umfassendes Verwaltungstool für lokale Web-Entwicklungsumgebungen, das für professionelle Webentwickler entwickelt wurde und jetzt sowohl für **macOS als auch für Windows** verfügbar ist. ServBay unterstützt eine Vielzahl von Entwicklungssprachen, Datenbanken, Webservern, Mailservern, DNS-Servern und Reverse-Proxys. Es verfügt jetzt auch über integrierte KI-Entwicklungsfähigkeiten mit Ollama, Objektspeicher mit MinIO, leistungsstarke Suche mit Typesense und Meilisearch sowie ein robustes Backup-System. Alles, was Sie für die Webentwicklung benötigen, ist hier. Richten Sie in nur 3 Minuten eine professionelle lokale Entwicklungsumgebung ein.

![ServBay Dashboard](/images/dashboard.png)

## Funktionen

### Verwaltung mehrerer Websites

Verwalten Sie mehrere Websites gleichzeitig? ServBay macht es einfach. Konfigurieren und betreiben Sie mühelos zahlreiche Websites auf Ihrem lokalen Rechner, jede mit ihren eigenen einzigartigen Einstellungen, Domain und Entwicklungsumgebung. Die intuitive Benutzeroberfläche von ServBay vereinfacht den Prozess und ermöglicht es Ihnen, schnell zwischen Projekten zu wechseln und deren Konfigurationen ohne komplexe Einrichtung oder Konflikte zu verwalten.

![Multi-site Management](/images/website.png)

### Webserver

ServBay enthält die beliebtesten Webserver – **Caddy, NGINX und Apache** – mit Unterstützung für HTTP/3 und CORS. Es unterstützt auch benutzerdefinierte Domains und die automatisierte SSL-Konfiguration, wodurch der Kauf von Domains und SSL-Zertifikaten entfällt und erhebliche Kosten während der Entwicklung eingespart werden.

![Web Servers](/images/web-servers.png)

### Web-Entwicklungssprachen

ServBay wird mit einer Vielzahl von Entwicklungssprachen geliefert, darunter **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust** und sogar **.NET** (2.0-10.0) & **Mono**. Entwickler können nahtlos zwischen verschiedenen Versionen wechseln und unterschiedliche Versionen für verschiedene Projekte verwenden. Diese immense Flexibilität gibt Entwicklern großes Vertrauen.

![Web Development Languages](/images/languages.png)

### Datenbanken

Datenbanken sind für die Webentwicklung unerlässlich. ServBay enthält **MySQL**, **MariaDB** und das immer beliebter werdende **PostgreSQL**. NoSQL-Datenbanken sind ebenfalls abgedeckt, mit **Redis**, **Memcached** und **MongoDB**, die sofort einsatzbereit sind und keine Konfiguration erfordern. ServBay integriert auch **phpMyAdmin** und **Adminer** zur einfachen Datenbankverwaltung.

![Databases](/images/databases.png)

### KI-Entwicklung mit Ollama

Begrüßen Sie die Zukunft der Entwicklung mit integrierten KI-Fähigkeiten. ServBay integriert Ollama, sodass Sie leistungsstarke Große Sprachmodelle (LLMs) wie Llama 3, Mistral und Gemma lokal ausführen können. Erstellen und testen Sie KI-gesteuerte Anwendungen mit null Latenz und vollständiger Datensicherheit, alles verwaltet über die intuitive Benutzeroberfläche von ServBay.

![AI Development with Ollama](/images/ai.png)

### Leistungsstarke Suche mit Typesense & Meilisearch

Statten Sie Ihre Anwendungen mit modernen, schnellen Suchmaschinen aus. ServBay enthält sowohl **Typesense** als auch **Meilisearch**, zwei der führenden Open-Source-Suchlösungen, die Sie mit einem Klick zu Ihren Projekten hinzufügen können.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Objektspeicher mit MinIO

Verwalten Sie unstrukturierte Daten mühelos mit MinIO, einem leistungsstarken, S3-kompatiblen Objektspeicherdienst, der jetzt in ServBay enthalten ist. Er eignet sich perfekt zum Speichern von Backups, Protokollen, Mediendateien und Artefakten und bietet eine robuste Speicherlösung für Ihre lokalen Entwicklungsanforderungen.

![Object Storage with MinIO](/images/minio.png)

### Domain- und DNS-Dienste

Domains sind eine Verbrauchsressource im Lebenszyklus der Webentwicklung. ServBay enthält einen DNS-Server, der es Entwicklern ermöglicht, nicht existierende Domains und TLDs ohne Registrierung zu verwenden und sogar SSL-Zertifikate für sie auszustellen. Dies spart Entwicklern nicht nur erhebliche Kosten, sondern erhöht auch die Sicherheit – Hacker können nicht auf eine nicht existierende Domain zugreifen. Darüber hinaus bietet ServBay eine grafische Oberfläche zur bequemen Verwaltung Ihrer Hosts-Datei.

![Domain and DNS Services](/images/dns.png)

### PKI- und SSL-Zertifikatsverwaltung

ServBay bietet ein PKI-System. Entwickler können ihre eigene Zertifizierungsstelle (CA) erstellen und SSL-Zertifikate ausstellen – besonders nützlich für kleine Entwicklungsteams. Mit einer privaten CA können kleine Teams die Datenübertragung verschlüsseln und internes Vertrauen in ihrer Entwicklungsumgebung aufbauen. Dies gilt nicht nur für Webdienste, sondern auch für Datenbanken, SMTP und andere Dienste. ServBay unterstützt sogar S/MIME-Zertifikate für die E-Mail-Verschlüsselung, Code-Signing-Zertifikate und PDF-Dokumenten-Signaturzertifikate.

Natürlich unterstützt ServBay auch das Abrufen und automatische Erneuern von SSL-Zertifikaten von Let's Encrypt, ZeroSSL und Google Trust Services über ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Mailserver

Möchten Sie SMTP/POP3 in Ihrer lokalen Entwicklung verwenden? Kein Problem! ServBay enthält einen integrierten Mailserver mit **Mailpit** für lokale E-Mail-Tests. Integriert in das PKI-System unterstützt der Mailserver STARTTLS und SSL/TLS ohne Konfiguration. Müssen Sie E-Mails an einen externen SMTP-Server weiterleiten? Der Mailserver von ServBay unterstützt die Weiterleitung. Wir unterstützen auch SpamAssassin, mit dem Sie jede ausgehende E-Mail bewerten und die Wahrscheinlichkeit verringern können, dass sie als Spam markiert wird.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Reverse Proxy

Müssen Sie Ihr Projekt vorübergehend mit Benutzern teilen? Möchten Sie einen Server zu Hause hosten, haben aber keine öffentliche IP-Adresse? ServBay hat die Lösung. Es unterstützt **ngrok, frp, Cloudflared und Pinggy**, um Ihre Website schnell öffentlich zu teilen.

![Reverse Proxy](/images/tunnel.png)

### Projektbezogene Laufzeitumgebungen

ServBay bietet eine projektbezogene Konfiguration der Laufzeitumgebung. Sie können die erforderlichen PHP- und Node.js-Versionen für verschiedene Projekte konfigurieren und sperren, was Ihre Projektentwicklung flexibler und kontrollierbarer macht.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Leistungsstarke Sicherung & Wiederherstellung

Datensicherheit und Wiederherstellung der Umgebung sind entscheidend. ServBay verfügt über ein umfassendes Sicherungs- und Wiederherstellungssystem, das Ihnen Sicherheit gibt.
*   **Ein-Klick- & geplante Backups**: Konfigurieren Sie automatische, geplante Backups oder lösen Sie manuelle Backups Ihrer Datenbanken, Website-Dateien, Dienstkonfigurationen und SSL-Zertifikate aus.
*   **Einfache Wiederherstellung & Migration**: Stellen Sie Ihre Umgebung im Falle eines Problems schnell in einen früheren Zustand wieder her oder verwenden Sie die Backups, um Ihre gesamte ServBay-Einrichtung einfach auf einen neuen Rechner zu migrieren.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Mitgelieferte Pakete

ServBay wird mit einer Vielzahl wichtiger Pakete geliefert, um Ihren Entwicklungsprozess zu optimieren:

-   **Webserver**: Caddy, Nginx, Apache
-   **Programmiersprachen**: PHP (5.6 bis 8.5-Alpha), Node.js (12 bis 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **SQL-Datenbanken**: MySQL (5.1 bis 9.3), MariaDB (10.4 bis 12.0), PostgreSQL (10 bis 17)
-   **NoSQL-Datenbanken**: Redis, Memcached, MongoDB (5.0 bis 8.0) & MongoSH 2
-   **KI / LLM**: Ollama
-   **Suchmaschinen**: Typesense, Meilisearch
-   **Objektspeicher**: MinIO
-   **DNS**: Integrierter DNS-Server (dnsmasq)
-   **E-Mail**: Mailpit für lokale E-Mail-Tests
-   **Tunnel/Reverse Proxy**: Cloudflared, frp, Ngrok, Pinggy
-   **Andere Werkzeuge**: phpMyAdmin, Adminer, Composer und mehr

![ServBay Bundled Packages](/images/services.png)

## Installation

ServBay ist sowohl für macOS als auch für Windows verfügbar.

### macOS

1.  Laden Sie die neueste Version von ServBay für macOS von der [offiziellen Website](https://www.servbay.com/download) herunter.
2.  Öffnen Sie das Installationsprogramm und folgen Sie den Anweisungen, um die Installation abzuschließen.
3.  Starten Sie ServBay und folgen Sie dem Ersteinrichtungsassistenten, um es zu konfigurieren.

### Windows

1.  Laden Sie die neueste Version von ServBay für Windows von der [offiziellen Download-Seite](https://www.servbay.com/download) oder direkt aus dem [Windows-Release-Repository](https://github.com/ServBay/ServBay-Windows-Release) herunter.
2.  Führen Sie das Installationsprogramm aus und folgen Sie den Anweisungen auf dem Bildschirm.
3.  Starten Sie ServBay, um mit der Konfiguration Ihrer lokalen Entwicklungsumgebung zu beginnen.

## Dokumentation

Für detaillierte Dokumentation und Nutzungsanleitungen besuchen Sie das [ServBay Dokumentationszentrum](https://support.servbay.com).

## Support

Wenn Sie bei der Verwendung von ServBay auf Probleme stoßen, können Sie über die folgenden Kanäle Unterstützung erhalten:

-   [Hilfezentrum](https://support.servbay.com)
-   [Discord-Community](https://talk.servbay.com)
-   [Telegram-Community](https://telegram.servbay.dev)
-   [WhatsApp-Community](https://wa.servbay.dev)
-   [WeChat-Community](https://wechat-group.servbay.dev)
-   [Ein Problem melden](https://github.com/ServBay/ServBay/issues)

## Community

Treten Sie unserer Community bei, um Erfahrungen mit anderen Entwicklern auszutauschen und die neuesten Updates zu erhalten:

-   [ServBay-Blog](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Vielen Dank, dass Sie ServBay verwenden! Wenn Sie Fragen oder Anregungen haben, zögern Sie bitte nicht, uns zu kontaktieren.