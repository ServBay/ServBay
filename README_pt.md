# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## Introdução

Pare de perder tempo gerenciando seu ambiente de desenvolvimento!

ServBay é uma ferramenta de gerenciamento de ambiente de desenvolvimento web local poderosa e abrangente, projetada para desenvolvedores web profissionais, agora disponível para **macOS e Windows**. O ServBay inclui suporte para uma variedade de linguagens de desenvolvimento, bancos de dados, servidores web, servidores de e-mail, servidores DNS e proxies reversos. Agora também possui capacidades de desenvolvimento de IA integradas com Ollama, armazenamento de objetos com MinIO, pesquisa poderosa com Typesense e Meilisearch, e um sistema de backup robusto. Tudo o que você precisa para o desenvolvimento web está aqui. Configure um ambiente de desenvolvimento local profissional em apenas 3 minutos.

![ServBay Dashboard](/images/dashboard.png)

## Recursos

### Gerenciamento de Múltiplos Sites

Gerenciando vários sites simultaneamente? O ServBay facilita. Configure e execute sem esforço vários sites em sua máquina local, cada um com suas próprias configurações, domínio e ambiente de desenvolvimento exclusivos. A interface intuitiva do ServBay simplifica o processo, permitindo que você alterne rapidamente entre projetos e gerencie suas configurações sem setup complexo ou conflitos.

![Multi-site Management](/images/website.png)

### Servidores Web

O ServBay inclui os servidores web mais populares—**Caddy, NGINX e Apache**—com suporte para HTTP/3 e CORS. Ele também suporta domínios personalizados e configuração automática de SSL, eliminando a necessidade de comprar domínios e certificados SSL, economizando custos significativos durante o desenvolvimento.

![Web Servers](/images/web-servers.png)

### Linguagens de Desenvolvimento Web

O ServBay vem com uma vasta gama de linguagens de desenvolvimento, incluindo **PHP** (5.6-8.5), **Node.js** (12-24), **Python** (2.7, 3.5-3.14), **Go** (1.11-1.24), **Java** (OpenJDK 7-24), **Ruby** (2.4-3.4), **Rust**, e até **.NET** (2.0-10.0) & **Mono**. Os desenvolvedores podem alternar perfeitamente entre diferentes versões e usar versões diferentes para projetos diferentes. Essa imensa flexibilidade dá aos desenvolvedores grande confiança.

![Web Development Languages](/images/languages.png)

### Bancos de Dados

Bancos de dados são essenciais para o desenvolvimento web. O ServBay inclui **MySQL**, **MariaDB** e o cada vez mais popular **PostgreSQL**. Bancos de dados NoSQL também são cobertos, com **Redis**, **Memcached** e **MongoDB** prontos para uso imediato, sem necessidade de configuração. O ServBay também integra **phpMyAdmin** e **Adminer** para fácil gerenciamento de banco de dados.

![Databases](/images/databases.png)

### Desenvolvimento de IA com Ollama

Abrace o futuro do desenvolvimento com capacidades de IA integradas. O ServBay incorpora o Ollama, permitindo que você execute poderosos Modelos de Linguagem Grandes (LLMs) como Llama 3, Mistral e Gemma localmente. Construa e teste aplicações orientadas por IA com latência zero e total privacidade de dados, tudo gerenciado através da interface intuitiva do ServBay.

![AI Development with Ollama](/images/ai.png)

### Pesquisa Poderosa com Typesense & Meilisearch

Potencialize suas aplicações com motores de busca modernos e rápidos. O ServBay inclui tanto **Typesense** quanto **Meilisearch**, duas das principais soluções de busca de código aberto que você pode adicionar aos seus projetos com um clique.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### Armazenamento de Objetos com MinIO

Gerencie dados não estruturados com facilidade usando o MinIO, um serviço de armazenamento de objetos de alto desempenho compatível com S3, agora incluído no ServBay. É perfeito para armazenar tudo, desde backups e logs até arquivos de mídia e artefatos, fornecendo uma solução de armazenamento robusta para suas necessidades de desenvolvimento local.

![Object Storage with MinIO](/images/minio.png)

### Serviços de Domínio e DNS

Domínios são um recurso consumível no ciclo de vida do desenvolvimento web. O ServBay inclui um servidor DNS, permitindo que os desenvolvedores usem domínios e TLDs inexistentes sem registro, e até mesmo emitam certificados SSL para eles. Isso não apenas economiza custos significativos para os desenvolvedores, mas também aumenta a segurança—hackers não podem acessar um domínio inexistente. Além disso, o ServBay fornece uma interface gráfica para gerenciar convenientemente seu arquivo hosts.

![Domain and DNS Services](/images/dns.png)

### Gerenciamento de PKI e Certificados SSL

O ServBay fornece um sistema PKI. Os desenvolvedores podem criar sua própria Autoridade de Certificação (CA) e emitir certificados SSL—o que é particularmente útil para pequenas equipes de desenvolvimento. Usando uma CA privada, pequenas equipes podem criptografar a transmissão de dados e estabelecer confiança interna em seu ambiente de desenvolvimento. Isso se aplica não apenas a serviços web, mas também a bancos de dados, SMTP e outros serviços. O ServBay ainda suporta certificados S/MIME para criptografia de e-mail, certificados de assinatura de código e certificados de assinatura de documentos PDF.

