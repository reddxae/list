# 🌐 Браузерные дополнения:

### Расширения

* [uBlock Origin.](https://ublockorigin.com/ru) Самый популярный свободный блокировщик рекламы. В представлении не нуждается.  

<details>

<summary>Пользовательские фильтры для uBlock</summary>

Как добавить: тапаем по иконке uBlock Origin → открываем панель управления (клик по шестерёнке) → Списки фильтров → активируем нужное (можно сразу всё). Применяем изменения.  
Далее переходим в раздел Мои фильтры → копируем и вставляем код, указанный ниже. Снова применяем изменения.

### Aternos

* Anti-Adblock баннер
```
@@||aternos.org^$shide
```

### Яндекс

* Реклама на страницах поиска и картинок
```
/^ya\.ru|yandex/##div[class*="-Incut"]
/^ya\.ru|yandex/###search-result > li:has(div[class*="Organic"]:not([class*="Title"]) > *:has-text(/^[РP]{1}[еe]{1}кл[аa]{1}м[аa]{1}$/i))
/^ya\.ru|yandex/##div:has(> .ImagesViewer-SidebarAdv)
/^ya\.ru|yandex/##div:has(> #ImagesViewer-SidebarAdv)
/^ya\.ru|yandex/##.ImagesViewer-LayoutFooter:has(.CommercialProduct)
/^ya\.ru|yandex/##.ImagesViewer-LayoutSideblock > div > div > div:not(:has(.MMViewerButtons))
/^ya\.ru|yandex/##.ProductGallery
/^ya\.ru|yandex/##.i-mini-bem:has([class*="tgo__mark"]:has-text(/^[РP]{1}[еe]{1}кл[аa]{1}м[аa]{1}$/i))
```

* Реклама на странице погоды. Убирает современный вид страницы, возвращая сводку по дням
```
yandex.*##:matches-path(/pogoda) #content_right
yandex.*##:matches-path(/pogoda) .blog-widget
yandex.*##:matches-path(/pogoda) [role="main"] > :not(#content_left, [data-bem*="/pogoda"])
yandex.*##:matches-path(/pogoda) .card:not(:has(.weather-table))
yandex.*##:matches-path(/pogoda) [data-bem*="segment-details"] > :not(article)
yandex.*##:matches-path(/pogoda) #__next > [data-overlay-container="true"] > div > div:has(main) > div
yandex.*##:matches-path(/pogoda) #__next > [data-overlay-container="true"] main > div:not(:has(nav)) > div:not(:has(article, ul))
yandex.*##:matches-path(/pogoda) #__next > [data-overlay-container="true"] main > div:not(:has(nav)) > div:has(ul) > div > div:not(:has(article, button))
yandex.*##:matches-path(/pogoda) .pro-entry-points
yandex.*##:matches-path(/pogoda) .header-b2b__menu-item
yandex.*##:matches-path(/weather) #content_right
yandex.*##:matches-path(/weather) .blog-widget
yandex.*##:matches-path(/weather) [role="main"] > :not(#content_left, [data-bem*="/weather"])
yandex.*##:matches-path(/weather) .card:not(:has(.weather-table))
yandex.*##:matches-path(/weather) [data-bem*="segment-details"] > :not(article)
yandex.*##:matches-path(/weather) #__next > [data-overlay-container="true"] > div > div:has(main) > div
yandex.*##:matches-path(/weather) #__next > [data-overlay-container="true"] main > div:not(:has(nav)) > div:not(:has(article, ul))
yandex.*##:matches-path(/weather) #__next > [data-overlay-container="true"] main > div:not(:has(nav)) > div:has(ul) > div > div:not(:has(article, button))
yandex.*##:matches-path(/weather) .pro-entry-points
yandex.*##:matches-path(/weather) .header-b2b__menu-item
```

* Кнопка вызова Алисы
```
ya.ru##.alice-fab
/^ya\.ru|yandex/##.AliceFabButton
```

### YouTube
* Кнопка "Спасибо/Thanks" под плеером
```
##yt-button-shape > button[aria-label="Thanks"]
```

</details>

* [SponsorBlock.](https://sponsor.ajay.app/) Автоматически пропускает любые рекламные секции в видео на YouTube. Полностью community-powered, вы можете сами добавлять метки и загружать рекламные секции для пропуска по своему усмотрению.
* [Track24.](https://chrome.google.com/webstore/detail/track24ru/lfijgegefgcgbfcgjgnhnkclenhfijhk?hl=ru) Удобное расширение для отслеживания посылок в браузере.
* [Tampermonkey.](https://tampermonkey.net/index.php?locale=ru) Реализация работы пользовательских скриптов в вашем браузере.  

Скрипты/расширения для Tampermonkey:  
<sup>(кликайте по названию для установки; везде поддерживается авто-обновление)</sup>

1. [AdGuardExtra.](https://userscripts.adtidy.org/release/adguard-extra/1.0/adguard-extra.user.js) *Блокировка попыток обхода блокировки рекламы...* Да, именно так. Работает для YouTube [и многих других сайтов.](https://github.com/AdguardTeam/AdGuardExtra#websites-where-adguard-extra-can-be-useful)
2. [Voice-Over-Translation.](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot.user.js) Автоматический закадровый перевод видео в реальном времени, свободный "порт" из Яндекс Браузера.

* [ClearURLs.](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) Автоматически очищает URL страницы от трекинг-содержимого.
* [Dark Reader.](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh) Хорошее расширения для автоматической перекраски сайтов в тёмные тона. Маст-хев, множество настроек.
* [Search by Image.](https://chrome.google.com/webstore/detail/search-by-image/cnojnbdhbhnkbcieeekonklommdnndci) Приятный интерфейс, большое количество сервисов для поиска, можно добавлять свои. Небольшой дополнительный функционал. Пробуйте.
* [User-Agent Switcher and Manager.](https://chrome.google.com/webstore/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) Позволяет быстро подменить useragent вашего девайса.
* [Old Genius (Song Page Switcher).](https://chrome.google.com/webstore/detail/old-genius-song-page-swit/dgdnchkkkknfdahaehnkfifchgnoidjj) Автоматически и без задержек (релоада) возвращает старую версию дизайна страницы текста на Genius.com.
* [Stylus.](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) Пользовательские стили для сайтов.
* [TosDR.](https://github.com/tosdr/browser-extensions) Расширение одноимённого сайта (описание есть в соответствующей категории).
* [Web Archives.](https://chrome.google.com/webstore/detail/web-archives/hkligngkgcpcolhcnkgccglchdafcnao) Быстрый переход к сохранённым копиям сайта/его версиям на archive.org (Wayback Machine).
* [Enable Right Click & Copy.](https://chrome.google.com/webstore/detail/absolute-enable-right-cli/jdocbkpgdakpekjlhemmfcncgdjeiika) Добавляет возможность выделять и копировать текст/контент на сайтах, которые это блокируют. Параметр Enable Copy разрешает копировать текст; Absolute Mode отключает защиту от копирования любого контента.
* [SponsorBlock.](https://sponsor.ajay.app/) Автоматический пропуск рекламы в видео, отрывки (таймкоды) которой указывает сообщество.
* [Return YouTube Dislike.](https://www.returnyoutubedislike.com/) Возвращает отображение количества дизлайков под видео.<sup>[`ℹ️`](https://www.returnyoutubedislike.com/faq)</sup>
* [Enchancer for YouTube.](https://chromewebstore.google.com/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle) Кастомизация страницы и плеера YouTube.

<details>

<summary>Enhancer for YouTube</summary>

Переходим в настройки расширения, активируем пункт «Пользовательская тема» и вставляем код. Сохраняем. Изменения применяются без необходимости в перезагрузке страницы.

Убираем новый уродский градиент в плеере и элементах интерфейса:

```css
.ytp-swatch-background-color,
#progress.ytd-thumbnail-overlay-resume-playback-renderer,
#progress.yt-page-navigation-progress,
.yt-spec-avatar-shape--live-ring::after,
.ytProgressBarLineProgressBarPlayedRefresh {
   background: #f03 !important;
   background-color: #f03 !important;
}
#yt-ringo2-svg_yt10 path:first-of-type {
   fill: #f03 !important;
}
```

Исправляем пропорции превью на странице воспроизведения:

```css
.html5-video-player,
.ytp-cued-thumbnail-overlay {
   background-size: contain !important;
   background-position: center !important;
   background-repeat: no-repeat !important;
}
```

</details>

### Темы

* [Just Black.](https://chrome.google.com/webstore/detail/just-black/aghfnjkcakhmadgdomlmlhhaocbkloab?hl=ru) Простая и минималистичная тема в тёмных тонах от Google.  
* *(Windows 11)* Включаем эффект Mica в Microsoft Edge: переходим по ссылке `edge://flags/#edge-visual-rejuv-mica`, активируем флаг, перезапускаем браузер.
* [WaveFox.](https://github.com/QNetITQ/WaveFox)
* [Geckium.](https://github.com/angelbruni/Geckium)

### Производительность
* [Bettefox.](https://github.com/yokoffing/Betterfox)
