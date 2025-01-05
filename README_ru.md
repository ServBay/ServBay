# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Логотип ServBay](/images/logo.png)

## Введение

Перестаньте тратить время на управление средой разработки!

ServBay — это мощный и комплексный [инструмент для управления локальной средой веб-разработки](https://www.servbay.com), разработанный для профессиональных веб-разработчиков. ServBay поддерживает различные языки разработки, базы данных, веб-серверы, почтовые серверы, DNS-серверы, объектное хранилище, обратные прокси и даже профессиональную платформу управления SSL-сертификатами. Всё, что вам нужно для веб-разработки, здесь. Настройте профессиональную локальную среду разработки всего за 3 минуты.

![Панель управления ServBay](/images/dashboard.png)

## Возможности

### Управление несколькими сайтами

[Управляете несколькими веб-сайтами](https://support.servbay.com/basic-usage/websites/adding-first-website) одновременно? ServBay упрощает эту задачу.  Без труда настраивайте и запускайте множество веб-сайтов на вашем локальном компьютере, каждый со своими уникальными настройками, доменом и средой разработки. Интуитивно понятный интерфейс ServBay упрощает процесс, позволяя быстро переключаться между проектами и управлять их конфигурациями без сложной настройки и конфликтов.

![Управление несколькими сайтами](/images/hosts.png)

### Веб-серверы

ServBay включает в себя самые популярные [веб-серверы](https://www.servbay.com/features/web-server) — Caddy и NGINX, с поддержкой HTTP/3 и CORS. Он также поддерживает пользовательские домены и [автоматическую настройку SSL](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), что исключает необходимость покупки доменов и SSL-сертификатов, экономя значительные средства во время разработки.

![Веб-серверы](/images/web-servers.png)

### Языки веб-разработки

ServBay поставляется с [Node.js](https://www.servbay.com/features/nodejs) (версии 12-23) и [PHP](https://www.servbay.com/features/php) (версии 5.6-8.5), покрывая потребности разработчиков на протяжении всего жизненного цикла веб-разработки. Разработчики могут легко переключаться между различными версиями и использовать разные версии для разных проектов. Эта огромная гибкость дает разработчикам уверенность. ServBay также включает Python и Golang.

![Языки веб-разработки](/images/languages.png)

### Базы данных

[Базы данных](https://www.servbay.com/features/database) необходимы для веб-разработки. ServBay включает [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) и на всё более популярный [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage).  NoSQL базы данных также поддерживаются: [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) и [MongoDB](https://www.servbay.com/features/database) готовы к использованию "из коробки", не требуя настройки. ServBay также интегрирует [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) и [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) для удобного управления базами данных.

![Базы данных](/images/databases.png)

### Службы доменов и DNS

[Домены](https://www.servbay.com/features/dns-server) — это расходуемый ресурс в жизненном цикле веб-разработки. ServBay включает в себя [DNS-сервер](https://www.servbay.com/features/dns-server), позволяющий разработчикам использовать несуществующие домены и TLD без регистрации и даже выпускать для них SSL-сертификаты. Это не только экономит разработчикам значительные средства, но и повышает безопасность — хакеры не могут получить доступ к несуществующему домену. Кроме того, ServBay предоставляет графический интерфейс для удобного управления файлом /etc/hosts.

![Службы доменов и DNS](/images/dns.png)

### Управление PKI и SSL-сертификатами

ServBay предоставляет [систему PKI](https://www.servbay.com/features/ssl). Разработчики могут создавать свои собственные центры сертификации (CA) и выпускать SSL-сертификаты, что особенно полезно для небольших команд разработчиков. Используя [частный CA](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management), небольшие команды могут шифровать передачу данных и устанавливать внутреннее доверие в своей среде разработки. Это относится не только к веб-сервисам, но и к базам данных, SMTP и другим службам. ServBay даже поддерживает [S/MIME сертификаты](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) для шифрования электронной почты, [сертификаты подписи кода](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) и [сертификаты подписи PDF-документов](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Конечно, ServBay также поддерживает получение и автоматическое обновление SSL-сертификатов от Let's Encrypt, ZeroSSL и Google Trust Services через [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Управление PKI и SSL-сертификатами](/images/ssl-pki.png)

### Почтовый сервер

Хотите использовать SMTP/POP3 в своей локальной разработке? Без проблем! ServBay включает в себя [встроенный почтовый сервер](https://www.servbay.com/features/email-server). Интегрированный с системой PKI, почтовый сервер поддерживает [STARTTLS и SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) без какой-либо настройки. Нужно переслать почту на внешний [SMTP-сервер](https://www.servbay.com/features/email-server)? Почтовый сервер ServBay поддерживает пересылку. Мы также поддерживаем SpamAssassin, позволяя вам оценивать каждое исходящее электронное письмо и снижать вероятность того, что оно будет помечено как спам.

![Почтовый сервер](/images/email-server.png)

![Веб-почта почтового сервера](/images/email-server-webmail.png)

### Обратный прокси-сервер

Нужно временно поделиться своим проектом с пользователями? Хотите разместить сервер дома, но у вас нет публичного IP-адреса? ServBay поможет вам. Он поддерживает [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp и Cloudflared для быстрой публикации вашего веб-сайта. Не доверяете сторонним сервисам? ServBay также предоставляет общедоступный сервис обратного прокси-сервера, легко интегрируемый для публикации в один клик.

*(Скоро)*

### Среды выполнения на уровне проекта

ServBay предлагает настройку среды выполнения на уровне проекта. Вы можете настраивать и фиксировать требуемые версии PHP и Node.js для различных проектов, делая разработку вашего проекта более гибкой и управляемой.

![Среды выполнения на уровне проекта](/images/project-level-runtime.png)

### Чистый и простой в резервном копировании

ServBay — это портативная установка, не оставляющая следов в вашей системе, в отличие от таких инструментов, как Homebrew, которые могут засорять ваши системные файлы. Вы можете легко создавать резервные копии своих данных с помощью Time Machine или rsync, обеспечивая безопасность данных.

![Чистый и простой в резервном копировании](/images/easy-to-backup.png)


## Включенные пакеты

ServBay поставляется с различными необходимыми пакетами для оптимизации процесса разработки:

- **Веб-серверы**: Caddy (2.8), Nginx (1.27) и Apache *(2.4, скоро)*
- **Языки программирования**: PHP (от PHP 5.6 до PHP 8.5-Dev), Node.js (от Node.js 12 до Node.js 23), Python *(скоро)*, Golang *(скоро)*
- **SQL базы данных**: MySQL (от MySQL 5.1 до MySQL 9.1), MariaDB (от MariaDB 10.4 до MariaDB 11.8), PostgreSQL (от PostgreSQL 10 до PostgreSQL 17)
- **NoSQL базы данных**: Redis (7.2), Memcached (1.6), MongoDB (от MongoDB 5.0 до MongoDB 8.0) и MongoSH 2
- **DNS**: Встроенный DNS-сервер для локальной разработки (dnsmasq 2.9)
- **Электронная почта**: Mailpit для локального тестирования электронной почты
- **Туннель/Обратный прокси**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Другие инструменты**: phpMyAdmin, Adminer и другие

![Включенные пакеты ServBay](/images/services.png)

## Установка

Выполните следующие действия, чтобы установить ServBay:

1. Загрузите последнюю версию ServBay с [официального веб-сайта](https://www.servbay.com).
2. Откройте установщик и следуйте инструкциям для завершения установки.
3. Запустите ServBay и следуйте инструкциям мастера начальной настройки.

## Документация

Подробную документацию и руководства пользователя см. в [центре документации ServBay](https://support.servbay.com).

## Поддержка

Если у вас возникнут какие-либо проблемы при использовании ServBay, вы можете получить поддержку по следующим каналам:

- [Центр помощи](https://support.servbay.com)
- [Сообщество Discord](https://talk.servbay.com)
- [Сообщество Telegram](https://telegram.servbay.dev)
- [Сообщество WhatsApp](https://wa.servbay.dev)
- [Сообщество WeChat](https://wechat-group.servbay.dev)
- [Создать обращение](https://github.com/ServBay/ServBay/issues)


## Сообщество

Присоединяйтесь к нашему сообществу, чтобы обменяться опытом с другими разработчиками и получать последние обновления:

- [Блог ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Спасибо за использование ServBay! Если у вас есть какие-либо вопросы или предложения, пожалуйста, свяжитесь с нами.
