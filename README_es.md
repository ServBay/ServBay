# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Logotipo de ServBay](/images/logo.png)

## Introducción

¡Deja de perder el tiempo administrando tu entorno de desarrollo!

ServBay es una [herramienta de administración de entornos de desarrollo web local](https://www.servbay.com) potente y completa, diseñada para desarrolladores web profesionales. ServBay incluye soporte para una variedad de lenguajes de desarrollo, bases de datos, servidores web, servidores de correo, servidores DNS, almacenamiento de objetos, proxies inversos e incluso una plataforma profesional de administración de certificados SSL. Todo lo que necesitas para el desarrollo web está aquí. Obtén un entorno de desarrollo local profesional configurado en solo 3 minutos.

![Panel de control de ServBay](/images/dashboard.png)

## Características

### Administración multisitio

¿[Administrando múltiples sitios web](https://support.servbay.com/basic-usage/websites/adding-first-website) simultáneamente? ServBay lo hace fácil. Configura y ejecuta sin esfuerzo numerosos sitios web en tu máquina local, cada uno con su propia configuración, dominio y entorno de desarrollo únicos. La interfaz intuitiva de ServBay simplifica el proceso, lo que te permite cambiar rápidamente entre proyectos y administrar sus configuraciones sin configuraciones complejas ni conflictos.

![Administración multisitio](/images/hosts.png)

### Servidores web

ServBay incluye los [servidores web](https://www.servbay.com/features/web-server) más populares, Caddy y NGINX, con soporte para HTTP/3 y CORS. También admite dominios personalizados y [configuración automática de SSL](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), lo que elimina la necesidad de comprar dominios y certificados SSL, ahorrando costos significativos durante el desarrollo.

![Servidores web](/images/web-servers.png)

### Lenguajes de desarrollo web

ServBay viene con [Node.js](https://www.servbay.com/features/nodejs) (versiones 12-23) y [PHP](https://www.servbay.com/features/php) (versiones 5.6-8.5), cubriendo las necesidades de los desarrolladores a lo largo del ciclo de vida del desarrollo web. Los desarrolladores pueden cambiar sin problemas entre diferentes versiones y usar diferentes versiones para diferentes proyectos. Esta inmensa flexibilidad brinda a los desarrolladores una gran confianza. ServBay también incluye Python y Golang.

![Lenguajes de desarrollo web](/images/languages.png)

### Bases de datos

Las [bases de datos](https://www.servbay.com/features/database) son esenciales para el desarrollo web. ServBay incluye [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) y el cada vez más popular [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage). Las bases de datos NoSQL también están cubiertas, con [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) y [MongoDB](https://www.servbay.com/features/database) listos para usar, sin necesidad de configuración. ServBay también integra [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) y [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) para una fácil administración de la base de datos.

![Bases de datos](/images/databases.png)

### Servicios de dominio y DNS

Los [dominios](https://www.servbay.com/features/dns-server) son un recurso consumible en el ciclo de vida del desarrollo web. ServBay incluye un [servidor DNS](https://www.servbay.com/features/dns-server), lo que permite a los desarrolladores utilizar dominios y TLD inexistentes sin registro, e incluso emitir certificados SSL para ellos. Esto no solo ahorra a los desarrolladores costos significativos, sino que también mejora la seguridad: los piratas informáticos no pueden acceder a un dominio inexistente. Además, ServBay proporciona una interfaz gráfica para administrar convenientemente tu archivo /etc/hosts.

![Servicios de dominio y DNS](/images/dns.png)

### Administración de certificados PKI y SSL

ServBay proporciona un [sistema PKI](https://www.servbay.com/features/ssl). Los desarrolladores pueden crear su propia Autoridad de certificación (CA) y emitir certificados SSL, lo cual es particularmente útil para equipos de desarrollo pequeños. Mediante el uso de una [CA privada](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management), los equipos pequeños pueden cifrar la transmisión de datos y establecer confianza interna dentro de su entorno de desarrollo. Esto se aplica no solo a los servicios web, sino también a las bases de datos, SMTP y otros servicios. ServBay incluso admite [certificados S/MIME](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) para el cifrado de correo electrónico, [certificados de firma de código](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) y [certificados de firma de documentos PDF](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Por supuesto, ServBay también admite la obtención y renovación automática de certificados SSL de Let's Encrypt, ZeroSSL y Google Trust Services a través de [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Administración de certificados PKI y SSL](/images/ssl-pki.png)

### Servidor de correo

¿Quieres usar SMTP/POP3 en tu desarrollo local? ¡No hay problema! ServBay incluye un [servidor de correo integrado](https://www.servbay.com/features/email-server). Integrado con el sistema PKI, el servidor de correo admite [STARTTLS y SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) sin configuración. ¿Necesitas retransmitir correo a un [servidor SMTP](https://www.servbay.com/features/email-server) externo? El servidor de correo de ServBay admite la retransmisión. También admitimos SpamAssassin, lo que te permite calificar cada correo electrónico saliente y reducir las posibilidades de que se marque como spam.


![Servidor de correo](/images/email-server.png)

![Correo web del servidor de correo](/images/email-server-webmail.png)

### Proxy inverso

¿Necesitas compartir temporalmente tu proyecto con los usuarios? ¿Quieres alojar un servidor en casa pero no tienes una dirección IP pública? ServBay te tiene cubierto. Admite [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp y Cloudflared para compartir rápidamente tu sitio web públicamente. ¿No confías en los servicios de terceros? ServBay también proporciona un servicio de proxy inverso público, perfectamente integrado para compartir con un solo clic.

*(Próximamente)*

### Entornos de ejecución a nivel de proyecto

ServBay ofrece configuración del entorno de ejecución a nivel de proyecto. Puedes configurar y bloquear las versiones requeridas de PHP y Node.js para diferentes proyectos, haciendo que el desarrollo de tu proyecto sea más flexible y controlable.


![Entornos de ejecución a nivel de proyecto](/images/project-level-runtime.png)

### Limpio y fácil de respaldar

ServBay es una instalación portátil, que no deja residuos en tu sistema, a diferencia de herramientas como Homebrew que pueden saturar los archivos de tu sistema. Puedes respaldar fácilmente tus datos utilizando Time Machine o rsync, lo que garantiza la seguridad de los datos.


![Limpio y fácil de respaldar](/images/easy-to-backup.png)

## Paquetes incluidos

ServBay viene con una variedad de paquetes esenciales para agilizar tu proceso de desarrollo:
- **Servidores web**: Caddy (2.8), Nginx (1.27) y Apache *(2.4, próximamente)*
- **Lenguajes de programación**: PHP (desde PHP 5.6 hasta PHP 8.5-Dev), Node.js (desde Node.js 12 hasta Node.js 23), Python *(próximamente)*, Golang *(próximamente)*
- **Bases de datos SQL**: MySQL (desde MySQL 5.1 hasta MySQL 9.1), MariaDB (desde MariaDB 10.4 hasta MariaDB 11.8), PostgreSQL (desde PostgreSQL 10 hasta PostgreSQL 17)
- **Bases de datos NoSQL**: Redis (7.2), Memcached (1.6), MongoDB (desde MongoDB 5.0 hasta MongoDB 8.0) y MongoSH 2
- **DNS**: Servidor DNS integrado para desarrollo local (dnsmasq 2.9)
- **Correo electrónico**: Mailpit para pruebas de correo electrónico locales
- **Túnel/Proxy inverso**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Otras herramientas**: phpMyAdmin, Adminer y más


![Paquetes incluidos en ServBay](/images/services.png)


## Instalación

Sigue estos pasos para instalar ServBay:

1. Descarga la última versión de ServBay desde el [sitio web oficial](https://www.servbay.com).
2. Abre el instalador y sigue las instrucciones para completar la instalación.
3. Inicia ServBay y sigue el asistente de configuración inicial para configurarlo.

## Documentación

Para obtener documentación detallada y guías de uso, visita el [Centro de documentación de ServBay](https://support.servbay.com).


## Soporte

Si encuentras algún problema al usar ServBay, puedes obtener soporte a través de los siguientes canales:


- [Centro de ayuda](https://support.servbay.com)
- [Comunidad Discord](https://talk.servbay.com)
- [Comunidad Telegram](https://telegram.servbay.dev)
- [Comunidad WhatsApp](https://wa.servbay.dev)
- [Comunidad WeChat](https://wechat-group.servbay.dev)
- [Enviar un problema](https://github.com/ServBay/ServBay/issues)


## Comunidad

Únete a nuestra comunidad para intercambiar experiencias con otros desarrolladores y obtener las últimas actualizaciones:


- [Blog de ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

¡Gracias por usar ServBay! Si tienes alguna pregunta o sugerencia, no dudes en contactarnos.
