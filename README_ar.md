# ServBay

[English](/README.md) | [简体中文](/README_zh-CN.md) | [繁體中文](/README_zh-TW.md) | [Español](/README_es.md) | [العربية](/README_ar.md) | [Português](/README_pt.md) | [Русский](/README_ru.md) | [日本語](/README_ja.md) | [Deutsch](/README_de.md) | [Français](/README_fr.md) | [Tiếng Việt](/README_vi.md) | [Türkçe](/README_tr.md) | [Italiano](/README_it.md)

![ServBay Logo](/images/logo.png)

## مقدمة

توقف عن إضاعة الوقت في إدارة بيئة التطوير الخاصة بك!

ServBay هي أداة قوية وشاملة لإدارة بيئة تطوير الويب المحلية مصممة لمطوري الويب المحترفين، وهي متاحة الآن لكل من **macOS و Windows**. يتضمن ServBay دعمًا لمجموعة متنوعة من لغات التطوير، وقواعد البيانات، وخوادم الويب، وخوادم البريد، وخوادم DNS، والوكلاء العكسيين. يتميز الآن أيضًا بقدرات تطوير الذكاء الاصطناعي المدمجة مع Ollama، وتخزين الكائنات مع MinIO، والبحث القوي مع Typesense و Meilisearch، ونظام نسخ احتياطي قوي. كل ما تحتاجه لتطوير الويب موجود هنا. قم بإعداد بيئة تطوير محلية احترافية في 3 دقائق فقط.

![ServBay Dashboard](/images/dashboard.png)

## الميزات

### إدارة مواقع متعددة

هل تدير عدة مواقع ويب في وقت واحد؟ ServBay يجعل الأمر سهلاً. قم بتكوين وتشغيل العديد من مواقع الويب على جهازك المحلي بسهولة، لكل منها إعداداته الفريدة ونطاقه وبيئة التطوير الخاصة به. واجهة ServBay البديهية تبسط العملية، مما يتيح لك التبديل بسرعة بين المشاريع وإدارة تكويناتها دون إعداد معقد أو تعارضات.

![Multi-site Management](/images/website.png)

### خوادم الويب

يتضمن ServBay أشهر خوادم الويب—**Caddy و NGINX و Apache**—مع دعم لـ HTTP/3 و CORS. كما أنه يدعم النطاقات المخصصة وتكوين SSL التلقائي، مما يلغي الحاجة إلى شراء النطاقات وشهادات SSL، ويوفر تكاليف كبيرة أثناء التطوير.

![Web Servers](/images/web-servers.png)

### لغات تطوير الويب

يأتي ServBay مع مجموعة واسعة من لغات التطوير، بما في ذلك **PHP** (5.6-8.5)، **Node.js** (12-24)، **Python** (2.7, 3.5-3.14)، **Go** (1.11-1.24)، **Java** (OpenJDK 7-24)، **Ruby** (2.4-3.4)، **Rust**، وحتى **.NET** (2.0-10.0) و **Mono**. يمكن للمطورين التبديل بسلاسة بين الإصدارات المختلفة واستخدام إصدارات مختلفة لمشاريع مختلفة. هذه المرونة الهائلة تمنح المطورين ثقة قوية.

![Web Development Languages](/images/languages.png)

### قواعد البيانات

قواعد البيانات ضرورية لتطوير الويب. يتضمن ServBay **MySQL** و **MariaDB** و **PostgreSQL** الذي يزداد شعبية. كما يتم تغطية قواعد بيانات NoSQL، مع **Redis** و **Memcached** و **MongoDB** الجاهزة للاستخدام فورًا، دون الحاجة إلى تكوين. يدمج ServBay أيضًا **phpMyAdmin** و **Adminer** لإدارة قواعد البيانات بسهولة.

![Databases](/images/databases.png)

### تطوير الذكاء الاصطناعي مع Ollama

احتضن مستقبل التطوير بقدرات الذكاء الاصطناعي المدمجة. يدمج ServBay Ollama، مما يتيح لك تشغيل نماذج لغوية كبيرة (LLMs) قوية مثل Llama 3 و Mistral و Gemma محليًا. قم ببناء واختبار التطبيقات المدعومة بالذكاء الاصطناعي بزمن انتقال صفري وخصوصية كاملة للبيانات، كل ذلك تتم إدارته من خلال واجهة ServBay البديهية.

![AI Development with Ollama](/images/ai.png)

### بحث قوي مع Typesense و Meilisearch

