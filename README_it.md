# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introduzione

Smetti di sprecare tempo a gestire il tuo ambiente di sviluppo!

ServBay è un potente e completo strumento di gestione dell'ambiente di sviluppo web locale, progettato per sviluppatori web professionisti, ora disponibile sia per **macOS che per Windows**. ServBay include il supporto per una varietà di linguaggi di sviluppo, database, server web, server di posta, server DNS e proxy inversi. Ora dispone anche di capacità di sviluppo AI integrate con Ollama, archiviazione di oggetti con MinIO, ricerca potente con Typesense e Meilisearch, e un robusto sistema di backup. Tutto ciò di cui hai bisogno per lo sviluppo web è qui. Ottieni un ambiente di sviluppo locale professionale configurato in soli 3 minuti.

![ServBay Dashboard](/images/dashboard.png)

## Caratteristiche

### Gestione Multi-sito

Gestisci più siti web contemporaneamente? ServBay lo rende facile. Configura ed esegui senza sforzo numerosi siti web sulla tua macchina locale, ognuno con le proprie impostazioni, dominio e ambiente di sviluppo unici. L'interfaccia intuitiva di ServBay semplifica il processo, permettendoti di passare rapidamente da un progetto all'altro e di gestire le loro configurazioni senza setup complessi o conflitti.

![Multi-site Management](/images/website.png)

### Server Web

ServBay include i server web più popolari—**Caddy, NGINX e Apache**—con supporto per HTTP/3 e CORS. Supporta anche domini personalizzati e la configurazione SSL automatizzata, eliminando la necessità di acquistare domini e certificati SSL, risparmiando costi significativi durante lo sviluppo.

![Web Servers](/images/web-servers.png)

### Linguaggi di Sviluppo Web

ServBay è dotato di una vasta gamma di linguaggi di sviluppo, tra cui **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, e persino **.NET** (2.0-10.0) & **Mono**. Gli sviluppatori possono passare senza problemi tra diverse versioni e utilizzare versioni diverse per progetti diversi. Questa immensa flessibilità dà agli sviluppatori una forte fiducia.

![Web Development Languages](/images/languages.png)

### Database

I database sono essenziali per lo sviluppo web. ServBay include **MySQL**, **MariaDB** e il sempre più popolare **PostgreSQL**. Sono coperti anche i database NoSQL, con **Redis**, **Memcached** e **MongoDB** pronti all'uso, senza necessità di configurazione. ServBay integra anche **phpMyAdmin** e **Adminer** per una facile gestione dei database.

![Databases](/images/databases.png)

### Sviluppo AI con Ollama

Abbraccia il futuro dello sviluppo con capacità AI integrate. ServBay incorpora Ollama, permettendoti di eseguire localmente potenti Modelli Linguistici di Grandi Dimensioni (LLM) come Llama 3, Mistral e Gemma. Costruisci e testa applicazioni basate sull'IA con latenza zero e completa privacy dei dati, tutto gestito tramite l'interfaccia intuitiva di ServBay.

![AI Development with Ollama](/images/ai.png)

### Ricerca Potente con Typesense & Meilisearch

Potenzia le tue applicazioni con motori di ricerca moderni e veloci. ServBay include sia **Typesense** che **Meilisearch**, due delle principali soluzioni di ricerca open-source che puoi aggiungere ai tuoi progetti con un solo clic.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Archiviazione di Oggetti con MinIO

Gestisci i dati non strutturati con facilità utilizzando MinIO, un servizio di archiviazione di oggetti ad alte prestazioni compatibile con S3, ora incluso in ServBay. È perfetto per archiviare di tutto, dai backup e log ai file multimediali e agli artefatti, fornendo una solida soluzione di archiviazione per le tue esigenze di sviluppo locale.

![Object Storage with MinIO](/images/minio.png)

### Servizi di Dominio e DNS

I domini sono una risorsa consumabile nel ciclo di vita dello sviluppo web. ServBay include un server DNS, che consente agli sviluppatori di utilizzare domini e TLD inesistenti senza registrazione, e persino di emettere certificati SSL per essi. Questo non solo fa risparmiare agli sviluppatori costi significativi, ma migliora anche la sicurezza: gli hacker non possono accedere a un dominio inesistente. Inoltre, ServBay fornisce un'interfaccia grafica per gestire comodamente il tuo file hosts.

![Domain and DNS Services](/images/dns.png)

### Gestione PKI e Certificati SSL

ServBay fornisce un sistema PKI. Gli sviluppatori possono creare la propria Autorità di Certificazione (CA) ed emettere certificati SSL, particolarmente utile per piccoli team di sviluppo. Utilizzando una CA privata, i piccoli team possono crittografare la trasmissione dei dati e stabilire una fiducia interna nel loro ambiente di sviluppo. Questo non si applica solo ai servizi web, ma anche a database, SMTP e altri servizi. ServBay supporta persino certificati S/MIME per la crittografia delle email, certificati di firma del codice e certificati di firma di documenti PDF.

