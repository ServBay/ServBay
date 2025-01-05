# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Logo ServBay](/images/logo.png)

## Introduzione

Smettila di perdere tempo a gestire il tuo ambiente di sviluppo!

ServBay è un potente e completo [strumento di gestione dell'ambiente di sviluppo web locale](https://www.servbay.com) progettato per sviluppatori web professionisti. ServBay include il supporto per una varietà di linguaggi di sviluppo, database, server web, server di posta, server DNS, object storage, reverse proxy e persino una piattaforma professionale per la gestione dei certificati SSL. Tutto ciò di cui hai bisogno per lo sviluppo web è qui. Ottieni un ambiente di sviluppo locale professionale configurato in soli 3 minuti.

![Dashboard ServBay](/images/dashboard.png)

## Caratteristiche

### Gestione Multi-sito

[Gestisci più siti web](https://support.servbay.com/basic-usage/websites/adding-first-website) contemporaneamente? ServBay lo rende facile. Configura ed esegui senza sforzo numerosi siti web sul tuo computer locale, ognuno con le proprie impostazioni, dominio e ambiente di sviluppo unici. L'interfaccia intuitiva di ServBay semplifica il processo, consentendoti di passare rapidamente da un progetto all'altro e di gestirne le configurazioni senza configurazioni complesse o conflitti.

![Gestione Multi-sito](/images/hosts.png)

### Server Web

ServBay include i [server web](https://www.servbay.com/features/web-server) più popolari, Caddy e NGINX, con supporto per HTTP/3 e CORS. Supporta anche domini personalizzati e [configurazione SSL automatizzata](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), eliminando la necessità di acquistare domini e certificati SSL, con un notevole risparmio sui costi durante lo sviluppo.

![Server Web](/images/web-servers.png)

### Linguaggi di Sviluppo Web

ServBay viene fornito con [Node.js](https://www.servbay.com/features/nodejs) (versioni 12-23) e [PHP](https://www.servbay.com/features/php) (versioni 5.6-8.5), coprendo le esigenze degli sviluppatori durante tutto il ciclo di vita dello sviluppo web. Gli sviluppatori possono passare facilmente da una versione all'altra e utilizzare versioni diverse per progetti diversi. Questa immensa flessibilità offre agli sviluppatori una forte fiducia. ServBay include anche Python e Golang.

![Linguaggi di Sviluppo Web](/images/languages.png)

### Database

I [database](https://www.servbay.com/features/database) sono essenziali per lo sviluppo web. ServBay include [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) e il sempre più popolare [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage). Sono coperti anche i database NoSQL, con [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) e [MongoDB](https://www.servbay.com/features/database) pronti all'uso, senza bisogno di configurazione. ServBay integra anche [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) e [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) per una facile gestione del database.

![Database](/images/databases.png)

### Servizi di Dominio e DNS

I [domini](https://www.servbay.com/features/dns-server) sono una risorsa consumabile nel ciclo di vita dello sviluppo web. ServBay include un [server DNS](https://www.servbay.com/features/dns-server), che consente agli sviluppatori di utilizzare domini e TLD inesistenti senza registrazione e persino di emettere certificati SSL per essi. Ciò non solo consente agli sviluppatori di risparmiare costi significativi, ma migliora anche la sicurezza: gli hacker non possono accedere a un dominio inesistente. Inoltre, ServBay fornisce un'interfaccia grafica per gestire comodamente il tuo file /etc/hosts.

![Servizi di Dominio e DNS](/images/dns.png)

### Gestione dei Certificati PKI e SSL

ServBay fornisce un [sistema PKI](https://www.servbay.com/features/ssl). Gli sviluppatori possono creare la propria autorità di certificazione (CA) ed emettere certificati SSL, particolarmente utile per piccoli team di sviluppo. Utilizzando una [CA privata](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management), i piccoli team possono crittografare la trasmissione dei dati e stabilire la fiducia interna all'interno del loro ambiente di sviluppo. Questo vale non solo per i servizi web, ma anche per database, SMTP e altri servizi. ServBay supporta persino i [certificati S/MIME](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) per la crittografia della posta elettronica, i [certificati di firma del codice](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) e i [certificati di firma dei documenti PDF](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Ovviamente, ServBay supporta anche l'ottenimento e il rinnovo automatico dei certificati SSL da Let's Encrypt, ZeroSSL e Google Trust Services tramite [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Gestione dei Certificati PKI e SSL](/images/ssl-pki.png)

### Server di Posta

Vuoi utilizzare SMTP/POP3 nel tuo sviluppo locale? Nessun problema! ServBay include un [server di posta integrato](https://www.servbay.com/features/email-server). Integrato con il sistema PKI, il server di posta supporta [STARTTLS e SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) senza configurazione.  Hai bisogno di inoltrare la posta a un [server SMTP](https://www.servbay.com/features/email-server) esterno? Il server di posta di ServBay supporta l'inoltro. Supportiamo anche SpamAssassin, che ti consente di assegnare un punteggio a ciascuna email in uscita e ridurre le possibilità che venga contrassegnata come spam.

![Server di Posta](/images/email-server.png)

![Webmail del Server di Posta](/images/email-server-webmail.png)

### Reverse Proxy

Devi condividere temporaneamente il tuo progetto con gli utenti? Vuoi ospitare un server a casa ma non hai un indirizzo IP pubblico? ServBay ti copre. Supporta [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp e Cloudflared per condividere rapidamente il tuo sito web pubblicamente. Non ti fidi dei servizi di terze parti? ServBay fornisce anche un servizio di reverse proxy pubblico, perfettamente integrato per la condivisione con un clic.

*(Prossimamente)*


### Ambienti di Runtime a Livello di Progetto

ServBay offre la configurazione dell'ambiente di runtime a livello di progetto. È possibile configurare e bloccare le versioni richieste di PHP e Node.js per diversi progetti, rendendo lo sviluppo del progetto più flessibile e controllabile.

![Ambienti di Runtime a Livello di Progetto](/images/project-level-runtime.png)

### Pulito e Facile da Eseguire il Backup

ServBay è un'installazione portatile, che non lascia residui sul tuo sistema, a differenza di strumenti come Homebrew che possono ingombrare i file di sistema. Puoi eseguire facilmente il backup dei tuoi dati utilizzando Time Machine o rsync, garantendo la sicurezza dei dati.

![Pulito e Facile da Eseguire il Backup](/images/easy-to-backup.png)

## Pacchetti Inclusi

ServBay viene fornito con una varietà di pacchetti essenziali per semplificare il processo di sviluppo:

- **Server Web**: Caddy (2.8), Nginx (1.27) e Apache *(2.4, prossimamente)*
- **Linguaggi di Programmazione**: PHP (da PHP 5.6 a PHP 8.5-Dev), Node.js (da Node.js 12 a Node.js 23), Python *(prossimamente)*, Golang *(prossimamente)*
- **Database SQL**: MySQL (da MySQL 5.1 a MySQL 9.1), MariaDB (da MariaDB 10.4 a MariaDB 11.8), PostgreSQL (da PostgreSQL 10 a PostgreSQL 17)
- **Database NoSQL**: Redis (7.2), Memcached (1.6), MongoDB (da MongoDB 5.0 a MongoDB 8.0) e MongoSH 2
- **DNS**: Server DNS integrato per lo sviluppo locale (dnsmasq 2.9)
- **Email**: Mailpit per i test di posta elettronica locali
- **Tunnel/Reverse Proxy**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Altri Strumenti**: phpMyAdmin, Adminer e altro ancora

![Pacchetti Inclusi in ServBay](/images/services.png)

## Installazione

Segui questi passaggi per installare ServBay:

1. Scarica l'ultima versione di ServBay dal [sito web ufficiale](https://www.servbay.com).
2. Apri il programma di installazione e segui le istruzioni per completare l'installazione.
3. Avvia ServBay e segui la procedura guidata di configurazione iniziale per configurarlo.


## Documentazione

Per una documentazione dettagliata e guide all'utilizzo, visita il [Centro di Documentazione di ServBay](https://support.servbay.com).

## Supporto

Se riscontri problemi durante l'utilizzo di ServBay, puoi ottenere supporto tramite i seguenti canali:

- [Centro Assistenza](https://support.servbay.com)
- [Community Discord](https://talk.servbay.com)
- [Community Telegram](https://telegram.servbay.dev)
- [Community WhatsApp](https://wa.servbay.dev)
- [Community WeChat](https://wechat-group.servbay.dev)
- [Invia una Segnalazione](https://github.com/ServBay/ServBay/issues)

## Community

Unisciti alla nostra community per scambiare esperienze con altri sviluppatori e ottenere gli ultimi aggiornamenti:

- [Blog di ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Grazie per aver utilizzato ServBay! Se hai domande o suggerimenti, non esitare a contattarci.
