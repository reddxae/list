# 🤖 Android

## Приложения:
### 📹 Стриминговый контент и социальные сети
* [ReVanced для YouTube.](https://github.com/j-hc/revanced-magisk-module/releases) Идейное продолжение Vanced — модификации, предоставляющей блокировку рекламы, фоновое воспроизведение видео, режим Картинка-в-картинке и другие полезные функции, официально предоставляемые только за плату или вовсе недоступные в официальном клиенте. По ссылке предоставлены готовые сборки в виде модулей и non-root версий (для последних требуется [ReVanced GmsCore](https://github.com/ReVanced/GmsCore)).
  * Рекомендую использовать сборки ReVanced Extended на основе патчей от [inotia00.](https://github.com/inotia00/revanced-patches) Они содержат больше функций.<sup>[`ℹ️`](https://github.com/inotia00/revanced-patches?tab=readme-ov-file#-comgoogleandroidyoutube)</sup> Публикуются на указанной выше странице релизов с пометкой "YouTube-Extended".
* [PurpleTV для Twitch.](https://t.me/pubTw) Модификация на основе официального клиента (ранее называлась TwitchMod). Позволяет скрывать или перемещать элементы интерфейса, можно обходить блокировки в чатах (писать нельзя, но доступен просмотр). Для чатов так же доступны кастомные смайлики (BTTV и подобные). Встроен VODHunter и другие функции.
* [Piko для X.](https://github.com/crimera/twitter-apk) Это сторонние revanced-патчи<sup>[`ℹ️`](https://github.com/crimera/piko#%EF%B8%8F-patch-details)</sup> для официального клиента X (Twitter). Содержат базовые функции, присущие модификациям: скрытие рекламы, изменение порядка или скрытие элементов в интерфейсе, и другое. Также разблокирована загрузка видео. По ссылке предоставлены готовые сборки пропатченного клиента.
* [Взломанная версия приватного мода от TikTokModCloud.](https://t.me/tiktalkupdate) Ранее это был отдельный мод от Jaggu со схожей функциональностью, но времена меняются. Мод всё так же позволяет выкладывать фото/видео без VPN, менять по необходимости регион (лучше оставить США/Беларусь), да и в целом работа клиента неотличимо стабильна от оригинала. Замечу, что автору канала очень свойственно пропасть на полгода без поддержки клиента, поэтому если вам важна актуальность версии приложения и методов обхода, лучше [приобрести мод](https://t.me/TikTokMod_Bot) у его разработчика.
  * Может, пригодится: [здесь](https://t.me/tiktokmodcloud_apk) также публикуется и бесплатная версия мода от TikTokModCloud, без убогих рефералок и прочих трудностей с загрузкой. В этих версиях публикация медиа работает не у всех, а так же присутствуют рекламные баннеры.

> [!TIP]
> Можно подменить код региона SIM-карты в системе, что позволит использовать официальную версию TikTok прямо из Google Play со всеми функциями, включая публикацию контента. Сделать это можно с помощью [модуля](https://github.com/reddxae/list/blob/files/iso-code-changer.zip) (по умолчанию указана Беларусь) или [через Shamiko,](https://github.com/nullbytepl/CarrierVanityName) если у вас нет рут-прав.

Ах, ВКонтакте... вы и сами всё про него знаете. Тем не менее, наверняка по тем или иным причинам кто-нибудь его все ещё использует (надеюсь, только из вынужденных обстоятельств 🙏):
* [VTLite.](https://github.com/vtosters/lite) Классический клиент на основе старой базы с открытым исходным кодом.
* [SOVA V RE.](https://t.me/sovaV) На момент мая 2025, последнее обновление клиента было больше года назад [(1 апреля 2024),](https://t.me/sovaV/354) сейчас в клиенте не работают push-уведомления через FCM<sup>[`ℹ️`](https://firebase.google.com/docs/cloud-messaging)</sup>, а также недоступно подавляющее большинство реакций в сообщениях.

### 💬 Мессенджеры

> [!IMPORTANT]
> Так уж повелось в среде разработки сторонних Telegram-клиентов, что подавляющее большинство среди крайне редко обновляют свой исходный код, а некоторые и вовсе поставляются с закрытым. Поэтому я ввёл ~~рівень потужності~~ условные обозначения для клиентов, использовать которые можно только на свой страх и риск, ведь это приложения, имеющие доступ ко всем вашим личным перепискам.  
> ⚠️ — клиент не обновляет исходный код и его сборки невозможно воспроизвести.  
> ❗ — клиент нарушает ToS (Условия использования). Будьте осторожны, существует риск блокировки аккаунта.

Telegram:
* [Nekogram.](https://t.me/NekoUpdates) Классический кастомный клиент Telegram с базовым набором функций и открытым исходным кодом. Недавно (в кои-то веки!) добавили опцию, отключающую воспроизведение медиа на экране по нажатию клавиш громкости.
* [⚠️ exteraGram.](https://t.me/exteraGramCI) Клиент с качественным интерфейсом и грамотной Monet-покраской. По функциональности, есть отключение Premium-анимаций/стикеров/оформления профиля, оформления сообщений, статусов, аватаров и т.п., скрытие нижней панели в каналах, скрытие меню "Отправить от имени канала" (с сохранением его функциональности), сворачивание клавиатуры при прокрутке чата, бесконечные недавние стикеры, новое сжатие отправляемых фото (2560px), отключение воспроизведения медиа на экране по нажатию клавиш громкости и некоторые другие эксклюзивные функции, такие как AI Chat, адблок для встроенного браузера, использование Яндекс Карт вместо Google и другое.
  * [⚠️❗ AyuGram.](https://t.me/ayugramchat) Клиент на основе exteraGram, содержащий в себе функции режима "невидимки", сохранения удалённых сообщений, сохранение истории редактирования сообщений, пересылка и скриншоты в каналах, где это запрещено настройками приватности. Помимо этого, в клиенте полностью отсутствует реклама даже без подписки Telegram Premium.
* [❗ Nagram X.](https://github.com/risin42/NagramX) Открытый клиент, совмещающий в себе функции из обычного [Nekogram](https://github.com/reddxae/list/blob/main/list/android.md#:~:text=Nekogram), [NekogramX](https://t.me/NekogramX), [Nagram](https://t.me/nagram_channel) и ToS-breaking функции из [AyuGram.](https://github.com/reddxae/list/blob/main/list/android.md#:~:text=AyuGram)
* [⚠️ Plus Messenger.](https://t.me/PlusMessengerUpdates) Идейный собрат ныне покойного [⚠️ BGram.](https://t.me/BGramChannel) Содержит огромное количество функций и широкую кастомизацию.

<sup>`(Требуются root-права и LSPosed)`</sup> [Killergram Neo.](https://github.com/AetherMagee/KillergramNeo/tags) Модуль для клиентов Telegram на основе официального. Опционально позволяет заменить стоковые иконки интерфейса в приложении на Solar, скрыть истории, отключить автовоспроизведение медиа по кнопке громкости, удалить рекламу из каналов, разрешить пересылку из защищенных каналов, снять лимит на количество аккаунтов в приложении, форсировать использование системных шрифтов.

Matrix:
* [Element для Matrix.](https://element.io/download) Самый функциональный и стабильный кроссплатформенный клиент.
* [Fluffy Chat.](https://github.com/krille-chan/fluffychat) Работает так себе, но в нём достаточно функций, чтобы им можно было заменить Element, если тот по каким-то причинам не нравится.
* [Element X.](https://github.com/element-hq/element-x-android) Красивый и быстрый клиент, но очень скупой на функциональность. Подойдет только для самой базовой переписки.

### ⌛️ Блокировка рекламы
* [AdAway.](https://github.com/AdAway/AdAway) Блокировка рекламы через локальные hosts-файлы. Может работать в режиме VPN (т.е. root-доступ необязателен; с root рекомендуется использовать в паре с [bindhosts](https://github.com/bindhosts/bindhosts)). Готовые списки можно взять [здесь.](https://4pda.to/forum/index.php?showtopic=275091&st=8000#entry89665467)
> Лучше добавить в разрешённые листы `firebase-settings.crashlytics.com`, `firebaseremoteconfig.googleapis.com` и *(опционально)* `firebaselogging.googleapis.com`. Эти адреса должны быть разблокированы для корректной работы некоторых приложений, завязанных на Сервисах Google.

### 🎧 Аудио и стриминг музыки
Стриминговые сервисы:
* [XManager для Spotify.](https://t.me/xManagerUpdates) Подойдёт как для не-Premium, так и для Premium-аккаунтов. В случае с первыми, мод отключает всю аудио/визуальную рекламу, оставляя лишь серверные ограничения на качество воспроизводимого аудио и необходимость в ре-логине каждые 2 недели (если вы не находитесь в регионе, установленном в вашем аккаунте). Для обоих типов пользователей будет полезна активация экспериментальных функций (значок колбочки сверху в менеджере), зачастую среди них много полезного.
* [Взломанная Яндекс Музыка.](https://github.com/slavrom21/YMReleases)
* [VK X.](https://t.me/vkxci)

Локальное аудио:
* [Auxio.](https://github.com/OxygenCobalt/Auxio) Плеер локальной музыки.
* [Wavelet.](https://pittvandewitt.github.io/Wavelet/) Скромный эквалайзер с базовыми настройками и поддержкой конфигов AutoEQ. Не требует root-прав или Shizuku и работает с большинством популярных плееров, включая Spotify. [Взломанные версии здесь.](https://4pda.to/forum/index.php?showtopic=994106)
* <sup>`(Shizuku)`</sup> [RootlessJamesDSP.](https://github.com/ThePBone/RootlessJamesDSP) Эквалайзер с большим количеством настроек.

### 📪 Почта
* [Thunderbird или K-9 Mail](https://github.com/thunderbird/thunderbird-android) (сейчас это один и тот же клиент).

### 🛡 Аутентификация и пароли
* 2FA-аутентификация: [Authenticator Pro](https://apt.izzysoft.de/fdroid/index/apk/me.jmh.authenticatorpro) или [Aegis.](https://github.com/beemdevelopment/Aegis)
* [Keyguard.](https://github.com/AChep/keyguard-app) Частично-свободный, удобный клиент для Bitwarden.
* [KeePassDX.](https://github.com/Kunzisoft/KeePassDX) Локальное хранение паролей в зашифрованном виде с унифицированным форматом дата-баз KeePass.

### 🖼 Фотографии
* [ReVanced Google Photos.](https://github.com/j-hc/revanced-magisk-module/releases) Безлимитный бэкап медиа в Google Фото без root-прав (работает по той же логике, что и с помощью модулей — спуф устройства под Pixel XL). Среди файлов находим Google Photos, предоставлены варианты в виде модуля и приложения (для последнего требуется [ReVanced GmsCore](https://github.com/ReVanced/GmsCore)).
* [Aves.](https://github.com/deckerst/aves) Свободная, красивая и функциональная галерея. Поддерживает огромное количество форматов фото/видео, расширенный поиск по медиатеке, сортировку по различным критериям и другие функции.
* [Snapseed.](https://play.google.com/store/apps/details?id=com.niksoftware.snapseed) Редактирование фотографий с небольшим уклоном в профессиональную обработку. Нечто большее, чем тупой кроп или стрёмные фильтры.
* [Photok.](https://f-droid.org/packages/dev.leonlatsch.photok/) Хранение фотографий на устройстве под кодовой защитой с применением шифрования.

### 🌐 Браузеры
* [Edge.](https://play.google.com/store/apps/details?id=com.microsoft.emmx) Да, внезапно самый сбалансированный браузер на сегодня. Имеет хоть и ограниченную, но достаточную поддержку расширений для большинства пользователей (доступен uBlock Origin с некоторыми махинациями: для приложения нужно установить китайский язык, тогда оно станет доступным для загрузки и останется после возвращения языка. Чтобы не переключать весь интерфейс системы на китайский, а поменять его только для Edge, читайте здесь), Dark Reader, Tampermonkey, SponsorBlock и другие), интерфейс постепенно становится удобнее. Основан на Chromium.
* [Iceraven.](https://github.com/fork-maintainers/iceraven-browser) Форк Firefox на GeckoView с нормальной поддержкой расширений, чуть более широкой кастомизацией и доступом к флагам (about:config).
* 🪦 <sup>`(разработка прекращена)`</sup> [Kiwi Browser.](https://github.com/kiwibrowser/src.next/releases/tag/12867802748) Поддерживает [десктопные расширения](https://github.com/reddxae/list/blob/main/list/browser_add-ons.md) для Chrome и ещё [несколько полезных функций.](https://kiwibrowser.com/features/)
* [Cromite.](https://github.com/uazo/cromite) Форк Bromite [с большим количеством функций.](https://github.com/uazo/cromite#features)

### ☀️ Погода
* [Breezy Weather.](https://github.com/breezy-weather/breezy-weather) Обновляемый форк [Geomertic Weather,](https://github.com/WangDaYeeeeee/GeometricWeather) выросший в отдельный проект. Гибко настраиваемое приложение с прогнозами погоды. Сделано качественно, имеет хороший дизайн и отзывчивый интерфейс, поддерживает множество источников информации.
* <sup>`(Android 14+)`</sup> [Погода Pixel.](https://www.apkmirror.com/apk/google-inc/pixel-weather/) Прогноз погоды от Google.

### 🔍 Поиск
* [Поиск Pixel.](https://4pda.to/forum/index.php?showtopic=1095929) Поиск в интернете и на устройстве, как в Pixel Launcher (начиная с Android 13 QPR1+). [Рекомендую мой русифицированный мод.](https://4pda.to/forum/index.php?showtopic=1095929&view=findpost&p=132797216)
* [MiCTS.](https://github.com/parallelcc/MiCTS/blob/main/README_en.md) Активация функции "Обвести для поиска" от Google на любых устройствах.
* [SauceNAO.](https://f-droid.org/ru/packages/com.luk.saucenao/) Android-клиент [одноимённого сервиса](https://saucenao.com/) для реверсивного поиска изображений.

### 📁 Файловые менеджеры
* [Material Files.](https://f-droid.org/ru/packages/me.zhanghai.android.files/) Свободная альтернатива Google Files с расширенной функциональностью. Поддерживает работу с FTP.

### 🤖 Эмуляция
* [Winlator.](https://github.com/brunodev85/winlator) Запуск классических x86_64 Windows-программ через Wine и Box86/Box64.

### 🏃 Продуктивность
* [HabitKit.](https://play.google.com/store/apps/details?id=com.roehl.habitkit&hl=en_US) Индивидуальный журнал-трекер вашей продуктивности.
* [Гречка (Buckwheat).](https://apt.izzysoft.de/fdroid/index/apk/com.danilkinkin.buckwheat) Менеджер финансов и трат.

### 🛍 Дисконтные карты
* [Catima.](https://github.com/CatimaLoyalty/Android) Карты лояльности с категориями и прочими опциями.

### 🎦 Видеосъёмка
* [mcpro24fps.](https://t.me/mcpro24fps) Лучший бесплатный софт для профессиональной (и не очень) видеосъёмки на Android. К огромному удивлению, действительно удобнее и качественнее своих платных аналогов. Отмечу крайнюю легковесность, приложение весит меньше 2 МБ.

### 📷 Веб-камера и микрофон
* [VO Mic.](https://wolicheng.com/womic/) Используйте свой телефон как микрофон для ПК.
* [DroidCam.](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=ru&gl=US) Использование камеры и микрофона устройства на ПК. [Клиенты для декстопных платформ.](https://dev47apps.com/)

### 📦 Отслеживание посылок
* [ГдеПосылка.](https://4pda.to/forum/index.php?showtopic=765532&st=620#entry127192901) По ссылке Pro-версия с рабочими уведомлениями.
* [Track24.](https://play.google.com/store/apps/details?id=net.track24.android&hl=ru&gl=US) Отслеживание посылок в виде сводки информации со всех международных источников.

### 🗣 Имиджборды и форумы
* [DashchanFork.](https://github.com/TrixiEther/DashchanFork) Актуальная версия мобильного клиента для различных имиджбордов.
* [Тема MaterialYou ComboSkin для официального клиента 4PDA.](https://4pda.to/forum/index.php?showtopic=1054830)
* [ForPDA.](https://f-droid.org/ru/packages/org.softeg.slartus.forpdaplus/) Альтернативный клиент для 4PDA, если оригинальный чем-то не устраивает.

### 📖 Чтение
* [ReadEra.](https://readera.org/ru)

### 🗾 Аниме и манга
* [Anixart.](https://t.me/seele_channel/170) Лучший агрегатор аниме на мобильных устройствах. По ссылке мод с премиумом и без региональных ограничений. Опционально добавлена поддержка Monet или AMOLED-темы.
* [Kotatsu.](https://github.com/KotatsuApp/Kotatsu) Приложение для чтения манги.
* [ShikiWatch.](https://github.com/wheremyfiji/ShikiWatch) Неофициальное приложение для Shikimori с возможностью онлайн просмотра аниме.

### ⚙️ Управление пакетами
* [Skit.](https://play.google.com/store/apps/details?id=com.pavelrekun.skit&hl=ru&gl=US) Менеджер установленных приложений. Умеет устанавливать сплит-пакеты, сохранять установленные приложения как .apk/сплит, быстро переходить к папкам с содержимым конкретных программ и другие функции.
* <sup>`(Root/Shizuku)`</sup> [Canta.](https://github.com/samolego/Canta) Удаление предустановленных приложений.

### 📥 Магазины приложений
* [Droid-ify.](https://f-droid.org/packages/com.looker.droidify/) Фронтенд F-Droid, выполненный в Material Design 3.
  * Рекомендуемые репозитории:  
`https://apt.izzysoft.de/fdroid/`
* [Aurora Store](https://f-droid.org/ru/packages/com.aurora.store/) или [App Lounge.](https://doc.e.foundation/support-topics/app_lounge) Свободный фронтенд для Google Play. Не требует авторизации – выбираем анонимную сессию (работает плохо, лучше всё-таки авторизоваться).
* [Obtainium.](https://github.com/ImranR98/Obtainium) Менеджер обновлений приложений из большого количества вручную настраиваемых источников (например GitHub, F-Droid или Huawei AppGallery, полезный для загрузки российских приложений).

<details>

<summary>Прямые ссылки на некоторые российские приложения из AppGallery</summary>

Т-Банк (Тинькофф): `https://appgallery.huawei.com/app/C101291451`  
Mir Pay: `https://appgallery.huawei.com/app/C103191567`  
Альфа-Банк: `https://appgallery.huawei.com/app/C101515897`  
Сбер: `https://appgallery.huawei.com/app/C100994843`  
ВТБ: `https://appgallery.huawei.com/app/C102312137`  
ПСБ: `https://appgallery.huawei.com/app/C102409911`  
Райффайзен: `https://appgallery.huawei.com/app/C101231337`  
Почта Банк: `https://appgallery.huawei.com/app/C101191061`  
Газпром Банк: `https://appgallery.huawei.com/app/C102137729`  
Мегафон: `https://appgallery.huawei.com/app/C101202073`  
Yota: `https://appgallery.huawei.com/app/C105436239`  
ЮMoney: `https://appgallery.huawei.com/app/C103046791`  
Авито: `https://appgallery.huawei.com/app/C101350475`
2ГИС: `https://appgallery.huawei.com/app/C100888583` (ещё доступно в Google Play)  
OZON: `https://appgallery.huawei.com/app/C100847609` (ещё доступно в Google Play)  
Wildberries: `https://appgallery.huawei.com/app/C101183325` (ещё доступно только в российском Google Play)

</details>

### 🛠 Системные утилиты
* [QuickTiles.](https://f-droid.org/packages/com.asdoi.quicktiles/) Позволяет добавлять готовые или кастомные быстрые тогглы для панели управления.
* [Tasker](https://tasker.joaoapps.com/) или [MacroDroid.](https://macrodroid.com/) Автоматизация действий.
* [LinkSheet.](https://github.com/LinkSheet/LinkSheet) Возвращает меню выбора приложения, которое откроет ссылку.
* [Blocker.](https://github.com/lihenggui/blocker) Блокировка компонентов приложений с помощью Intent Firewall. Имеет встроенные списки для массового отключения компонентов аналитики и слежки в других установленных приложениях.
* [OwnDroid.](https://apt.izzysoft.de/fdroid/index/apk/com.bintianqi.owndroid) Управление функциями системы от имени владельца (админа).
* [aShell.](https://f-droid.org/packages/in.sunilpaulmathew.ashell/) Терминал для ADB Shell с запущенным Shizuku.

### 🛜 Сеть
* [NetGuard.](https://github.com/M66B/NetGuard/) Выборочная блокировка доступа к интернету для приложений и ограничение рекламы через hosts, как в AdAway. Работает через локальное VPN-подключение, root-режима нет. [Варез здесь.](https://4pda.to/forum/index.php?showtopic=700336)
* [PCAPdroid.](https://f-droid.org/ru/packages/com.emanuelef.remote_capture/) Инструмент мониторинга и записи сетевого трафика. Рут-права не для работы необязательны, ибо приложение может работать через локальное VPN-подключение.
* [Rethink](https://f-droid.org/ru/packages/com.celzero.bravedns/) и [Data Monitor.](https://github.com/itsdrnoob/DataMonitor) Статистика использования трафика приложениями.
* [Hiddify Next.](https://github.com/hiddify/hiddify-next) "Однокнопочный" клиент для прокси и VPN.
* [NekoBox.](https://github.com/MatsuriDayo/NekoBoxForAndroid) Управление прокси и VPN на базе ядра sing-box (если вам нужно ядро Xray, используйте [v2rayNG](https://github.com/2dust/v2rayNG)).
> [!CAUTION]
> **Не используйте NekoBox из Google Play!** Версия в магазине приложений больше не принадлежит разработчику.
* [inviZible Pro.](https://f-droid.org/packages/pan.alexander.tordnscrypt.stable/) Обход блокировок через сеть Tor и i2p, а также шифрование DNS-запросов с помощью DNSCrypt. Для нормального запуска Tor, пройдите в быстрые настройки → Настройки Tor → Мосты → Запросить новый мост → выберите *obfs4* → введите капчу и подтвердите запрос, готово.

### ⬇️ Внешние загрузчики
* [Seal.](https://github.com/JunkFood02/Seal) Загрузчик видео/аудио, использующий yt-dlp (можно использовать aria2c). Очень удобный и простой в использовании. Выполнен в соответствии с MD3.
* [Aria2App.](https://f-droid.org/packages/com.gianlu.aria2app/) Фронтенд для [aria2.](https://github.com/aria2/aria2) Скачивает почти всё, поддерживает торренты.

### 🗄 Шифрование и безопасное хранение файлов
* [DroidFS.](https://f-droid.org/packages/sushi.hardcore.droidfs/) Шифрование файлов с использованием [gocryptfs](https://github.com/rfjakob/gocryptfs) или [CryFS](https://github.com/cryfs/cryfs) и управление ими на устройстве.
* [EDS Lite.](https://f-droid.org/ru/packages/com.sovworks.edslite/) Создание и управление зашифрованными контейнерами на Android.

### ♻️ Резервное копирование
* [Neo Backup.](https://f-droid.org/ru/packages/com.machiav3lli.backup/) Свободный бэкапер. Выборочное резервирование и восстановление одного или нескольких приложений. Работает только с root-правами.
* [Lucky Patcher.](https://4pda.to/forum/index.php?showtopic=298302) Нестареющая классика взлома приложений. Строго рекомендуем не лезть этой утилитой в недра системы, пользуйтесь только для операций с софтом.

### 💡 Полезное
* [Калькулятор из MIUI с нормальной иконкой для Launcher3-like лаунчеров.](https://4pda.to/forum/index.php?showtopic=792469&st=400#entry109791426)
* [LSPatch.](https://github.com/JingMatrix/LSPatch) Имплементация API Xposed в сборку приложения с дальнейшим управлением модулями через менеджер без root-прав. Работает далеко не со всеми модулями, каждый нужно проверять отдельно.
* [Barcode Scanner.](https://f-droid.org/packages/com.atharok.barcodescanner/) Сканер штрих/QR-кодов.
* <sup>`(Android 12 и ниже)`</sup>[Clipboard Cleaner.](https://f-droid.org/ru/packages/io.github.deweyreed.clipboardcleaner/) Выводит уведомления об операциях приложений/пользователя с буфером обмена, и тоггл в шторку для его очистки.
* [Memory Guardian.](https://apt.izzysoft.de/fdroid/index/apk/ara.memoryguardian) Настройка автоочистки буфера обмена.

## Shizuku
* [Shizuku.](https://shizuku.rikka.app/) Предоставление повышенных прав приложениям через adb с использованием локального сервера.  
Все приложения ниже поддерживают работу на устройствах без root-прав!  
[Автоматический запуск Shizuku после перезагрузки через Automate](https://llamalab.com/automate/community/flows/44848) и [как поставить.](https://www.reddit.com/r/Android/comments/128eak8/comment/jescmhz/?utm_source=share&utm_medium=web2x&context=3)
* [ShizuTools.](https://github.com/legendsayantan/ShizuTools) Набор утилит для работы с привилигерованным доступом. Так же добавляет новые функции в систему (например, управление громкостью отдельных приложений, разрешает понижение версии приложения без переустановки, форсирует Картинку-в-картинке для приложений, что её запрещают).
* <sup>`(Google Tensor)`</sup> [Pixel VoLTE Patch.](https://github.com/kyujin-cho/pixel-volte-patch/blob/main/README.en.md) Активация VoLTE на устройствах Pixel с процессором Tensor (Pixel 6 и новее).

Рекомендую заглянуть в [Awesome Shizuku.](https://github.com/ThePBone/awesome-shizuku) Это обновляемый список приложений, поддерживающих работу через локальный adb.

## Модули для Magisk
* [Net Switch.](https://github.com/Rem01Gaming/net-switch) Простой фаервол на iptables для ограничения доступа в интернет конкретным приложениям.
* [Hide My Applist.](https://github.com/Dr-TSNG/Hide-My-Applist) Скрытие отдельных приложений.
* [ViPER4Android Repackaged.](https://github.com/programminghoch10/ViPER4AndroidRepackaged)
  * [ViperFX RE (Material Design 3)](https://github.com/WSTxda/ViperFX-RE-Releases) Дополнительно нужен [драйвер.](https://github.com/WSTxda/ViPERFX_RE/releases)
* [JamesDSPManager.](https://github.com/Zackptg5/JamesDSPManager/blob/master/install.zip) Актуальный установщик root-версии JamesDSP (при установке рекомендую выбирать интерфейс от [ThePBone](https://github.com/timschneeb)). Дальнейшие обновления приходят автоматически в приложении.
* [Call Recording](https://modules.lsposed.org/module/io.github.vvb2060.callrecording/) для Google Телефона. Простой модуль без интерфейса, который убирает региональные ограничения на доступ к самой функции записи вызовов и убирает предупреждение о начале записи (обратите внимание: предупреждение перестанет воспроизводиться только после совершения первого звонка с записью вызовов, т.е. при активации записи в первый раз, предупреждение будет озвучено на линии собеседнику, а уже следующие разы будут без предупреждения. Чтобы обойти это, включите автоматическую запись вызовов в настройках и подтвердите согласие на отказ от ответственности во всплывающем окне. Затем фукнцию можно отключить и пользоваться только ручной активацией).
* [Basic Call Recorder.](https://github.com/chenxiaolong/BCR#readme) Стороннее приложения для записи вызовов.
  * [bcr-gui.](https://github.com/nicorac/bcr-gui) Интерфейс для управления сохраненными записями.
* [Font Loader.](https://github.com/JingMatrix/FontLoader) Предзагружает файлы кастомных шрифтов с помощью Zygisk для приложений, для которых модули размонтированы, тем самым предотвращая вылет из-за невозможности доступа приложения к шрифтам.
* [KTweak.](https://t.me/ktweak) Безопасные твики производительности, разделенные на пресеты с разными нуждами. Не требуется для современных устройств.
* [Global Optimized GPS.](https://github.com/skyrocketingHong/OptmizedGPSConf) Улучшение и ускорение фиксации/блокировки спутниковых сигналов.
* [DriveDroid Fix.](https://github.com/overzero-git/DriveDroid-fix-Magisk-module) Восстаналивает работу DriveDroid на новых версиях Android.
* <sup>`(Google Tensor)`</sup> [Universal Modem Fix.](https://github.com/daradan/5g_enabler) Снимает ограничения работы LTE в странах СНГ.
* [Custota.](https://github.com/chenxiaolong/Custota) Установка OTA-обновлений с вашего сервера. Поддерживает работу в паре с [avbroot.](https://github.com/chenxiaolong/avbroot/blob/master/README.ru.md)
  - [PixelUpdater.](https://github.com/PixelUpdater/PixelUpdater) Замена встроенного OTA-апдейтера в стоковой прошивке Pixel. Установка официальных обновлений системы от Google для рутированных устройств с автоматическим патчингом Magisk и пропуском ненужных проверок, что значительно ускоряет процесс обновления.
* [QuickSwitch.](https://github.com/j7b3y/QuickSwitch/releases) Безболезненная замена стандартного лаунчера вместе с провайдером меню недавних приложений.
* [Disable logs.](https://github.com/reddxae/list/tree/files#disable-logs) Отключение логгирования.
* [BitGApps.](https://bitgapps.io/) Бессистемная установка GApps.
* [microG Installer Revived.](https://github.com/nift4/microg_installer_revived) Почти единственный актуальный установщик microG для Magisk. Включает в себя всё для стабильной работы (включая пуши и геолокацию). Если прошивка не поддерживает подмену подписи, активируем её через [этот модуль для LSPosed.](https://github.com/whew-inc/FakeGApps/releases)
  - [microG Sync Services.](https://github.com/reddxae/list/blob/files/microg-sync-services.zip) Добавляет сервисы синхронизации данных для Google Контактов и Календаря.
* [zygisk-detach.](https://github.com/j-hc/zygisk-detach) Блокировка автообновления приложений через Google Play путём скрытия их наличия в системе от маркета. Мастхэв при установленном ReVanced rooted-методом.
  * [zygsik-detach-app.](https://github.com/j-hc/zygisk-detach-app) Интерфейс для модуля.

### Модули для LSPosed

* [SmartPiXelsPosed.](https://github.com/frknkrc44/SmartPiXelsPosed) Порт функции "Умных пикселей" из кастомных прошивок.
* <sup>`(Android 14+)`</sup> [DisableTargetAPIBlock.](https://github.com/buttercookie42/DisableTargetAPIBlock) В Android 14 было введено новое ограничение на установку древних приложений, из-за которого установщик выдаст ошибку, если Target API (целевая версия Android) слишком низкая. Этот модуль снимает это ограничение.
* <sup>`(Android 14+)`</sup> [CaptureSposed.](https://github.com/99keshav99/CaptureSposed) Отключает API обнаружения скриншотов приложениями.<sup>[`ℹ️`](https://github.com/99keshav99/CaptureSposed#capturesposed)</sup>
* [Enable Screenshot (Disable FLAG_SECURE).](https://github.com/LSPosed/DisableFlagSecure) Отключает способность приложений обнаруживать и запрещать скриншоты/запись экрана.
* <sup>`(Android 14+)`</sup> [Circe to Search Spoofer.](https://github.com/fillwithjoy1/circle-to-search-spoofer) Спуф устройства под Pixel 8 Pro для активации функции Обвести для поиска. Применяется исключительно к приложению Google (`com.google.android.googlequicksearchbox`).
* [Pixelify GPhotos.](https://github.com/miIiano/Pixelify-Google-Photos) Безлимитное копирование фотографий в исходном качестве. Для активации выберите подмену устройства под Pixel XL. Применяется исключительно к приложению Google Фото (`com.google.android.apps.photos`).
* <sup>`(Android 12+)`</sup> [Let Me Downgrade.](https://github.com/DavidBerdik/Let-Me-Downgrade) Откат версии приложения с сохранением данных.

> [!WARNING]
> Эти модули встраиваются в финансовые приложения. Используйте на свой страх и риск!
* [Yandex Maps Patcher.](https://github.com/Xposed-Modules-Repo/ru.bluecat.yandexmapspatcher) Скрытие рекламы в приложении Карт.
* [Marketplace Adaway.](https://github.com/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway) Скрывает назойливую рекламу в приложениях российских маркетплейсов.
* [Sberbank Patcher.](https://github.com/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher) Различные QOL-изменения в приложении Сбербанка: отключение панелей "Прайма", Ассистента, автообновления, антивируса и прочего шлака.
* [Alfabank Patcher.](https://github.com/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher) Скрытие рекламы различного формата и управление push-уведомлениями.

### Персонализация с root-правами
* <sup>`(Root, Android 12+)`</sup> [ColorBlendr.](https://github.com/Mahmud0808/ColorBlendr) Приложения для тонкой настройки вашей Monet-темы. Поддерживает покраску новых приложений от Google и других с обновлёнными компонентами Material Design.
* <sup>`(Root, Android 12+)`</sup> [Global Icon Pack.](https://github.com/RichardLuo0/global-icon-pack-android) Применение пакетов иконок для всей системы и/или для лаунчеров, где эта функциональность не предусмотрена.
* <sup>`(Root, Android 12+)`</sup> [Classic Power Menu.](https://github.com/KieronQuinn/ClassicPowerMenu) Возвращает «классическое» меню питания (как в Android 11) с быстрым доступом к картам в Google Wallet, плиткам «Управления домом» и дисконтным картам.
* <sup>`(Shizuku, Android 12+)`</sup> [Smartspacer.](https://github.com/KieronQuinn/Smartspacer) Модификация встроенного виджета "Самое главное" (At a Glance) для устройств Pixel.
* [WallMan.](https://apt.izzysoft.de/fdroid/index/apk/com.colorata.wallman) Живые обои всех моделей Google Pixel в одном месте.
* [Lawnicons.](https://github.com/LawnchairLauncher/lawnicons/releases) Хороший набор иконок для всех лаунчеров.
* <sup>`(макс. Android 13, 14 и выше не поддерживается)`</sup> 🪦 [Shortcut Maker.](https://play.google.com/store/apps/details?id=rk.android.app.shortcutmaker) Позволяет создавать шорткаты приложений с автоматической Monet-покраской (для тех, что не поддерживают ее по умолчанию) или с использованием сторонних иконпаков, неотличимо маскируя результат под нативные иконки в любом Launcher3-like лончере (это Pixel Launcher, Trebuchet, crDroid Home и прочие).
* <sup>`(Модуль / Android 13+)`</sup> [PixelXpert.](https://github.com/siavash79/PixelXpert) Кастомизация из сторонних прошивок для стоковой прошивки Pixel/чистого AOSP.
  * Кстати, если вам нужны стили иконок для статус-бара или плиток в быстрых настройках, [используйте старую версию модуля](https://github.com/siavash79/PixelXpert/releases/tag/v2.9.0) (ранее он назывался AOSPMods). Работает только на Android <13.
* <sup>`(Shizuku / Android 12+)`</sup>[Better Internet Tiles.](https://github.com/CasperVerswijvelt/Better-Internet-Tiles) Возвращает раздельные тайлы для мобильного интернета и Wi-Fi.
* <sup>`(Модуль / Android 15+)`</sup> [Шрифт Inter.](https://github.com/reddxae/protonaosp-font-pack)<sup>[`ℹ️`](https://rsms.me/inter/)</sup>
  * для предыдущих версий Android, файлы можно найти [здесь.](https://github.com/ihfandicahyo/proton-aosp-stuff)
* <sup>`(Модуль / Android 12+)`</sup> [Эмодзи из iOS.](https://github.com/Keinta15/Magisk-iOS-Emoji)<sup>[`ℹ️`](https://emojipedia.org/apple)</sup>
* <sup>`(Модуль / Android 13+)`</sup> [Split Shade (BetterQS).](https://github.com/reddxae/list/blob/files/split-shade.zip) Удобная разметка панели быстрого доступа и уведомлений при горизонтальной ориентации экрана.<sup>[`ℹ️`](https://github.com/reddxae/list/blob/files/betterqs_preview.png)</sup>
* <sup>`(Модуль / Android 11+)`</sup> [Модуль, отключающий эффект приближения обоев на рабочем столе при разблокировке устройства и открытии/сворачивании приложения.](https://github.com/reddxae/list/blob/files/wall_zoom_anim_disabler.zip)
* <sup>`(LSPosed / Android 12+)`</sup> [Модуль, отключающий анимацию "волны" при разблокировке устройства.](https://github.com/reddxae/list/blob/files/disable_ripple_on_unlock.apk) Полезно, если у вас она систематически подтормаживает.
* <sup>`(Модуль)`</sup> [Всякая хрень для статус-бара.](https://www.pling.com/p/1488365/) Может пригодиться, если, например, вы используете набор иконок Circular или Outline, и вам не нравится сильно бросающийся в глаза жирный шрифт у значка LTE. Тогда можно заменить его на иконку 4G или LTE+ в стиле Android 11.

## Полезное
* Установить кастомную скорость анимаций через adb shell:
  * `settings put global window_animation_scale 0.XX`
  * `settings put global transition_animation_scale 0.XX`
  * `settings put global animator_duration_scale 0.XX`
* Принудительный запуск оптимизации приложений (бывает полезно в случаях, если сделали клинфлеш с последующей установкой большого количества приложений/обновили версию Android с сохранением данных):
  1. Если у вас есть root-права: запускаем в Терминале команду `su -c "cmd package bg-dexopt-job"` и ожидаем окончания процесса (будет выведена строка Success).
  2. Если root-прав нет, выполняем `cmd package bg-dexopt-job` через Shizuku или классический `adb shell`.
  3. Предкомпиляция байт-кода, принудительное пересоздание уже созданного раннее системой кэша: `pm compile -a -f -m everything; cmd package bg-dexopt-job` (рекомендуется).
* Разблокировать смену языка для всех приложений на Android 13+ (может не поддерживаться приложением, в таком случае смена языка не окажет никакого эффекта):
  `settings put global settings_app_locale_opt_in_enabled false`

Оптимизация отдельного приложения производится командой `cmd package compile --reset <имя_пакета>`.
* [scrspy.](https://github.com/Genymobile/scrcpy) Универсальное решение для захвата экрана, звука или видео с Android-устройства через прямое подключение по USB или Wi-Fi.
* Легковесный [ADB Debloater](https://github.com/SunsetTechuila/ADB-Debloater) с оптимальным набором пакетов для всех устройств или более функциональный [Universal Android Debloater](https://github.com/0x192/universal-android-debloater) с большим числом пакетов для прошивок китайских вендоров.

# 📚 Подборки софта
* [Большой список исключительно свободного софта для Android (некоторые приложения могут быть устаревшими)](https://github.com/offa/android-foss)
* [Список всевозможных приложений, выполненных в Material Design 3.](https://github.com/nyas1/Material-You-app-list)
