Чат-бот платформа @robosellerbot
=====================
Сейчас платформа это MVP (minimum viable product) — это минимально жизнеспособный продукт, который позволяет получить осмысленную обратную связь от пользователей и предоставить понятный ограниченный функционал в экосистеме Telegram.
***Интерфейс управления из приложений или web версии месенджера.***

Пошаговое руководство
-----------------------------------

### Регистрация в платформе, вводные данные:

**Фамилия Имя**
указанные данные мы используем для внутреннего учета клиентов платформы. Потребуется в случае восстановления доступа к платформе.

**Мобильный телефон**
мы планируем его использовать для сервисных функций платформы, таких оповещений как окончание срока действия пакетов доступа, массовое удаление контента в боте, чрезвычайные обстоятельства разбили/сломался телефон, его украли... Вы можете позвонить с зарегистрированого номера и заблокировать бота.

**Электронный адрес (E-mail)**
этот адрес будет использован для входа на Web версию платформы для управления роботами, выгрузки статистик и тонких настроек.

![Пример регистрации](https://telegra.ph/file/c5bfcf269b3b446d44978.png)

Регистрация [здесь](https://tele.click/robosellerbot)

### Регистрация имени чат-бота, первичные настройки:

Подумайте над тем как будет называться ваш бот имя на нужном вам языке, псевдоним на латинице либо транскрипции.
**Имя**
может отражать характер вашей деятельности, позволяет однозначно идентифицировать вас в ленте с чатами. Например: „Служба заботы RoboSeller“ или „SMM manager HELP“. Так как Телеграм международный вы можете сделать бота на английском языке и продвигать на весь мир!

**Псевдоним**
то слово или словосочетание (без пробелов) с приставкой bot по которому вас смогут найти ваши клиенты, может быть все что угодно латинскими буквами или на английском языке. Рекомендуем использовать ключевые слова для вашего бизнеса.

**Картинка**
аватар/фото профиля вашего бота, то что будет выделять его среди других чатов в ленте. Чем индивидуальнее и ярче сделаете, тем заметнее он будет.

**Приветствие бота**
тут, мы не рекомендуем сильно раскрывать то что выполняет ваш бот, только в общих чертах. Лучше предложить пользователю „нажать start или начать“ и маленькое отступление почему. Когда пользователь нажал старт бот автоматически получает id пользователя и сможет в последствии напрямую обратится к пользователю.

**Описание бота**
а вот тут нужно раскрыть суть бота, указать УТП, привести доводы чем ваш бот может быть полезен. Ваши контакты. Когда вы делитесь ссылкой в соц сети именно эта информация подгружается автоматически с аватаркой. Размер поля ограничен поэтому пишите самую соль.

![Как зарегистрировать чат-бота](https://telegra.ph/file/44e64a4247b8249d3f055.png)

Посмотрите, мы специально записали [Видео инструкцию](https://youtu.be/wsOoPOqIFrs)


### Подключение чат-бота к платформе, выбор тарифа:
Платформа предоставляется без оплаты! После того как вы добавили бота выберите пакет универсальный и нажмите подключить. После этого в вашем боте станут доступны следующие функции:

**Страницы**
место где вы можете рассказать о товаре/услуге или другом вашем продукте. Или просто разместить контактную информацию.
Посмотрите, мы специально записали [Видео инструкцию](https://youtu.be/ciBNh1A9QAI) 

**Коструктор форм**
мега крутая штука, которая присоединяется к страницам. Позволяет получать заявки в бота или менежерский чат. Имеет гибкие настройки и вы сможете создать практически любую форму.
Посмотрите, мы специально записали [Видео инструкцию](https://youtu.be/dW24qA4NAk0) 

**Публикатор**
основной функционал для ведения каналов и чатов. Одним ботом можно управлять несколькими ресурсами, кстати они необязательно должны быть созданы с одного аккаунта. Отложенные публикации, периодические посты, рекламные посты, реакции, опросы, кнопки-ссылки - уже присутствуют.
Посмотрите, мы специально записали [Видео инструкцию](https://youtu.be/k2IJqNdZHDE) 

### Команды для управления чат-ботом в чатах и каналах.
Рабочие проверенные команды, которыми можно уверенно пользоваться.

***@namebot - это имя Вашего бота.***

**Активация в чате для менеджеров:**
1) Добавьте Вашего бота в чат с менеджерами, сделайте его админом, напишите любое сообщение.
2) Активируйте бота в чате для менеджеров.
	a) для включения бота в чате с вашими менеджерами введите команду активации бота в чате  /manager @namebot
	b) для ВЫключения бота /nomanager @namebot

**Активация чат-бота в чатах:**
1) Добавьте Вашего бота в админы чата с правами доступа публиковать сообщения.
2) введите команду активации бота в чате  /publisher @bot_name - для включения, /nopublisher @bot_name - для выключения.

**Экспериментальные команды**
Команды для вновь разрабатываемых функций.

### Внимание!!!
Если вы уже подключали бота в другой системе, он работать не будет, требуется предварительно его отключить от старой системы и обновить токен в BotFather.