Naturalmente, ServBay supporta anche l'ottenimento e il rinnovo automatico dei certificati SSL da Let's Encrypt, ZeroSSL e Google Trust Services tramite ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Server di Posta

Vuoi usare SMTP/POP3 nel tuo sviluppo locale? Nessun problema! ServBay include un server di posta integrato con **Mailpit** per i test di posta elettronica locali. Integrato con il sistema PKI, il server di posta supporta STARTTLS e SSL/TLS senza configurazione. Hai bisogno di inoltrare la posta a un server SMTP esterno? Il server di posta di ServBay supporta l'inoltro. Supportiamo anche SpamAssassin, che ti permette di assegnare un punteggio a ogni email in uscita e ridurre le possibilità che venga contrassegnata come spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Proxy Inverso

Hai bisogno di condividere temporaneamente il tuo progetto con gli utenti? Vuoi ospitare un server a casa ma non hai un indirizzo IP pubblico? ServBay ha la soluzione. Supporta **ngrok, frp, Cloudflared e Pinggy** per condividere rapidamente il tuo sito web pubblicamente.

![Reverse Proxy](/images/tunnel.png)

### Ambienti di Esecuzione a Livello di Progetto

ServBay offre la configurazione dell'ambiente di esecuzione a livello di progetto. Puoi configurare e bloccare le versioni di PHP e Node.js richieste per diversi progetti, rendendo lo sviluppo del tuo progetto più flessibile e controllabile.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Backup e Ripristino Potenti

La sicurezza dei dati e il ripristino dell'ambiente sono cruciali. ServBay dispone di un sistema completo di backup e ripristino per darti la massima tranquillità.
*   **Backup con un clic e pianificati**: Configura backup automatici e pianificati, o avvia backup manuali dei tuoi database, file del sito web, configurazioni dei servizi e certificati SSL.
*   **Ripristino e Migrazione Facili**: Ripristina rapidamente il tuo ambiente a uno stato precedente in caso di problemi, o usa i backup per migrare facilmente l'intera configurazione di ServBay su una nuova macchina.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Pacchetti Inclusi

ServBay è dotato di una varietà di pacchetti essenziali per semplificare il tuo processo di sviluppo:

-   **Server Web**: Caddy, Nginx, Apache
-   **Linguaggi di Programmazione**: PHP (da 5.6 a 8.5-Alpha), Node.js (da 12 a 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **Database SQL**: MySQL (da 5.1 a 9.3), MariaDB (da 10.4 a 12.0), PostgreSQL (da 10 a 17)
-   **Database NoSQL**: Redis, Memcached, MongoDB (da 5.0 a 8.0) & MongoSH 2
-   **AI / LLM**: Ollama
-   **Motori di Ricerca**: Typesense, Meilisearch
-   **Archiviazione di Oggetti**: MinIO
-   **DNS**: Server DNS integrato (dnsmasq)
-   **Email**: Mailpit per i test di posta elettronica locali
-   **Tunnel/Proxy Inverso**: Cloudflared, frp, Ngrok, Pinggy
-   **Altri Strumenti**: phpMyAdmin, Adminer, Composer, e altro ancora

![ServBay Bundled Packages](/images/services.png)

## Installazione

ServBay è disponibile sia per macOS che per Windows.

### macOS

1.  Scarica l'ultima versione di ServBay per macOS dal [sito web ufficiale](https://www.servbay.com/download).
2.  Apri l'installer e segui le istruzioni per completare l'installazione.
3.  Avvia ServBay e segui la procedura guidata di configurazione iniziale per configurarlo.

### Windows

1.  Scarica l'ultima versione di ServBay per Windows dalla [pagina di download ufficiale](https://www.servbay.com/download) o direttamente dal [repository delle release di Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  Esegui l'installer e segui le istruzioni a schermo.
3.  Avvia ServBay per iniziare a configurare il tuo ambiente di sviluppo locale.

## Documentazione

Per documentazione dettagliata e guide all'uso, visita il [Centro Documentazione di ServBay](https://support.servbay.com).

## Supporto

Se incontri problemi durante l'uso di ServBay, puoi ottenere supporto attraverso i seguenti canali:

-   [Centro Assistenza](https://support.servbay.com)
-   [Comunità Discord](https://talk.servbay.com)
-   [Comunità Telegram](https://telegram.servbay.dev)
-   [Comunità WhatsApp](https://wa.servbay.dev)
-   [Comunità WeChat](https://wechat-group.servbay.dev)
-   [Invia un Problema](https://github.com/ServBay/ServBay/issues)

## Comunità

Unisciti alla nostra comunità per scambiare esperienze con altri sviluppatori e ricevere gli ultimi aggiornamenti:

-   [Blog di ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Grazie per aver usato ServBay! Se hai domande o suggerimenti, non esitare a contattarci.