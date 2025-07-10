# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introducción

¡Deje de perder tiempo en la gestión de su entorno de desarrollo!

ServBay es una herramienta de gestión de entorno de desarrollo web local potente y completa, diseñada para desarrolladores web profesionales, ahora disponible tanto para **macOS como para Windows**. ServBay incluye soporte para una variedad de lenguajes de desarrollo, bases de datos, servidores web, servidores de correo, servidores DNS y proxies inversos. Ahora también cuenta con capacidades de desarrollo de IA integradas con Ollama, almacenamiento de objetos con MinIO, búsqueda potente con Typesense y Meilisearch, y un robusto sistema de copias de seguridad. Todo lo que necesita para el desarrollo web está aquí. Configure un entorno de desarrollo local profesional en solo 3 minutos.

![ServBay Dashboard](/images/dashboard.png)

## Características

### Gestión de Múltiples Sitios

¿Gestionando múltiples sitios web simultáneamente? ServBay lo hace fácil. Configure y ejecute sin esfuerzo numerosos sitios web en su máquina local, cada uno con su propia configuración, dominio y entorno de desarrollo únicos. La interfaz intuitiva de ServBay simplifica el proceso, permitiéndole cambiar rápidamente entre proyectos y gestionar sus configuraciones sin instalaciones complejas ni conflictos.

![Multi-site Management](/images/website.png)

### Servidores Web

ServBay incluye los servidores web más populares—**Caddy, NGINX y Apache**—con soporte para HTTP/3 y CORS. También admite dominios personalizados y configuración automática de SSL, eliminando la necesidad de comprar dominios y certificados SSL, lo que ahorra costos significativos durante el desarrollo.

![Web Servers](/images/web-servers.png)

### Lenguajes de Desarrollo Web

ServBay viene con una vasta gama de lenguajes de desarrollo, incluyendo **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, e incluso **.NET** (2.0-10.0) y **Mono**. Los desarrolladores pueden cambiar sin problemas entre diferentes versiones y usar diferentes versiones para diferentes proyectos. Esta inmensa flexibilidad da a los desarrolladores una gran confianza.

![Web Development Languages](/images/languages.png)

### Bases de Datos

Las bases de datos son esenciales para el desarrollo web. ServBay incluye **MySQL**, **MariaDB** y el cada vez más popular **PostgreSQL**. Las bases de datos NoSQL también están cubiertas, con **Redis**, **Memcached** y **MongoDB** listos para usar sin necesidad de configuración. ServBay también integra **phpMyAdmin** y **Adminer** para una fácil gestión de bases de datos.

![Databases](/images/databases.png)

### Desarrollo de IA con Ollama

Abrace el futuro del desarrollo con capacidades de IA integradas. ServBay incorpora Ollama, permitiéndole ejecutar potentes Modelos de Lenguaje Grandes (LLMs) como Llama 3, Mistral y Gemma localmente. Construya y pruebe aplicaciones impulsadas por IA con cero latencia y total privacidad de datos, todo gestionado a través de la interfaz intuitiva de ServBay.

![AI Development with Ollama](/images/ai.png)

### Búsqueda Potente con Typesense y Meilisearch

Potencie sus aplicaciones con motores de búsqueda modernos y rápidos. ServBay incluye tanto **Typesense** como **Meilisearch**, dos de las principales soluciones de búsqueda de código abierto que puede agregar a sus proyectos con un solo clic.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Almacenamiento de Objetos con MinIO

Gestione datos no estructurados con facilidad utilizando MinIO, un servicio de almacenamiento de objetos de alto rendimiento compatible con S3, ahora incluido con ServBay. Es perfecto para almacenar todo, desde copias de seguridad y registros hasta archivos multimedia y artefactos, proporcionando una solución de almacenamiento robusta para sus necesidades de desarrollo local.

![Object Storage with MinIO](/images/minio.png)

### Servicios de Dominio y DNS

Los dominios son un recurso consumible en el ciclo de vida del desarrollo web. ServBay incluye un servidor DNS, permitiendo a los desarrolladores usar dominios y TLDs no existentes sin registro, e incluso emitir certificados SSL para ellos. Esto no solo ahorra a los desarrolladores costos significativos, sino que también mejora la seguridad: los hackers no pueden acceder a un dominio no existente. Además, ServBay proporciona una interfaz gráfica para gestionar cómodamente su archivo hosts.

![Domain and DNS Services](/images/dns.png)

### Gestión de PKI y Certificados SSL

ServBay proporciona un sistema PKI. Los desarrolladores pueden crear su propia Autoridad de Certificación (CA) y emitir certificados SSL, lo cual es particularmente útil para pequeños equipos de desarrollo. Usando una CA privada, los pequeños equipos pueden cifrar la transmisión de datos y establecer confianza interna en su entorno de desarrollo. Esto se aplica no solo a los servicios web, sino también a las bases de datos, SMTP y otros servicios. ServBay incluso admite certificados S/MIME para el cifrado de correo electrónico, certificados de firma de código y certificados de firma de documentos PDF.