Claro, o ServBay também suporta a obtenção e renovação automática de certificados SSL da Let's Encrypt, ZeroSSL e Google Trust Services via ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### Servidor de E-mail

Quer usar SMTP/POP3 em seu desenvolvimento local? Sem problemas! O ServBay inclui um servidor de e-mail integrado com **Mailpit** para testes de e-mail locais. Integrado com o sistema PKI, o servidor de e-mail suporta STARTTLS e SSL/TLS sem configuração. Precisa retransmitir e-mails para um servidor SMTP externo? O servidor de e-mail do ServBay suporta retransmissão. Também suportamos o SpamAssassin, permitindo que você pontue cada e-mail de saída e reduza as chances de ser marcado como spam.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### Proxy Reverso

Precisa compartilhar temporariamente seu projeto com os usuários? Quer hospedar um servidor em casa, mas não tem um endereço IP público? O ServBay tem a solução. Ele suporta **ngrok, frp, Cloudflared e Pinggy** para compartilhar rapidamente seu site publicamente.

![Reverse Proxy](/images/tunnel.png)

### Ambientes de Execução em Nível de Projeto

O ServBay oferece configuração de ambiente de execução em nível de projeto. Você pode configurar e bloquear as versões necessárias de PHP и Node.js para diferentes projetos, tornando o desenvolvimento do seu projeto mais flexível e controlável.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### Backup e Restauração Poderosos

A segurança dos dados e a recuperação do ambiente são cruciais. O ServBay possui um sistema abrangente de backup e restauração para lhe dar tranquilidade.
*   **Backups com Um Clique e Agendados**: Configure backups automáticos e agendados ou acione backups manuais de seus bancos de dados, arquivos de sites, configurações de serviços e certificados SSL.
*   **Restauração e Migração Fáceis**: Restaure rapidamente seu ambiente para um estado anterior em caso de problema, ou use os backups para migrar facilmente toda a sua configuração do ServBay para uma nova máquina.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## Pacotes Incluídos

O ServBay vem com uma variedade de pacotes essenciais para agilizar seu processo de desenvolvimento:

-   **Servidores Web**: Caddy, Nginx, Apache
-   **Linguagens de Programação**: PHP (5.6 a 8.5-Alpha), Node.js (12 a 24), Python (2.7, 3.5-3.14), Golang (1.11-1.24), Java (OpenJDK 7-24), .NET (2.0-10.0), Mono (6.14), Ruby (2.4-3.4), Rust
-   **Bancos de Dados SQL**: MySQL (5.1 a 9.3), MariaDB (10.4 a 12.0), PostgreSQL (10 a 17)
-   **Bancos de Dados NoSQL**: Redis, Memcached, MongoDB (5.0 a 8.0) & MongoSH 2
-   **IA / LLM**: Ollama
-   **Motores de Busca**: Typesense, Meilisearch
-   **Armazenamento de Objetos**: MinIO
-   **DNS**: Servidor DNS integrado (dnsmasq)
-   **E-mail**: Mailpit para testes de e-mail locais
-   **Túnel/Proxy Reverso**: Cloudflared, frp, Ngrok, Pinggy
-   **Outras Ferramentas**: phpMyAdmin, Adminer, Composer, e mais

![ServBay Bundled Packages](/images/services.png)

## Instalação

O ServBay está disponível para macOS e Windows.

### macOS

1.  Baixe a versão mais recente do ServBay para macOS no [site oficial](https://www.servbay.com/download).
2.  Abra o instalador и siga as instruções para concluir a instalação.
3.  Inicie o ServBay e siga o assistente de configuração inicial para configurá-lo.

### Windows

1.  Baixe a versão mais recente do ServBay para Windows na [página de download oficial](https://www.servbay.com/download) ou diretamente do [repositório de lançamentos do Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  Execute o instalador e siga as instruções na tela.
3.  Inicie o ServBay para começar a configurar seu ambiente de desenvolvimento local.

## Documentação

Para documentação detalhada e guias de uso, visite o [Centro de Documentação do ServBay](https://support.servbay.com).

## Suporte

Se você encontrar algum problema ao usar o ServBay, pode obter suporte através dos seguintes canais:

-   [Central de Ajuda](https://support.servbay.com)
-   [Comunidade no Discord](https://talk.servbay.com)
-   [Comunidade no Telegram](https://telegram.servbay.dev)
-   [Comunidade no WhatsApp](https://wa.servbay.dev)
-   [Comunidade no WeChat](https://wechat-group.servbay.dev)
-   [Enviar um Problema](https://github.com/ServBay/ServBay/issues)

## Comunidade

Junte-se à nossa comunidade para trocar experiências com outros desenvolvedores e obter as últimas atualizações:

-   [Blog do ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

Obrigado por usar o ServBay! Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato conosco.