قم بتزويد تطبيقاتك بمحركات بحث حديثة وسريعة. يتضمن ServBay كلاً من **Typesense** و **Meilisearch**، وهما من أبرز حلول البحث مفتوحة المصدر التي يمكنك إضافتها إلى مشاريعك بنقرة واحدة.

![Powerful Search with Typesense & Meilisearch](/images/search.png)

### تخزين الكائنات مع MinIO

قم بإدارة البيانات غير المهيكلة بسهولة باستخدام MinIO، وهي خدمة تخزين كائنات عالية الأداء ومتوافقة مع S3 مدرجة الآن مع ServBay. إنها مثالية لتخزين كل شيء من النسخ الاحتياطية والسجلات إلى ملفات الوسائط والمنتجات، مما يوفر حلاً تخزينًا قويًا لاحتياجات التطوير المحلية الخاصة بك.

![Object Storage with MinIO](/images/minio.png)

### خدمات النطاق و DNS

النطاقات هي مورد مستهلك في دورة حياة تطوير الويب. يتضمن ServBay خادم DNS، مما يسمح للمطورين باستخدام نطاقات و TLDs غير موجودة دون تسجيل، وحتى إصدار شهادات SSL لها. هذا لا يوفر على المطورين تكاليف كبيرة فحسب، بل يعزز أيضًا الأمان—لا يمكن للمتسللين الوصول إلى نطاق غير موجود. بالإضافة إلى ذلك، يوفر ServBay واجهة رسومية لإدارة ملف hosts الخاص بك بسهولة.

![Domain and DNS Services](/images/dns.png)

### إدارة PKI وشهادات SSL

يوفر ServBay نظام PKI. يمكن للمطورين إنشاء هيئة إصدار شهادات (CA) خاصة بهم وإصدار شهادات SSL—وهو أمر مفيد بشكل خاص لفرق التطوير الصغيرة. باستخدام CA خاص، يمكن للفرق الصغيرة تشفير نقل البيانات وإنشاء ثقة داخلية في بيئة التطوير الخاصة بهم. لا ينطبق هذا على خدمات الويب فحسب، بل ينطبق أيضًا على قواعد البيانات و SMTP والخدمات الأخرى. يدعم ServBay حتى شهادات S/MIME لتشفير البريد الإلكتروني وشهادات توقيع التعليمات البرمجية وشهادات توقيع مستندات PDF.

بالطبع، يدعم ServBay أيضًا الحصول على شهادات SSL وتجديدها تلقائيًا من Let's Encrypt و ZeroSSL و Google Trust Services عبر ACME.

![PKI and SSL Certificate Management](/images/ssl-pki.png)

### خادم البريد

هل تريد استخدام SMTP/POP3 في تطويرك المحلي؟ لا مشكلة! يتضمن ServBay خادم بريد مدمجًا مع **Mailpit** لاختبار البريد الإلكتروني المحلي. متكامل مع نظام PKI، يدعم خادم البريد STARTTLS و SSL/TLS دون تكوين. هل تحتاج إلى ترحيل البريد إلى خادم SMTP خارجي؟ يدعم خادم بريد ServBay الترحيل. ندعم أيضًا SpamAssassin، مما يتيح لك تقييم كل بريد إلكتروني صادر وتقليل فرص تمييزه كبريد عشوائي.

![Mail Server](/images/email-server.png)

![Mail Server Webmail](/images/email-server-webmail.png)

### الوكيل العكسي

هل تحتاج إلى مشاركة مشروعك مؤقتًا مع المستخدمين؟ هل تريد استضافة خادم في المنزل ولكن ليس لديك عنوان IP عام؟ ServBay يغطي احتياجاتك. إنه يدعم **ngrok و frp و Cloudflared و Pinggy** لمشاركة موقع الويب الخاص بك بسرعة بشكل عام.

![Reverse Proxy](/images/tunnel.png)

### بيئات التشغيل على مستوى المشروع

يقدم ServBay تكوين بيئة التشغيل على مستوى المشروع. يمكنك تكوين وقفل إصدارات PHP و Node.js المطلوبة لمشاريع مختلفة، مما يجعل تطوير مشروعك أكثر مرونة وقابلية للتحكم.

![Project-Level Runtime Environments](/images/project-level-runtime.png)

### نسخ احتياطي واستعادة قوية

