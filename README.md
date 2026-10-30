<p align="center"><img src="screenshots/icon.png" width="96" alt="Значок ElseConf"></p>

# ElseConf

<p align="center">
  <a href="screenshots/windows-video.mp4"><img src="screenshots/windows-video.webp" alt="Ролик: чаты, звонки и встречи в клиенте Windows"></a>
  <br>
  <a href="screenshots/windows-video.mp4">Ролик со звуком</a>
</p>

> [!IMPORTANT]
> **Установщик Windows прерывается ошибкой 4551?** «Политика управления приложениями
> заблокировала этот файл» — так срабатывает Smart App Control в Windows 11: у установщика нет
> подписи разработчика. Откройте свойства скачанного установщика, внизу вкладки «Общие» поставьте
> галочку «Разблокировать», нажмите «ОК» и запустите его снова. Не помогло — поставьте ElseConf
> [из Microsoft Store](https://apps.microsoft.com/detail/9NZ0MQ87265F): пакет из Store подписан, и Windows его не останавливает.
>
> Не хотите ставить из Store — выключите Smart App Control: откройте «Безопасность Windows» →
> «Управление приложениями и браузером» → параметры службы «Интеллектуальное управление
> приложениями» и выключите её. В Windows 11 24H2 и 25H2 с обновлениями от апреля 2026 года
> защиту включают обратно там же; без этих обновлений её возвращает только переустановка Windows,
> о чём система предупредит при выключении. С включённой защитой ElseConf, поставленный
> установщиком, снова не запустится.

Корпоративный мессенджер с чатами, звонками и встречами: нативные клиенты для Windows, macOS,
Linux, iPhone и Android на общем ядре. Работает с сервером платформы вашей организации — под той же
учётной записью, с теми же чатами, контактами и встречами, что и штатный клиент платформы.

<p align="center">
  <a href="https://github.com/poznik/elseconf-pub/releases/download/v6.9.307/ElseConf-6.9.307-setup.exe"><img src="screenshots/download-windows.png" width="250" alt="Скачать ElseConf 6.9.307 для Windows"></a>
  &nbsp;
  <a href="https://apps.microsoft.com/detail/9NZ0MQ87265F"><img src="screenshots/download-store.png" width="250" alt="Установить ElseConf из Microsoft Store"></a>
  &nbsp;
  <a href="https://github.com/poznik/elseconf-pub/releases/download/v6.9.301/ElseConf-6.9.301.msix"><img src="screenshots/download-store-package.png" width="250" alt="Скачать пакет Store ElseConf 6.9.301"></a>
  <br><br>
  <a href="https://github.com/poznik/elseconf-pub/releases/download/v6.9.303/ElseConf-6.9.303.dmg"><img src="screenshots/download-macos.png" width="250" alt="Скачать ElseConf 6.9.303 для macOS"></a>
  &nbsp;
  <a href="https://github.com/poznik/elseconf-pub/releases/download/v6.9.279/ElseConf-6.9.279.apk"><img src="screenshots/download-android.png" width="250" alt="Скачать ElseConf 6.9.279 для Android"></a>
  &nbsp;
  <a href="https://github.com/poznik/elseconf-pub/releases/download/v6.9.289/elseconf_6.9.289_amd64.deb"><img src="screenshots/download-linux.png" width="250" alt="Скачать ElseConf 6.9.289 для Linux"></a>
  <br>
  <sub>Windows: установщик — версия 6.9.307, Store и пакет Store — 6.9.301 · macOS — версия 6.9.303 · Android — версия 6.9.279 · Linux (Ubuntu 22.04 и 24.04) — версия 6.9.289</sub>
</p>

Для Windows — три варианта:

- **Установщик** — самая свежая версия, с последними правками. Он не подписан: Smart App Control в
  Windows 11 может его остановить — тогда файл нужно разблокировать или выключить защиту, как
  сказано в рамке в начале страницы. В закрытых системах у него могут блокироваться микрофон и камера.
- **Microsoft Store** — версия, подписанная Microsoft: микрофон и камера не блокируются и в закрытых
  системах. Каждую версию Store проверяет перед публикацией, поэтому она может отставать от
  установщика.
- **Пакет Store** — та же версия из Store, только скачанная заранее: на случай, если в Windows нет
  Store, например в LTSC. Как поставить — в разделе [«Установка на Windows»](#установка-на-windows).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/windows-chats-dark.png">
  <img src="screenshots/windows-chats.png" alt="Чаты в клиенте Windows">
</picture>

## Что умеет

### Чаты

- Личная переписка и группы, «Избранное» для заметок себе.
- Ответы с цитатой, пересылка, правка и удаление сообщений, упоминания, реакции и эмодзи.
- Файлы и картинки в обе стороны, просмотр картинок поверх окна, медиа и файлы беседы списком.
- Папки «Личные», «Группы», «Непрочитанные», «Архив» и свои папки; закрепление бесед, «отметить
  непрочитанной», «отметить всё прочитанным».
- Отметки доставки и прочтения, «печатает…», поиск людей и чатов.
- Группы: создание, участники и роли, права, картинка и название, передача владения, очистка и
  удаление.

### Звонки

- Звонки один на один: входящие и исходящие, журнал звонков, пропущенные с уведомлением.
- В окне звонка — камера, показ экрана и чат с собеседником.
- К разговору можно добавить людей — звонок продолжится конференцией.
- Звонок, принятый на другом вашем устройстве, не остаётся пропущенным.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/windows-call-dark.png">
  <img src="screenshots/windows-call.png" alt="Звонок в клиенте Windows">
</picture>

### Встречи

- Вход по ссылке из приглашения или по номеру — и на своём сервере, и гостем на чужом.
- «Сегодня в календаре»: встречи из Outlook с кнопкой «Войти», а когда встреча началась без вас —
  окно с «Подключиться».
- Окно встречи: видео участников, своя камера и показ экрана, список участников, чат встречи,
  плашка «Говорит», мини-окно поверх остальных окон.
- Свои встречи: создать сейчас, по расписанию или постоянной комнатой, изменить, начать, удалить.
- Запись встречи — на сервере или на свой компьютер, с согласием участников; раздел «Записи».
- История встреч по дням с карточкой: организатор, участники, чат.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/windows-meetings-dark.png">
  <img src="screenshots/windows-meetings.png" alt="Раздел «Встречи» в клиенте Windows">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/windows-meeting-dark.png">
  <img src="screenshots/windows-meeting.png" alt="Окно встречи в клиенте Windows">
</picture>

### Контакты

- «Мои контакты», все люди сервера и структура компании по подразделениям.
- Карточка человека: должность, отдел, почта, телефон, звонки с ним, кнопки «Написать» и
  «Позвонить».
- Статусы людей и свой статус: «в сети», «нет на месте», «не беспокоить» и свой текст — например,
  «в отпуске до 6 октября».

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/windows-contacts-dark.png">
  <img src="screenshots/windows-contacts.png" alt="Структура компании в клиенте Windows">
</picture>

### Вход и оформление

- Вход паролем или через SSO; со второго запуска пароль не нужен.
- Несколько сохранённых подключений — к разным серверам и учётным записям.
- С сервером — только HTTPS.
- Светлая и тёмная темы, фоны бесед.

## Платформы

| Платформа | Состояние | Требования |
|---|---|---|
| Windows | Установщик и пакет `.msix` для Windows без Store — в [Releases](https://github.com/poznik/elseconf-pub/releases) или [Microsoft Store](https://apps.microsoft.com/detail/9NZ0MQ87265F) | Windows 10 1809 и новее, x64 |
| macOS | Образ установки — в [Releases](https://github.com/poznik/elseconf-pub/releases) | macOS 15 и новее, Apple Silicon |
| Linux | Пакет [`elseconf_6.9.289_amd64.deb`](https://github.com/poznik/elseconf-pub/releases/download/v6.9.289/elseconf_6.9.289_amd64.deb), установка: `sudo apt install ./elseconf_6.9.289_amd64.deb` | Ubuntu Desktop 22.04 и 24.04, x86-64 |
| Терминальный клиент | Один файл без окна для сервера и NAS — в [Releases](https://github.com/poznik/elseconf-pub/releases): вход, туннель между своими устройствами, лента переписки в папку | Linux x86-64 и ARM64, Synology DSM 7 |
| iPhone | В разработке, готовых сборок здесь пока нет | iOS 26 и новее |
| Android | Пакет `.apk` — в [Releases](https://github.com/poznik/elseconf-pub/releases) | Android 10 и новее, arm64 и x86-64 |

Набор возможностей у клиентов различается: полнее всего — клиент Windows, по нему и составлен
список выше.

### macOS

![Чаты в клиенте macOS](screenshots/macos-chats.png)

![Раздел «Встречи» в клиенте macOS](screenshots/macos-meetings.png)

![Окно встречи в клиенте macOS](screenshots/macos-meeting.png)

### iPhone

![Чаты в клиенте iPhone](screenshots/iphone-chats.jpg)

![Звонок и встреча в клиенте iPhone](screenshots/iphone-calls.jpg)

## Установка на Windows

1. Скачайте `ElseConf-<версия>-setup.exe` по ссылке вверху страницы или из
   [Releases](https://github.com/poznik/elseconf-pub/releases) и запустите.
2. Укажите адрес сервера, имя и пароль — или войдите через SSO.

- Права администратора не нужны: установщик ставит клиент в `%LOCALAPPDATA%\Programs\ElseConf`.
- Обновление — с версии 6.9.158 клиент, поставленный установщиком, обновляется сам: найдя новую
  версию, скачивает её и показывает синюю кнопку над шестерёнкой, щелчок ставит её и перезапускает
  клиент. Выбор — «Настройки → Общие → Обновления». Версии до 6.9.158 обновляет тот же установщик
  поверх прежней версии; данные остаются.
- Без WebView2 Runtime не откроются встречи по ссылке и вход через SSO.
- Тихая установка: `ElseConf-<версия>-setup.exe /VERYSILENT /SUPPRESSMSGBOXES`.

Установщик не запускается или установка прерывается — поставьте ElseConf
[из Microsoft Store](https://apps.microsoft.com/detail/9NZ0MQ87265F): нажмите «Установить». В поиске Store приложения нет, оно
открывается только по этой ссылке.

Нет Microsoft Store — например, в Windows LTSC — скачайте из
[Releases](https://github.com/poznik/elseconf-pub/releases) пакет `ElseConf-<версия>.msix`: это
тот же пакет из Store, подписанный Microsoft. Поставьте его из PowerShell, права администратора не
нужны:

```powershell
Add-AppxPackage -Path "$env:USERPROFILE\Downloads\ElseConf-6.9.301.msix"
```

Проверено на Windows 10 LTSC 2019: работают звонки, видео, звук и показ экрана. Клиент из пакета
сам не обновляется: новую версию ставят так же, поверх прежней, данные остаются.

Что делает каждый параметр клиента — в [описании настроек](SETTINGS.md).

## Установка на macOS

1. Скачайте `ElseConf-<версия>.dmg` по ссылке вверху страницы или из
   [Releases](https://github.com/poznik/elseconf-pub/releases), откройте и перетащите ElseConf в папку «Программы».
2. Запустите ElseConf. Образ не нотаризован, поэтому первый запуск macOS остановит: откройте
   «Системные настройки» → «Конфиденциальность и безопасность» и нажмите «Всё равно открыть».
3. Укажите адрес сервера, имя и пароль — или войдите через SSO.

- Обновление — с версии 6.9.157 ElseConf из папки «Программы» обновляется сам: найдя новую версию,
  скачивает её и показывает синюю кнопку над кнопками папок и настроек, щелчок ставит её и
  перезапускает клиент. Выбор — «Настройки → Общие → Обновления». Версии до 6.9.157 обновляют,
  перетащив новую поверх прежней; данные остаются.

## Установка на Android

1. Скачайте `ElseConf-<версия>.apk` на телефон по ссылке вверху страницы или из
   [Releases](https://github.com/poznik/elseconf-pub/releases).
2. Откройте скачанный файл. Android спросит, можно ли браузеру или файловому менеджеру ставить
   приложения, — разрешите и нажмите «Установить». Пакет не из Google Play, поэтому Play Защита может
   предупредить о неизвестном разработчике: «Подробнее» → «Всё равно установить».
3. Укажите адрес сервера, имя и пароль — или войдите через SSO.

- Обновление — новый пакет ставят тем же путём поверх прежнего; данные остаются. Сам клиент на
  Android пока не обновляется.
- Ссылку на встречу из браузера или почты откройте через «Поделиться» → ElseConf.
- Чтобы сообщения и звонки приходили в фоне на Xiaomi, Huawei и похожих телефонах, разрешите
  ElseConf автозапуск и снимите для него ограничения батареи.

## Лицензия

ElseConf распространяется по лицензии [Apache-2.0](LICENSE). Сторонние компоненты в составе сборок
идут под своими лицензиями.

Какие данные клиент передаёт и хранит — в [политике конфиденциальности](PRIVACY.md).

---

Люди, переписка и встречи на снимках и в ролике выдуманы.
