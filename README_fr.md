# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introduction

Ne perdez plus de temps à gérer votre environnement de développement !

ServBay est un outil de gestion d'environnement de développement web local puissant et complet, conçu pour les développeurs web professionnels, maintenant disponible pour **macOS et Windows**. ServBay inclut le support d'une variété de langages de développement, de bases de données, de serveurs web, de serveurs de messagerie, de serveurs DNS et de proxys inverses. Il dispose désormais également de capacités de développement IA intégrées avec Ollama, de stockage d'objets avec MinIO, de recherche puissante avec Typesense et Meilisearch, et d'un système de sauvegarde robuste. Tout ce dont vous avez besoin pour le développement web est ici. Obtenez un environnement de développement local professionnel en seulement 3 minutes.

![ServBay Dashboard](/images/dashboard.png)

## Fonctionnalités

### Gestion multi-sites

Gérer plusieurs sites web simultanément ? ServBay rend cela facile. Configurez et exécutez sans effort de nombreux sites web sur votre machine locale, chacun avec ses propres paramètres, domaine et environnement de développement uniques. L'interface intuitive de ServBay simplifie le processus, vous permettant de basculer rapidement entre les projets et de gérer leurs configurations sans installation complexe ni conflits.

![Multi-site Management](/images/website.png)

### Serveurs Web

ServBay inclut les serveurs web les plus populaires—**Caddy, NGINX et Apache**—avec prise en charge de HTTP/3 et CORS. Il prend également en charge les domaines personnalisés et la configuration SSL automatisée, éliminant le besoin d'acheter des domaines et des certificats SSL, ce qui permet de réaliser des économies importantes pendant le développement.

![Web Servers](/images/web-servers.png)

### Langages de développement Web

ServBay est livré avec une vaste gamme de langages de développement, y compris **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, et même **.NET** (2.0-10.0) & **Mono**. Les développeurs peuvent basculer de manière transparente entre différentes versions et utiliser différentes versions pour différents projets. Cette immense flexibilité donne aux développeurs une grande confiance.

![Web Development Languages](/images/languages.png)

### Bases de données

Les bases de données sont essentielles pour le développement web. ServBay inclut **MySQL**, **MariaDB**, et le de plus en plus populaire **PostgreSQL**. Les bases de données NoSQL sont également couvertes, avec **Redis**, **Memcached** et **MongoDB** prêts à l'emploi, ne nécessitant aucune configuration. ServBay intègre également **phpMyAdmin** et **Adminer** pour une gestion facile des bases de données.

![Databases](/images/databases.png)

### Développement IA avec Ollama

Adoptez l'avenir du développement avec des capacités d'IA intégrées. ServBay intègre Ollama, vous permettant d'exécuter localement de puissants Grands Modèles de Langage (LLM) comme Llama 3, Mistral et Gemma. Créez et testez des applications basées sur l'IA avec une latence nulle et une confidentialité totale des données, le tout géré via l'interface intuitive de ServBay.

![AI Development with Ollama](/images/ai.png)

### Recherche puissante avec Typesense & Meilisearch

Alimentez vos applications avec des moteurs de recherche modernes et rapides. ServBay inclut à la fois **Typesense** et **Meilisearch**, deux des principales solutions de recherche open-source que vous pouvez ajouter à vos projets en un clic.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Stockage d'objets avec MinIO

Gérez facilement les données non structurées avec MinIO, un service de stockage d'objets haute performance compatible S3, désormais inclus avec ServBay. Il est parfait pour stocker tout, des sauvegardes et des journaux aux fichiers multimédias et aux artefacts, offrant une solution de stockage robuste pour vos besoins de développement local.

![Object Storage with MinIO](/images/minio.png)

### Services de domaine et DNS

Les domaines sont une ressource consommable dans le cycle de vie du développement web. ServBay inclut un serveur DNS, permettant aux développeurs d'utiliser des domaines et des TLD inexistants sans enregistrement, et même d'émettre des certificats SSL pour eux. Cela permet non seulement aux développeurs de réaliser des économies importantes, mais aussi d'améliorer la sécurité—les pirates ne peuvent pas accéder à un domaine inexistant. De plus, ServBay fournit une interface graphique pour gérer facilement votre fichier hosts.

![Domain and DNS Services](/images/dns.png)

### Gestion PKI et des certificats SSL

ServBay fournit un système PKI. Les développeurs peuvent créer leur propre Autorité de Certification (CA) et émettre des certificats SSL—particulièrement utile pour les petites équipes de développement. En utilisant une CA privée, les petites équipes peuvent chiffrer la transmission des données et établir une confiance interne dans leur environnement de développement. Cela s'applique non seulement aux services web, mais aussi aux bases de données, SMTP et autres services. ServBay prend même en charge les certificats S/MIME pour le chiffrement des e-mails, les certificats de signature de code et les certificats de signature de documents PDF.