أمان البيانات واستعادة البيئة أمران حاسمان. يتميز ServBay بنظام نسخ احتياطي واستعادة شامل ليمنحك راحة البال.
*   **نسخ احتياطي بنقرة واحدة ومجدول**: قم بتكوين نسخ احتياطية تلقائية ومجدولة، أو قم بتشغيل نسخ احتياطية يدوية لقواعد البيانات وملفات مواقع الويب وتكوينات الخدمة وشهادات SSL.
*   **استعادة وترحيل سهلان**: قم باستعادة بيئتك بسرعة إلى حالة سابقة في حالة حدوث مشكلة، أو استخدم النسخ الاحتياطية لترحيل إعداد ServBay بالكامل بسهولة إلى جهاز جديد.

![Clean and Easy to Back Up](/images/easy-to-backup.png)

![Clean and Easy to Back Up](/images/easy-to-backup-2.png)

## الحزم المضمنة

يأتي ServBay مع مجموعة متنوعة من الحزم الأساسية لتبسيط عملية التطوير الخاصة بك:

-   **خوادم الويب**: Caddy, Nginx, Apache
-   **لغات البرمجة**: PHP (5.6 إلى 8.5-Alpha)، Node.js (12 إلى 24)، Python (2.7, 3.5-3.14)، Golang (1.11-1.24)، Java (OpenJDK 7-24)، .NET (2.0-10.0)، Mono (6.14)، Ruby (2.4-3.4)، Rust
-   **قواعد بيانات SQL**: MySQL (5.1 إلى 9.3)، MariaDB (10.4 إلى 12.0)، PostgreSQL (10 إلى 17)
-   **قواعد بيانات NoSQL**: Redis, Memcached, MongoDB (5.0 إلى 8.0) و MongoSH 2
-   **الذكاء الاصطناعي / LLM**: Ollama
-   **محركات البحث**: Typesense, Meilisearch
-   **تخزين الكائنات**: MinIO
-   **DNS**: خادم DNS مدمج (dnsmasq)
-   **البريد الإلكتروني**: Mailpit لاختبار البريد الإلكتروني المحلي
-   **النفق/الوكيل العكسي**: Cloudflared, frp, Ngrok, Pinggy
-   **أدوات أخرى**: phpMyAdmin, Adminer, Composer, والمزيد

![ServBay Bundled Packages](/images/services.png)

## التثبيت

ServBay متاح لكل من macOS و Windows.

### macOS

1.  قم بتنزيل أحدث إصدار من ServBay لـ macOS من [الموقع الرسمي](https://www.servbay.com/download).
2.  افتح المثبت واتبع التعليمات لإكمال التثبيت.
3.  قم بتشغيل ServBay واتبع معالج الإعداد الأولي لتكوينه.

### Windows

1.  قم بتنزيل أحدث إصدار من ServBay لـ Windows من [صفحة التنزيل الرسمية](https://www.servbay.com/download) أو مباشرة من [مستودع إصدارات Windows](https://github.com/ServBay/ServBay-Windows-Release).
2.  قم بتشغيل المثبت واتبع التعليمات التي تظهر على الشاشة.
3.  قم بتشغيل ServBay لبدء تكوين بيئة التطوير المحلية الخاصة بك.

## التوثيق

للحصول على توثيق مفصل وأدلة استخدام، قم بزيارة [مركز توثيق ServBay](https://support.servbay.com).

## الدعم

إذا واجهت أي مشاكل أثناء استخدام ServBay، يمكنك الحصول على الدعم من خلال القنوات التالية:

-   [مركز المساعدة](https://support.servbay.com)
-   [مجتمع Discord](https://talk.servbay.com)
-   [مجتمع Telegram](https://telegram.servbay.dev)
-   [مجتمع WhatsApp](https://wa.servbay.dev)
-   [مجتمع WeChat](https://wechat-group.servbay.dev)
-   [إرسال مشكلة](https://github.com/ServBay/ServBay/issues)

## المجتمع

انضم إلى مجتمعنا لتبادل الخبرات مع المطورين الآخرين والحصول على آخر التحديثات:

-   [مدونة ServBay](https://blog.servbay.com)
-   [Facebook](https://www.facebook.com/ServBay.Dev)
-   [Twitter (X)](https://twitter.com/ServBayDev)
-   [YouTube](https://www.youtube.com/@ServBay)
-   [Weibo](https://weibo.com/ServBay)
-   [WeChat](https://mp.weixin.qq.com/s/CC9-1YagpZYmUxg01UJHTw)

---

شكرًا لاستخدامك ServBay! إذا كان لديك أي أسئلة أو اقتراحات، فلا تتردد في التواصل معنا.