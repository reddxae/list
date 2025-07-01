# 🪟 Windows:  
>
> [!NOTE]
> [Перманентная активация Windows 10-11 с серверной привязкой по железу:](https://github.com/massgravel/Microsoft-Activation-Scripts)  
Открываем PowerShell, запускаем команду `irm https://get.activated.win | iex`, выбираем **[1] HWID.** Готово.  

### ⚙️ Настройка, дополнения и системные утилиты
* [Sophia Script.](https://github.com/farag2/Sophia-Script-for-Windows) Тонкая подстройка рабочего окружения под себя. Использует только то, что реализуемо путём задокументированной разработчиками Windows функциональности. Перед началом работы, **обязательно проверяйте совместимость** текущей версии скрипта с вашей сборкой Windows.
  * [SophiApp.](https://github.com/Sophia-Community/SophiApp) Sophia Script, завернутый в удобный пользовательский интерфейс с дополнительным описанием к каждой опции.<sup>[`ℹ️`](https://github.com/Sophia-Community/SophiApp?tab=readme-ov-file#key-features)</sup> Находится в стадии вечной разработки и может быть несовместим с последними сборками Windows.
* [VisualCppRedist AIO.](https://github.com/abbodi1406/vcredist) Сборник всех устанавливаемых Visual C++ Redistributable 2005-2022.
  * [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework)<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/info.md#net-runtime)</sup> и [VCLibs.](https://learn.microsoft.com/ru-ru/troubleshoot/developer/visualstudio/cpp/libraries/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages)<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/info.md#vclibs)</sup> Порой нужные зависимости.
* [SKTimeStamp.](https://tools.stefankueng.com/SKTimeStamp.html) Добавляет раздел для точного изменения времени создания/модификации/открытия через свойства файла в Проводнике.
* [Windows Terminal.](https://github.com/microsoft/terminal/) Терминал от Microsoft с широкой кастомизацией, поддерживает любые виды консолей, будь то Командная строка, PowerShell или WSL. Рекомендую задать его как приложение для командной строки по умолчанию.<sup>[`ℹ️`](https://learn.microsoft.com/ru-ru/windows/terminal/install#set-your-default-terminal-application)</sup>
* [SuperF4.](https://github.com/stefansundin/superf4/releases/download/v1.4/SuperF4-1.4.exe) «Принудительно закрывает»‎ зависшее окно, иными словами, убивает его процесс по сочетанию клавиш Ctrl+Alt+F4. То есть используется вами вместо стандартного сочетания Alt+F4, которое в случаях повисшего процесса не помогает.
* [Notepad Replacer.](https://www.binaryfortress.com/NotepadReplacer/) Замена классического Блокнота и соответствующих системных ссылок на пользовательскую программу.
* [Monitorian.](https://apps.microsoft.com/store/detail/monitorian/9NW33J738BL0) Изменение яркости внешних мониторов с поддержкой DDC/CI.<sup>[`ℹ️`](https://github.com/emoacht/Monitorian#detection-of-external-monitors)</sup>
* [System Informer.](https://github.com/winsiderss/systeminformer) Свободная альтернатива Process Explorer/Hacker с поддержкой тёмной темы (Options → General → Enable theme support). Управление работающими процессами в системе. Расширенная альтернатива системных диспетчера задач и монитора ресурсов.

### 🎨 Персонализация интерфейса
* [BeautySearch.](https://github.com/krlvm/BeautySearch) Модификации для поиска встроенного в панель задач.
* <sup>`(Windows 11)`</sup>[MicaForEveryone.](https://github.com/MicaForEveryone/MicaForEveryone) Кастомизация внешнего вида окон Win32-приложений. 
* <sup>`(Windows 11)`</sup>[StartAllBack.](https://t.me/repack_me_clone) Незаменимый софт для комфортного перехода с Windows 10 на 11. Можно использовать пресет "Правильная 11", либо настроить всё вручную. Нормальная панель задач, кардинально переработанный тёмный режим, покраска в акцентный цвет для Win32-элементов, акриловый фон для классического контекстного меню, регулировка громкости колёсиком мыши по значку по панели задач и другие настройки. 
* <sup>`(Windows 10/11)`</sup>[ExplorerBlurMica.](https://github.com/Maplespe/ExplorerBlurMica) Софт для настройки эффекта акрила (как в Windows 10) или Mica для окон Проводника.

<details>

<summary>Рекомендуемые настройки для Windows 11</summary>

1. Для [MicaForEveryone:](https://github.com/MicaForEveryone/MicaForEveryone) проставить всё на "По умолчанию" в разделе "Глобальное правило", в дальнейшем создавая для каждой программы отдельный конфиг. Цвет заголовка окна выбирайте в соответствии с темой программы; фон на Tabbed; включить "Расширить рамку окна в клиентскую область".
2. [StartAllBack:](https://www.startallback.com/) открыть окно "Выполнить" (Win+R), запустить команду `startisbackcfg /magic`. Откроется окно свойств StartAllBack в разделе Magic, включаем пункт Cast dark magic. 
3. [ExplorerBlurMica:](https://github.com/Maplespe/ExplorerBlurMica) настраиваем эффект Mica для всех окон Проводника в Windows 11:
   * Должны быть установлены **все три** программы: Mica For Everyone, StartAllBack и ExplorerBlurMica.
   * В StartAllBack должена быть активирована опция Cast dark magic.
   1. Переходим к файлу config.ini, расположенном в папке с ExplorerBlurMica.
   2. Редактируем содержимое строк:  
   `effect` меняем на `2`  
   `clearWinUIBg` меняем на `false`<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#explorerblurmica-false)</sup> или оставляем `true`<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#explorerblurmica-true)</sup> – попробуйте, какой вариант больше понравится. 
   3. Открываем Mica For Everyone и полностью удаляем пресет для explorer.
   4. Добавляем правила для классов `#32700` и `OperationStatusWindow`. В обоих устанавливаем параметр Фон на *Tabbed* и включаем Расширение рамки в клиентскую область.
   5. Принудительно перезагружаем Проводник.
</details>
 
* [Windhawk.](https://github.com/ramensoftware/windhawk) Инъекции кода в Windows.
  * [Windows 11 Start Menu Styling.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide) [Различные стили](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#themes) для меню Пуск в Windows 11. Например, скрывающий секцию "Рекомендации", или добавляющий разметку с закрепленными приложениями и списком всех приложений. [Инструкция.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#introduction)
* [MSEdgeRedirect.](https://github.com/rcmaehl/MSEdgeRedirect) Кастомизация для панелей новостей, погоды; смена стандартного браузера для результатов поиска в Интернете через Поиск Windows.
* [Cursor Colors Synchronizer.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer) Синхронизирует тему и акцентный цвет [одной из двух версий кастомного курсора](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer?tab=readme-ov-file#description) с системой.
* [WinPaletter.](https://github.com/Abdelrhman-AK/WinPaletter) Гибкая настройка цветовой палитры различных элементов интерфейса Windows.<sup>[`ℹ️`](https://github.com/Abdelrhman-AK/WinPaletter#-winpaletter-advanced-windows-appearance-editor)</sup>
* <sup>`(Windows 10)`</sup>[TrayVolumeControl.](https://github.com/krlvm/TrayVolumeControl) Регулировка громкости колёсиком мыши при наведении курсора на иконку громкости. Быстро привыкаешь и без этого становится неудобно, советую.
* <sup>`(Windows 10/11 <22H2)`</sup>[EarTrumpet.](https://eartrumpet.app/) Альтернативное меню управления звуком для панели задач. Основная польза в наличии микшера громкости приложений под общим ползунком громкости. Переключение источника звука через ПКМ по иконке.<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#eartrumpet)</sup> Так же по умолчанию есть регулировка громкости колёсиком по наведении на иконку, соответственно программа выше не нужна.

### ⏺ Скрин-шеринг и скринрекордеры
* [RustDesk (Windows).](https://rustdesk.com/) Свободная альтернатива AnyDesk/TeamViewer. Возможен селфхост, но отлично работает и на бесплатных серверах из Германии и Киева. Последний не будет работать в России без VPN (РКН заблокировал любые подключения к UA-зоне).
* [ShareX.](https://getsharex.com/) Лучший скрин-шотер/рекордер для Windows. Очень кастомизируемая программа с полностью открытым исходным кодом. Предоставляет точный выбор области записи/снимка, широкий выбор инструментов для редактирования скриншота, умеет записывать экран с использованием NVENC, автоматическое конвертирование записанных видео в GIF. Опционально можно выгружать скриншоты на всевозможные имейдж-аплоадеры, выборочно, в пару кликов. Всё управление можно настроить на хоткеи. Абсолютный мастхэв.
* [OBS.](https://obsproject.com/ru) Утилита для захвата экрана и проведения прямых трансляций. Гибко настраивается, имеет управление с разными пресетами ("сценами"), удобная и простая панель управления, поддержка плагинов.

### 🌐 Браузеры
* [Chromium GOST.](https://github.com/deemru/Chromium-Gost) Браузер с открытым исходным кодом на основе Chromium с поддержкой алгоритмов ГОСТ (т.е. для российских сайтов, форсирующих использование государственных сертификатов).

### ⛅️ Погода
* [Lively Weather.](https://github.com/rocksdanister/weather) Шикарное приложение для просмотра прогноза погоды.

### 🤖 Эмуляторы
* [(*EOL*)](https://github.com/microsoft/WSA/commit/5e0b982be3f6a9613d65a389d12554844d931bba) [WSABuilds.](https://github.com/MustardChef/WSABuilds) Подсистема Windows для Android, увидевшая свет с выходом Windows 11. Репозиторий содержит сборки как для Windows 11, так и 10. Есть вариации с OpenGApps/MindTheGApps, Magisk/~~KernelSU~~. И вырезан бесполезный Amazon Store, конечно.

### ▶️ Работа с медиафайлами
* [Mp3tag.](https://mp3tag.de/en/download.html) Редактирование метаданных в аудиофайлах.

### 🔈 Настройка звука
* [Alternative A2DP Driver.](https://bluetoothgoodies.com/a2dp/) Незаменимая вещь для владельцев Bluetooth-наушников с поддержкой HiRes кодеков aptX HD, aptX HD Low Latency и LDAC. По умолчанию Windows умеет работать только с AAC (Windows 11)/SBC/aptX кодеками, что существенно режет качество воспроизводимого аудио. Данная программа действительно панацея, но... Внимание: платно! Есть пробный период, в течение которого доступна вся функциональность. Проверьте совместимость с вашими наушниками, затем либо программа прекращает работу, либо вами покупается перманентная лицензия с привязкой по железу — $5.99. В рублях, на момент написания текста, это ~850 руб. оплатой через карту, [приобретённую на Plati.market.](https://plati.io/itm/1065234)
* [EqualizerAPO.](https://sourceforge.net/projects/equalizerapo/) Лучший эквлайзер для Windows, легко устаналивается и не вредит системе. Имеет широкий спектр различных настроек, возможность сохранять/применять пресеты для разных параметров.
* [EQAPOtoGraphicEQ.](https://github.com/zettonaender/eqapotographiceq-gui) Конвертация настроек Parametric EQ/Convolution EQ из EqualizerAPO или Peace в формат AutoEQ (например, для Wavelet). Рекомендую использовать Python-версию.

### ✉️ Почтовые клиенты
* [Thunderbird.](https://www.thunderbird.net/en-US/) Классический полнофункциональный почтовый клиент.
* Существует довольно красивый [Wino Mail,](https://github.com/bkaankose/Wino-Mail) вдохновленный ныне заброшенным нативным клиентом Outlook. Однако, за добавление более чем трёх ящиков, разработчик просит донат. <sup>[🤫](https://github.com/reddxae/Wino-Mail)</sup>

### 📄 Офисные приложения
* [Notepad++.](https://notepad-plus-plus.org/downloads/) Текстовый редактор с широкой поддержкой сообщества. Поддерживает плагины, темы, разные форматы.
* [Office Tool Plus.](https://github.com/YerongAI/Office-Tool) Настройка и управление пакетом Office.
* [Okular.](https://okular.kde.org/ru/) Универсальная читалка от KDE для форматов PDF, EPub, Tiff [и подобных.](https://okular.kde.org/ru/formats/)

### 🎞 Транскодирование
* [HandBrake.](https://handbrake.fr/) Конвертирование видео с различными параметрами в почти любой формат.

### 🖥 Управление программами
* [WingetUI.](https://github.com/marticliment/WingetUI) Графический интерфейс управления пакетным менеджером winget. Из наиболее очевидных удобств, автоматическое/выборочное обновление всего установленного софта на ПК через winget. Советуем попробовать начать пользоваться этим.
* [Uninstall Tool.](https://t.me/repack_me_clone) Расширенное удаление программ вместе с их "хвостами". Можно опционально выбрать установку сервиса, который будет отслеживать установки и собирать точную информацию про инсталляцию любого софта в систему.

### 📶 Управление сетью
* [Simplewall.](https://henrypp.org/product/simplewall) Настройка трафика с Windows Filtering Platform (WFP).

### 📀 Запись образов
* [Rufus.](https://rufus.ie) Базированнейшая тулза для записи образов. 
* [Ventoy.](https://ventoy.net/en/index.html) Софт для создания установочных, мульти/загрузочных флешек. Крайне прост в использовании: достаточно в один клик установить загрузочный раздел, а затем в автоматически созданный пустой раздел положить загрузочный(-е) .iso-образ(-ы). Работает с MBR и GPT (не всегда корректно). Если вы копируете образ на флешку из-под Linux, после копирования **обязательно выполните синхронизацию (sync) раздела.**

### ⬇️ Управление файлами и загрузками
* [NanaZip.](https://github.com/M2Team/NanaZip) Форк 7-Zip с модернизированным интерфейсом.
* [Free Download Manager.](https://freedownloadmanager.org/ru/) Удобный менеджер загрузок.
* [qBittorrent.](https://fosshub.com/qBittorrent.html) Загрузка торрентов.
* [cppcryptfs.](https://github.com/bailey27/cppcryptfs) Управление файлами, зашифрованными с помощью Gocryptfs.

### 💡 Полезное
* [MacType.](https://github.com/snowie2000/mactype) Альтернативный рендеринг шрифтов. Полезен на экранах с разрешением FHD и ниже.
* [PowerToys.](https://github.com/microsoft/PowerToys) Что-то вроде [сборника утилит всё-в-одном](https://github.com/microsoft/PowerToys#about) от Microsoft.
* [Sysinternals Suite.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) Ещё один набор мелких утилит. Можно скачать всё разом, [либо необходимое по отдельности.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite#introduction)

## ✈️ Telegram
* [AyuGram Desktop.](https://github.com/AyuGram/AyuGramDesktop) Клиент без рекламы [с большим количеством полезных функций,](https://docs.ayugram.one/desktop/) часть которых нарушает ToS. Будьте осторожны, существует риск блокировки аккаунта.
* [64Gram.](https://github.com/TDesktop-x64/tdesktop) Легкий клиент [c базовыми функциями](https://github.com/TDesktop-x64/tdesktop/blob/dev/features.md) и небольшим количеством эксклюзивных дополнений (например, конвертирование чатов в супергруппы).
* [Unigram.](https://github.com/UnigramDev/Unigram) UWP-клиент c Fluent дизайном. Анимации подтормаживают уже не так сильно, как раньше, и в целом клиент юзабельный. Но все ещё сильно уступает Telegram Desktop по удобству и быстродействию. 

## 👾 Discord

Существует два актуальных варианта:
1. [Vesktop.](https://github.com/Vencord/Vesktop) Discord с встроенным [Vencord,](https://vencord.dev) предоставляющим широкую поддержку полезных плагинов и тем от сообщества. С клиентом Vesktop нет необходимости вручную переустанавливать модификацию каждый раз, когда обновляется база Discord. Очень лёгкий, работает быстрее оригинального клиента. Это также и более приватный вариант, поскольку клиент не имеет никакого доступа к системе.
2. Связка из оригинального клиента Discord, Vencord и [OpenAsar.](https://openasar.dev) Суть последнего заключается в существенном повышении общей производительности Discord, включая ускорение холодного старта программы. В конфигурации OpenAsar можно выбрать режим производительности: для настольных ПК/при подключенном питании рекомендуется использовать Performance, в ином случае Balanced.

Установку производим через [инсталлер Vencord.](https://github.com/Vencord/Installer/releases/latest/download/VencordInstaller.exe) Важно: сохраните его в любом удобном для Вас месте. Иногда Vencord (и реже OpenAsar) слетают после обновления Discord, в таком случае нужно заново запустить установщик и переустановить их кнопками **Install Vencord** или **Reinstall / Repair** и **Install OpenAsar.** Это восстановит моды со всеми вашими настройками, плагинами и темами.  
> [!WARNING]
> В последнее время участились случаи, когда Discord после холодного старта висит на сплеше и ни на что не реагирует, при том перезапуск приложения не помогает. Это происходит из-за Vencord. Запустите VencordInstaller и переустановите нужные модификации, после этого всё заработает. Кстати, иногда процесс установки OpenAsar немного тупит (например, жалуется на то, что процесс занят) – просто несколько раз подряд кликайте на установку, и это действительно сработает. ¯\\\_(ツ)_/¯

### Темы

<details>

<summary>Установка через Vencord (проще)</summary>

Настройки Discord, раздел Vencord → Themes → Online Themes. Поместите прямую ссылку к .css темы в поле ввода и переключите вкладку.

</details>

<details>

<summary>Установка через OpenAsar (лучше)</summary>

Настройки Discord → OpenAsar → Theming.  
1. Перейдите в репозиторий нужной темы.
2. В поиск по репо введите `@import url`.
3. Найдите основной файл в формате .css, **который состоит только из импорта ссылки на ресурсы темы и настроек.** Если такого нет среди файлов самого репозитория, то поищите его в релизах.
4. Скопируйте содержимое файла в поле ввода раздела Theming.  

</details>

* [Fluent Discord.](https://github.com/TakosThings/Fluent-Discord) Тема, выполненная под стиль Microsoft Fluent Design (как в Windows 11). [Превью.](https://raw.githubusercontent.com/TakosThings/Fluent-Discord/develop/images/ui-1.5.5.png)  
Можно заменить фон приложения на свой (в соответствии с обоями рабочего стола, например). Для этого замените содержимое в скобках параметра `--fluent-acrylic-background: url` на прямую ссылку к картинке.

### 🎧 Медиапроигрыватели и стриминговые сервисы

___
* Spotify:

**Софт**
1. [Spicetify](https://github.com/spicetify/spicetify-cli):
   * [Сразу устанавливаем Spicetify с Маркетплейсом одной командой.](https://github.com/spicetify/spicetify-marketplace/wiki/Installation)  
     Дальнейшая установка производится в основном только через меню Маркетплейса → Расширения. Этот метод установки подразумевает дальнейшее автоматическое обновление расширений по мере поступления апдейтов.
   * Установка Spicetify добавляет меню экспериментальных функций клиента (не меняя ничего по умолчанию). Используйте осторожно!  
   * Для пользователей без Premium-подписки → [Adblock.](https://github.com/CharlieS1103/spicetify-extensions/blob/main/adblock/README.md)

2. [SpotX](https://github.com/amd64fox/SpotX) (отключение рекламы для пользователей без Premium и активация экспериментальных функций; установка либо [автоматическая,](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat) либо через выбор необходимых флагов [вручную](https://github.com/amd64fox/SpotX/discussions/60)). Не рекомендуется использовать вместе со Spicetify.  
* [volt.fm.](https://volt.fm) Сервис сбора и анализа статистики вашего прослушивания. Предоставляет огромное количество полезных данных по жанрам, категориям, промежуткам времени.  
* [Google-таблица с прямыми ссылками на загрузку оффлайн-установщика всех версий Spotify для Windows.](https://docs.google.com/spreadsheets/d/1wztO1L4zvNykBRw7X4jxP8pvo11oQjT0O5DvZ_-S4Ok)
* [Скрипт блокировки обновлений настольного клиента Spotify.](https://github.com/amd64fox/Rollback-Spotify)
* [Полное удаление клиента Spotify из системы.](https://github.com/amd64fox/Uninstall-Spotify)  

___

* [Взломанная Яндекс Музыка.](https://github.com/slavrom21/YMReleases)

## 🔧 CLI-утилиты
>
> [!NOTE]
> Для удобства использования рекомендуется прописать путь к .exe файлу приложения (или к папке, хранящей исполняемые файлы всех приложений) в переменные среды PATH. [Как это сделать](https://remontka.pro/add-to-path-variable-windows)  
Либо установить эти утилиты через Winget/Chocolatey/Scoop (рекомендуется!).  

* [aria2c.](https://aria2.github.io/) Аналог wget, Download Master и прочих. Поддерживает торренты.
* [ffmpeg.](https://ffmpeg.org/) Конвертер аудио и видео файлов, имеет много фич.
* [yt-dlp.](https://github.com/yt-dlp/yt-dlp) Загрузчик видео и аудио с YouTube, SoundCloud, PornHub и еще [с 1838 сайтов.](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md) Рекомендуется использовать через Hitomi Downloader (см. [в разделе Полезное](https://github.com/reddxae/list/blob/main/list/useful.md#Мультиплатформенные-программы)).
* [payload-dumper-go.](https://github.com/ssut/payload-dumper-go) Быстрая разборка payload.bin Android-прошивок на отдельные образы.
* [Revancify.](https://github.com/decipher3114/Revancify#installation) Удобная сборка и установка ReVanced/ReVanced Extended через Termux.
* [Chocolatey.](https://community.chocolatey.org/) Пакетный менеджер для Windows в стиле линуксовских apt/pacman. Мощнее встроенного Winget.
* [Scoop.](https://scoop.sh/) Аналог Chocolatey. В отличии от последнего, устанавливает программы не в систему, а в отдельную папку юзера (`%USERPROFILE%/scoop`), некие "полу-портативные" версии, которые потом легко удалить. 

## ⏹ Скрипты
* [OfflineInsiderEnroll.](https://github.com/abbodi1406/offlineinsiderenroll) Доступ к Windows Insider Program без аккаунта Microsoft.
* [Platform Tools Installer.](https://github.com/SunsetTechuila/Platform-Tools-Installer) Скрипт автоматически скачивает актуальные [Platform tools](https://developer.android.com/tools/releases/platform-tools) для вашей OC, предлагает выбрать место для распаковки, после чего добавляет их в PATH.

## 🗂 Модификация интерфейса Windows через .reg-файлы
* [Скрыть стрелку с ярлыков на рабочем столе.](https://www.elevenforum.com/t/remove-shortcut-arrow-icon-in-windows-11.3814/) Перемещаем файл Blank.ico в корневую папку Windows и запускаем RemoveArrow.bat; перезагружаем Проводник. Чтобы откатить изменения, запускаем RestoreArrow.bat.

## ⚒️ Решение проблем
* 🔵 Регулярные отвалы Bluetooth и подключенных устройств:  
Перейдите в Диспетчер устройств → разверните категорию «Bluetooth» → найдите ваш Bluetooth-адаптер (например, Intel® Wireless Bluetooth®) и откройте его параметры → перейдите в раздел «Управление электропитанием» → снимите галочку с «Разрешить отключение этого устройства для экономии энергии» и сохраните изменения. Устройства автоматически переподключатся.
* 📶 Отвал Wi-Fi при использовании дискретной видеокарты:  
Перейдите в Диспетчер устройств → разверните категорию «Сетевые адаптеры» → найдите ваш адаптер Wi-Fi (например, Intel® Wireless-AC 9560 – кстати, чаще всего указанная проблема возникает именно с ним) и откройте его параметры → перейдите в раздел «Дополнительно» → найдите параметры «Ширина канала для 2,4 ГГц» и «Ширина канала для 5 ГГц». Для обоих параметров, в выпадающем меню задайте значение **20 МГц.** Сохраните изменения.
* 🔐 BitLocker запрашивает пароль после полного выключения компьютера/неожиданного завершения работы:  
Вероятно, BitLocker не сохранил ключ в TPM вашего компьютера (так случилось у меня). В любом случае, стоит попробовать перезаписать его:
  * Запустите Терминал от имени администратора и выполните команду `manage-bde -protectors -add c: -tpm`. Если вы получили сообщение об успехе, **выключите компьютер через «Завершение работы»,** а не перезагрузкой, и проверьте дефект.
  * Если это не помогло или произошла ошибка, выполните команду `manage-bde -protectors -delete c: -t TPM`. Это очистит уже имеющуюся запись, если она существует. Перезагрузите компьютер и перезапишите ключ с помощью команды `manage-bde -protectors -add c: -tpm`. Теперь **выключите компьютер через «Завершение работы»** и проверьте дефект снова.
