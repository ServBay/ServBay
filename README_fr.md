# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Logo ServBay](/images/logo.png)

## Introduction

Arrêtez de perdre du temps à gérer votre environnement de développement !

ServBay est un [outil puissant et complet de gestion d'environnement de développement web local](https://www.servbay.com) conçu pour les développeurs web professionnels. ServBay prend en charge une variété de langages de développement, de bases de données, de serveurs web, de serveurs de messagerie, de serveurs DNS, de stockage d'objets, de proxys inverses et même une plateforme professionnelle de gestion de certificats SSL. Tout ce dont vous avez besoin pour le développement web est ici. Obtenez un environnement de développement local professionnel configuré en seulement 3 minutes.

![Tableau de bord ServBay](/images/dashboard.png)

## Fonctionnalités

### Gestion multi-sites

[Vous gérez plusieurs sites web](https://support.servbay.com/basic-usage/websites/adding-first-website) simultanément ? ServBay simplifie la tâche.  Configurez et exécutez sans effort de nombreux sites web sur votre machine locale, chacun avec ses propres paramètres, domaine et environnement de développement uniques. L'interface intuitive de ServBay simplifie le processus, vous permettant de basculer rapidement entre les projets et de gérer leurs configurations sans configuration complexe ni conflits.

![Gestion multi-sites](/images/hosts.png)

### Serveurs web

ServBay inclut les [serveurs web](https://www.servbay.com/features/web-server) les plus populaires, Caddy et NGINX, avec la prise en charge de HTTP/3 et CORS.  Il prend également en charge les domaines personnalisés et la [configuration SSL automatisée](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), éliminant ainsi le besoin d'acheter des domaines et des certificats SSL, ce qui permet de réaliser des économies considérables pendant le développement.

![Serveurs web](/images/web-servers.png)

### Langages de développement web

ServBay est fourni avec [Node.js](https://www.servbay.com/features/nodejs) (versions 12 à 23) et [PHP](https://www.servbay.com/features/php) (versions 5.6 à 8.5), couvrant ainsi les besoins des développeurs tout au long du cycle de vie du développement web. Les développeurs peuvent basculer facilement entre différentes versions et utiliser des versions différentes pour différents projets. Cette immense flexibilité donne aux développeurs une grande confiance. ServBay inclut également Python et Golang.

![Langages de développement web](/images/languages.png)

### Bases de données

Les [bases de données](https://www.servbay.com/features/database) sont essentielles au développement web. ServBay inclut [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) et le de plus en plus populaire [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage).  Les bases de données NoSQL sont également prises en charge, avec [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) et [MongoDB](https://www.servbay.com/features/database) prêts à l'emploi, sans aucune configuration requise. ServBay intègre également [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) et [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) pour une gestion facile des bases de données.

![Bases de données](/images/databases.png)

### Services de domaine et DNS

Les [domaines](https://www.servbay.com/features/dns-server) sont une ressource consommable dans le cycle de vie du développement web. ServBay inclut un [serveur DNS](https://www.servbay.com/features/dns-server), permettant aux développeurs d'utiliser des domaines et des TLD inexistants sans enregistrement, et même d'émettre des certificats SSL pour ceux-ci. Cela permet non seulement aux développeurs de réaliser des économies considérables, mais aussi d'améliorer la sécurité : les pirates informatiques ne peuvent pas accéder à un domaine inexistant. De plus, ServBay fournit une interface graphique pour gérer facilement votre fichier /etc/hosts.

![Services de domaine et DNS](/images/dns.png)

### Gestion des certificats PKI et SSL

ServBay fournit un [système PKI](https://www.servbay.com/features/ssl). Les développeurs peuvent créer leur propre autorité de certification (CA) et émettre des certificats SSL, ce qui est particulièrement utile pour les petites équipes de développement.  L'utilisation d'une [CA privée](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management) permet aux petites équipes de chiffrer la transmission des données et d'établir une confiance interne au sein de leur environnement de développement. Cela s'applique non seulement aux services web, mais aussi aux bases de données, à SMTP et à d'autres services. ServBay prend même en charge les [certificats S/MIME](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) pour le chiffrement des e-mails, les [certificats de signature de code](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) et les [certificats de signature de documents PDF](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Bien sûr, ServBay prend également en charge l'obtention et le renouvellement automatique des certificats SSL de Let's Encrypt, ZeroSSL et Google Trust Services via [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Gestion des certificats PKI et SSL](/images/ssl-pki.png)

### Serveur de messagerie

Vous souhaitez utiliser SMTP/POP3 dans votre développement local ? Aucun problème ! ServBay inclut un [serveur de messagerie intégré](https://www.servbay.com/features/email-server). Intégré au système PKI, le serveur de messagerie prend en charge [STARTTLS et SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) sans configuration.  Besoin de relayer le courrier vers un [serveur SMTP](https://www.servbay.com/features/email-server) externe ? Le serveur de messagerie de ServBay prend en charge le relayage. Nous prenons également en charge SpamAssassin, vous permettant d'évaluer chaque e-mail sortant et de réduire les risques qu'il soit marqué comme spam.


![Serveur de messagerie](/images/email-server.png)

![Webmail du serveur de messagerie](/images/email-server-webmail.png)

### Proxy inverse

Vous devez partager temporairement votre projet avec des utilisateurs ? Vous souhaitez héberger un serveur chez vous, mais vous ne disposez pas d'une adresse IP publique ? ServBay a ce qu'il vous faut. Il prend en charge [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp et Cloudflared pour partager rapidement votre site web publiquement. Vous ne faites pas confiance aux services tiers ? ServBay propose également un service de proxy inverse public, intégré de manière transparente pour un partage en un clic.

*(Bientôt disponible)*

### Environnements d'exécution au niveau du projet

ServBay offre une configuration d'environnement d'exécution au niveau du projet. Vous pouvez configurer et verrouiller les versions requises de PHP et Node.js pour différents projets, rendant le développement de votre projet plus flexible et contrôlable.

![Environnements d'exécution au niveau du projet](/images/project-level-runtime.png)

### Propre et facile à sauvegarder

ServBay est une installation portable, ne laissant aucun résidu sur votre système, contrairement à des outils comme Homebrew qui peuvent encombrer vos fichiers système. Vous pouvez facilement sauvegarder vos données à l'aide de Time Machine ou rsync, garantissant ainsi la sécurité des données.

![Propre et facile à sauvegarder](/images/easy-to-backup.png)

## Paquets inclus

ServBay est livré avec une variété de paquets essentiels pour rationaliser votre processus de développement :

- **Serveurs web** : Caddy (2.8), Nginx (1.27) et Apache *(2.4, bientôt disponible)*
- **Langages de programmation** : PHP (de PHP 5.6 à PHP 8.5-Dev), Node.js (de Node.js 12 à Node.js 23), Python *(bientôt disponible)*, Golang *(bientôt disponible)*
- **Bases de données SQL** : MySQL (de MySQL 5.1 à MySQL 9.1), MariaDB (de MariaDB 10.4 à MariaDB 11.8), PostgreSQL (de PostgreSQL 10 à PostgreSQL 17)
- **Bases de données NoSQL** : Redis (7.2), Memcached (1.6), MongoDB (de MongoDB 5.0 à MongoDB 8.0) et MongoSH 2
- **DNS** : Serveur DNS intégré pour le développement local (dnsmasq 2.9)
- **Messagerie électronique** : Mailpit pour les tests d'e-mails locaux
- **Tunnel/Proxy inverse** : Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Autres outils** : phpMyAdmin, Adminer, etc.

![Paquets inclus dans ServBay](/images/services.png)

## Installation

Suivez ces étapes pour installer ServBay :

1. Téléchargez la dernière version de ServBay depuis le [site web officiel](https://www.servbay.com).
2. Ouvrez le programme d'installation et suivez les instructions pour terminer l'installation.
3. Lancez ServBay et suivez l'assistant de configuration initiale.

## Documentation

Pour une documentation détaillée et des guides d'utilisation, consultez le [Centre de documentation ServBay](https://support.servbay.com).

## Support

Si vous rencontrez des problèmes lors de l'utilisation de ServBay, vous pouvez obtenir de l'aide via les canaux suivants :

- [Centre d'aide](https://support.servbay.com)
- [Communauté Discord](https://talk.servbay.com)
- [Communauté Telegram](https://telegram.servbay.dev)
- [Communauté WhatsApp](https://wa.servbay.dev)
- [Communauté WeChat](https://wechat-group.servbay.dev)
- [Soumettre un problème](https://github.com/ServBay/ServBay/issues)


## Communauté

Rejoignez notre communauté pour échanger des expériences avec d'autres développeurs et obtenir les dernières mises à jour :

- [Blog ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Merci d'utiliser ServBay ! Si vous avez des questions ou des suggestions, n'hésitez pas à nous contacter.

