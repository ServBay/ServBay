# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![Logotipo da ServBay](/images/logo.png)

## Introdução

Pare de perder tempo gerenciando seu ambiente de desenvolvimento!

ServBay é uma [ferramenta poderosa e abrangente de gerenciamento de ambiente de desenvolvimento web local](https://www.servbay.com) projetada para desenvolvedores web profissionais. ServBay inclui suporte para uma variedade de linguagens de desenvolvimento, bancos de dados, servidores web, servidores de e-mail, servidores DNS, armazenamento de objetos, proxies reversos e até mesmo uma plataforma profissional de gerenciamento de certificados SSL. Tudo o que você precisa para desenvolvimento web está aqui. Configure um ambiente de desenvolvimento local profissional em apenas 3 minutos.

![Painel da ServBay](/images/dashboard.png)

## Recursos

### Gerenciamento multi-site

[Gerenciando múltiplos sites](https://support.servbay.com/basic-usage/websites/adding-first-website) simultaneamente? ServBay torna isso fácil. Configure e execute vários sites em sua máquina local sem esforço, cada um com suas próprias configurações exclusivas, domínio e ambiente de desenvolvimento. A interface intuitiva da ServBay simplifica o processo, permitindo que você alterne rapidamente entre projetos e gerencie suas configurações sem configurações complexas ou conflitos.

![Gerenciamento multi-site](/images/hosts.png)

### Servidores Web

ServBay inclui os [servidores web](https://www.servbay.com/features/web-server) mais populares, Caddy e NGINX, com suporte para HTTP/3 e CORS. Ele também suporta domínios personalizados e [configuração automática de SSL](https://support.servbay.com/basic-usage/websites/using-ssl-to-secure-website), eliminando a necessidade de comprar domínios e certificados SSL, economizando custos significativos durante o desenvolvimento.

![Servidores Web](/images/web-servers.png)

### Linguagens de Desenvolvimento Web

ServBay vem com [Node.js](https://www.servbay.com/features/nodejs) (versões 12-23) e [PHP](https://www.servbay.com/features/php) (versões 5.6-8.5), cobrindo as necessidades dos desenvolvedores ao longo do ciclo de vida do desenvolvimento web. Os desenvolvedores podem alternar perfeitamente entre diferentes versões e usar versões diferentes para projetos diferentes. Essa imensa flexibilidade dá aos desenvolvedores grande confiança. ServBay também inclui Python e Golang.

![Linguagens de Desenvolvimento Web](/images/languages.png)

### Bancos de Dados

[Bancos de dados](https://www.servbay.com/features/database) são essenciais para o desenvolvimento web. ServBay inclui [MySQL](https://support.servbay.com/database-management/getting-started/mysql-management-and-usage), [MariaDB](https://support.servbay.com/database-management/getting-started/mariadb-management-and-usage) e o cada vez mais popular [PostgreSQL](https://support.servbay.com/database-management/getting-started/postgresql-management-and-usage). Bancos de dados NoSQL também são cobertos, com [Redis](https://support.servbay.com/database-management/getting-started/redis-management-and-usage), [Memcached](https://support.servbay.com/database-management/getting-started/memcached-management-and-usage) e [MongoDB](https://www.servbay.com/features/database) prontos para usar, sem necessidade de configuração. ServBay também integra [phpMyAdmin](https://support.servbay.com/database-management/management/using-phpmyadmin-to-manage-database) e [Adminer](https://support.servbay.com/database-management/management/using-adminer-to-manage-database) para facilitar o gerenciamento do banco de dados.

![Bancos de Dados](/images/databases.png)

### Serviços de Domínio e DNS

[Domínios](https://www.servbay.com/features/dns-server) são um recurso consumível no ciclo de vida do desenvolvimento web. ServBay inclui um [servidor DNS](https://www.servbay.com/features/dns-server), permitindo que os desenvolvedores usem domínios e TLDs inexistentes sem registro e até mesmo emitam certificados SSL para eles. Isso não apenas economiza custos significativos para os desenvolvedores, mas também aumenta a segurança - hackers não podem acessar um domínio inexistente. Além disso, ServBay fornece uma interface gráfica para gerenciar convenientemente seu arquivo /etc/hosts.

![Serviços de Domínio e DNS](/images/dns.png)

### Gerenciamento de Certificados PKI e SSL

ServBay fornece um [sistema PKI](https://www.servbay.com/features/ssl). Os desenvolvedores podem criar sua própria Autoridade Certificadora (CA) e emitir certificados SSL - particularmente útil para pequenas equipes de desenvolvimento. Usando uma [CA privada](https://support.servbay.com/basic-usage/ssl/local-ssl-root-certificate-management), pequenas equipes podem criptografar a transmissão de dados e estabelecer confiança interna em seu ambiente de desenvolvimento. Isso se aplica não apenas a serviços web, mas também a bancos de dados, SMTP e outros serviços. ServBay ainda suporta [certificados S/MIME](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-smime-email-certificate) para criptografia de e-mail, [certificados de assinatura de código](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-code-sining-certificate) e [certificados de assinatura de documento PDF](https://support.servbay.com/basic-usage/ssl/how-to-apply-for-and-use-document-signing-certificate).

Claro, ServBay também suporta a obtenção e renovação automática de certificados SSL do Let's Encrypt, ZeroSSL e Google Trust Services via [ACME](https://support.servbay.com/basic-usage/ssl/using-acme-to-issue-ssl-certificate).

![Gerenciamento de Certificados PKI e SSL](/images/ssl-pki.png)

### Servidor de E-mail

Quer usar SMTP/POP3 em seu desenvolvimento local? Sem problemas! ServBay inclui um [servidor de e-mail embutido](https://www.servbay.com/features/email-server). Integrado ao sistema PKI, o servidor de e-mail suporta [STARTTLS e SSL/TLS](https://support.servbay.com/advanced-settings/modify-configurations/modify-mailpit-settings) sem configuração. Precisa retransmitir e-mail para um [servidor SMTP](https://www.servbay.com/features/email-server) externo? O servidor de e-mail da ServBay suporta retransmissão. Também suportamos o SpamAssassin, permitindo que você pontue cada e-mail de saída e reduza as chances de ele ser marcado como spam.

![Servidor de E-mail](/images/email-server.png)

![Webmail do Servidor de E-mail](/images/email-server-webmail.png)

### Proxy Reverso

Precisa compartilhar seu projeto temporariamente com os usuários? Quer hospedar um servidor em casa, mas não tem um endereço IP público? ServBay te cobre. Ele suporta [ngrok](https://support.servbay.com/advanced-settings/how-to-use-ngrok), frp e Cloudflared para compartilhar seu site publicamente com rapidez. Não confia em serviços de terceiros? ServBay também fornece um serviço de proxy reverso público, perfeitamente integrado para compartilhamento com um clique.

*(Em breve)*

### Ambientes de Execução em Nível de Projeto

ServBay oferece configuração de ambiente de execução em nível de projeto. Você pode configurar e bloquear as versões necessárias de PHP e Node.js para diferentes projetos, tornando o desenvolvimento do seu projeto mais flexível e controlável.

![Ambientes de Execução em Nível de Projeto](/images/project-level-runtime.png)

### Limpo e Fácil de Fazer Backup

ServBay é uma instalação portátil, não deixando resíduos em seu sistema, ao contrário de ferramentas como Homebrew, que podem bagunçar seus arquivos de sistema. Você pode facilmente fazer backup de seus dados usando Time Machine ou rsync, garantindo a segurança dos dados.

![Limpo e Fácil de Fazer Backup](/images/easy-to-backup.png)

## Pacotes Inclusos

ServBay vem com uma variedade de pacotes essenciais para otimizar seu processo de desenvolvimento:

- **Servidores Web**: Caddy (2.8), Nginx (1.27) e Apache *(2.4, em breve)*
- **Linguagens de Programação**: PHP (do PHP 5.6 ao PHP 8.5-Dev), Node.js (do Node.js 12 ao Node.js 23), Python *(em breve)*, Golang *(em breve)*
- **Bancos de Dados SQL**: MySQL (do MySQL 5.1 ao MySQL 9.1), MariaDB (do MariaDB 10.4 ao MariaDB 11.8), PostgreSQL (do PostgreSQL 10 ao PostgreSQL 17)
- **Bancos de Dados NoSQL**: Redis (7.2), Memcached (1.6), MongoDB (do MongoDB 5.0 ao MongoDB 8.0) e MongoSH 2
- **DNS**: Servidor DNS embutido para desenvolvimento local (dnsmasq 2.9)
- **E-mail**: Mailpit para teste de e-mail local
- **Túnel/Proxy Reverso**: Cloudflared, frp, Ngrok, Oray HuaShengKe
- **Outras Ferramentas**: phpMyAdmin, Adminer e mais

![Pacotes Inclusos na ServBay](/images/services.png)

## Instalação

Siga estas etapas para instalar o ServBay:

1. Baixe a versão mais recente do ServBay no [site oficial](https://www.servbay.com).
2. Abra o instalador e siga as instruções para concluir a instalação.
3. Inicie o ServBay e siga o assistente de configuração inicial para configurá-lo.

## Documentação

Para obter documentação detalhada e guias de uso, visite o [Centro de Documentação da ServBay](https://support.servbay.com).

## Suporte

Se você encontrar algum problema ao usar o ServBay, pode obter suporte pelos seguintes canais:

- [Central de Ajuda](https://support.servbay.com)
- [Comunidade Discord](https://talk.servbay.com)
- [Comunidade Telegram](https://telegram.servbay.dev)
- [Comunidade WhatsApp](https://wa.servbay.dev)
- [Comunidade WeChat](https://wechat-group.servbay.dev)
- [Enviar um Problema](https://github.com/ServBay/ServBay/issues)

## Comunidade

Junte-se à nossa comunidade para trocar experiências com outros desenvolvedores e obter as atualizações mais recentes:

- [Blog da ServBay](https://blog.servbay.com)
- [Facebook](https://www.facebook.com/ServBay.Dev)
- [Twitter](https://twitter.com/ServBayDev)
- [YouTube](https://www.youtube.com/@ServBay)
- [Weibo](https://weibo.com/ServBay)
- [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)
---

Obrigado por usar o ServBay! Se você tiver alguma dúvida ou sugestão, não hesite em nos contatar.