Por supuesto, ServBay también admite la obtención y renovación automática de certificados SSL de Let's Encrypt, ZeroSSL y Google Trust Services a través de ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Servidor de Correo

¿Quiere usar SMTP/POP3 en su desarrollo local? ¡No hay problema! ServBay incluye un servidor de correo integrado con **Mailpit** para pruebas de correo electrónico locales. Integrado con el sistema PKI, el servidor de correo admite STARTTLS y SSL/TLS sin configuración. ¿Necesita retransmitir correo a un servidor SMTP externo? El servidor de correo de ServBay admite la retransmisión. También admitimos SpamAssassin, lo que le permite puntuar cada correo electrónico saliente y reducir las posibilidades de que sea marcado como spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Proxy Inverso

¿Necesita compartir temporalmente su proyecto con usuarios? ¿Quiere alojar un servidor en casa pero no tiene una dirección IP pública? ServBay lo tiene cubierto. Admite **ngrok, frp, Cloudflared y Pinggy** para compartir rápidamente su sitio web públicamente.

![Reverse Proxy](/images/tunnel.png)

### Entornos de Ejecución a Nivel de Proyecto

ServBay ofrece configuración de entorno de ejecución a nivel de proyecto. Puede configurar y bloquear las versiones de PHP y Node.js requeridas para diferentes proyectos, haciendo que el desarrollo de su proyecto sea más flexible y controlable.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Potente Copia de Seguridad y Restauración

La seguridad de los datos y la recuperación del entorno son cruciales. ServBay cuenta con un sistema completo de copia de seguridad y restauración para darle tranquilidad.
*   **Copias de Seguridad con un Clic y Programadas**: Configure copias de seguridad automáticas y programadas, o active copias de seguridad manuales de sus bases de datos, archivos de sitios web, configuraciones de servicios y certificados SSL.
*   **Restauración y Migración Fáciles**: Restaure rápidamente su entorno a un estado anterior en caso de un problema, o use las copias de seguridad para migrar fácilmente toda su configuración de ServBay a una nueva máquina.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Paquetes Incluidos

ServBay viene con una variedad de paquetes esenciales para agilizar su proceso de desarrollo:

-   **Servidores Web**: Caddy, Nginx, Apache
-   **Lenguajes de Programación**: PHP (5.6 a 8.5-Alpha), Node.js (12 a 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **Bases de Datos SQL**: MySQL (5.1 a 9.3), MariaDB (10.4 a 12.0), PostgreSQL (10 a 17)
-   **Bases de Datos NoSQL**: Redis, Memcached, MongoDB (5.0 a 8.0) y MongoSH 2
-   **IA / LLM**: Ollama
-   **Motores de Búsqueda**: Typesense, Meilisearch
-   **Almacenamiento de Objetos**: MinIO
-   **DNS**: Servidor DNS incorporado (dnsmasq)
-   **Correo Electrónico**: Mailpit para pruebas de correo electrónico locales
-   **Túnel/Proxy Inverso**: Cloudflared, frp, Ngrok, Pinggy
-   **Otras Herramientas**: phpMyAdmin, Adminer, Composer, y más

![ServBay Bundled Packages](/images/services.png)

## Instalación

ServBay está disponible tanto para macOS como para Windows.

### macOS

1.  Descargue la última versión de ServBay para macOS desde el [sitio web oficial](https://www.servbay.com/download).
2.  Abra el instalador y siga las indicaciones para completar la instalación.
3.  Inicie ServBay y siga el asistente de configuración inicial para configurarlo.

### Windows

1.  Descargue la última versión de ServBay para Windows desde la [página de descarga oficial](https://www.servbay.com/download) o directamente desde el [repositorio de lanzamientos de Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  Ejecute el instalador y siga las instrucciones en pantalla.
3.  Inicie ServBay para comenzar a configurar su entorno de desarrollo local.

## Documentación

Para obtener documentación detallada y guías de uso, visite el [Centro de Documentación de ServBay](https://support.servbay.com).

## Soporte

Si encuentra algún problema al usar ServBay, puede obtener soporte a través de los siguientes canales:

-   [Centro de Ayuda](https://support.servbay.com)
-   [Comunidad de Discord](https://talk.servbay.com)
-   [Comunidad de Telegram](https://telegram.servbay.dev)
-   [Comunidad de WhatsApp](https://wa.servbay.dev)
-   [Comunidad de WeChat](https://wechat-group.servbay.dev)
-   [Enviar un Problema](https://github.com/ServBay/ServBay/issues)

## Comunidad

Únase a nuestra comunidad para intercambiar experiencias con otros desarrolladores y obtener las últimas actualizaciones:

-   [Blog de ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

¡Gracias por usar ServBay! Si tiene alguna pregunta o sugerencia, no dude en contactarnos.