Bien sûr, ServBay prend également en charge l'obtention et le renouvellement automatique des certificats SSL de Let's Encrypt, ZeroSSL et Google Trust Services via ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Serveur de messagerie

Vous voulez utiliser SMTP/POP3 dans votre développement local ? Pas de problème ! ServBay inclut un serveur de messagerie intégré avec **Mailpit** pour les tests d'e-mails locaux. Intégré au système PKI, le serveur de messagerie prend en charge STARTTLS et SSL/TLS sans configuration. Besoin de relayer le courrier vers un serveur SMTP externe ? Le serveur de messagerie de ServBay prend en charge le relais. Nous prenons également en charge SpamAssassin, vous permettant de noter chaque e-mail sortant et de réduire les chances qu'il soit marqué comme spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Proxy inverse

Besoin de partager temporairement votre projet avec des utilisateurs ? Vous voulez héberger un serveur à la maison mais vous n'avez pas d'adresse IP publique ? ServBay a ce qu'il vous faut. Il prend en charge **ngrok, frp, Cloudflared et Pinggy** pour partager rapidement votre site web publiquement.

![Reverse Proxy](/images/tunnel.png)

### Environnements d'exécution au niveau du projet

ServBay offre une configuration d'environnement d'exécution au niveau du projet. Vous pouvez configurer et verrouiller les versions de PHP et Node.js requises pour différents projets, rendant le développement de votre projet plus flexible et contrôlable.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Sauvegarde et restauration puissantes

La sécurité des données et la récupération de l'environnement sont cruciales. ServBay dispose d'un système complet de sauvegarde et de restauration pour vous offrir la tranquillité d'esprit.
*   **Sauvegardes en un clic et planifiées** : Configurez des sauvegardes automatiques et planifiées, ou déclenchez des sauvegardes manuelles de vos bases de données, fichiers de site web, configurations de service et certificats SSL.
*   **Restauration et migration faciles** : Restaurez rapidement votre environnement à un état antérieur en cas de problème, ou utilisez les sauvegardes pour migrer facilement toute votre configuration ServBay vers une nouvelle machine.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Paquets inclus

ServBay est livré avec une variété de paquets essentiels pour rationaliser votre processus de développement :

-   **Serveurs Web** : Caddy, Nginx, Apache
-   **Langages de programmation** : PHP (de 5.6 à 8.5-Alpha), Node.js (de 12 à 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **Bases de données SQL** : MySQL (de 5.1 à 9.3), MariaDB (de 10.4 à 12.0), PostgreSQL (de 10 à 17)
-   **Bases de données NoSQL** : Redis, Memcached, MongoDB (de 5.0 à 8.0) & MongoSH 2
-   **IA / LLM** : Ollama
-   **Moteurs de recherche** : Typesense, Meilisearch
-   **Stockage d'objets** : MinIO
-   **DNS** : Serveur DNS intégré (dnsmasq)
-   **E-mail** : Mailpit pour les tests d'e-mails locaux
-   **Tunnel/Proxy inverse** : Cloudflared, frp, Ngrok, Pinggy
-   **Autres outils** : phpMyAdmin, Adminer, Composer, et plus

![ServBay Bundled Packages](/images/services.png)

## Installation

ServBay est disponible pour macOS et Windows.

### macOS

1.  Téléchargez la dernière version de ServBay pour macOS sur le [site officiel](https://www.servbay.com/download).
2.  Ouvrez l'installateur et suivez les instructions pour terminer l'installation.
3.  Lancez ServBay et suivez l'assistant de configuration initiale pour le configurer.

### Windows

1.  Téléchargez la dernière version de ServBay pour Windows depuis la [page de téléchargement officielle](https://www.servbay.com/download) ou directement depuis le [dépôt des versions Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  Exécutez l'installateur et suivez les instructions à l'écran.
3.  Lancez ServBay pour commencer à configurer votre environnement de développement local.

## Documentation

Pour une documentation détaillée et des guides d'utilisation, visitez le [Centre de documentation de ServBay](https://support.servbay.com).

## Support

Si vous rencontrez des problèmes lors de l'utilisation de ServBay, vous pouvez obtenir de l'aide via les canaux suivants :

-   [Centre d'aide](https://support.servbay.com)
-   [Communauté Discord](https://talk.servbay.com)
-   [Communauté Telegram](https://telegram.servbay.dev)
-   [Communauté WhatsApp](https://wa.servbay.dev)
-   [Communauté WeChat](https://wechat-group.servbay.dev)
-   [Soumettre un problème](https://github.com/ServBay/ServBay/issues)

## Communauté

Rejoignez notre communauté pour échanger des expériences avec d'autres développeurs et obtenir les dernières mises à jour :

-   [Blog de ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Merci d'utiliser ServBay ! Si vous avez des questions ou des suggestions, n'hésitez pas à nous contacter.