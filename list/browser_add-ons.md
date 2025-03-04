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

* [SponsorBlock.](https://sponsor.ajay.app/) Автоматически пропускает любые рекламные секции в видео на YouTube. Это community-powered проект, т.е. вы можете самостоятельно отмечать секции для пропуска, которые будут распространены для всех пользователей.
* [Tampermonkey.](https://tampermonkey.net/index.php?locale=ru) Пользовательские скрипты для страниц.  

Скрипты/расширения для Tampermonkey:  
<sup>(кликайте по названию для установки; везде поддерживается авто-обновление)</sup>

1. [AdGuardExtra.](https://userscripts.adtidy.org/release/adguard-extra/1.0/adguard-extra.user.js) *Блокировка попыток обхода блокировки рекламы...* Да, именно так. Работает для YouTube [и многих других сайтов.](https://github.com/AdguardTeam/AdGuardExtra#websites-where-adguard-extra-can-be-useful)
2. [Voice-Over-Translation.](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot.user.js) Автоматический закадровый перевод видео в реальном времени, свободный порт из Яндекс Браузера.
3. [Блокировка Anti-Adblock баннера на Aternos](https://gist.github.com/DvilMuck/f2b14f3f65e8f22974d781277158f82a/raw/66a0d8d9dd598fc516c3c9d9bbf6ef3f0f6a7a1e/aternosAntiAntiadblock.user.js)

* [ClearURLs.](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) Автоматически очищает URL страницы от трекинг-содержимого.
* [Dark Reader.](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh) Динамическая покраска сайтов в тёмные тона. Маст-хев, множество настроек.
* [Search by Image.](https://chrome.google.com/webstore/detail/search-by-image/cnojnbdhbhnkbcieeekonklommdnndci) Поиск по картинке. Предустановлено большое количество сервисов для поиска, также можно добавлять свои.
* [User-Agent Switcher and Manager.](https://chrome.google.com/webstore/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) Позволяет быстро подменить user-agent<sup>[`ℹ️`](https://ru.wikipedia.org/wiki/User_agent)</sup> вашего девайса.
* [Old Genius (Song Page Switcher).](https://chrome.google.com/webstore/detail/old-genius-song-page-swit/dgdnchkkkknfdahaehnkfifchgnoidjj) Автоматически возвращает старую версию дизайна страницы текста на [Genius.](https://genius.com) В скором времени поддержка старой версии страницы может быть отключена со стороны сайта.
* [Stylus.](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) Пользовательские стили для сайтов.
* [TosDR.](https://github.com/tosdr/browser-extensions) Расширение одноимённого сайта.<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/useful.md#:~:text=%D1%81%D0%BB%D0%B8%D1%88%D0%BA%D0%BE%D0%BC%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%BE%D0%B3%D0%BE%20%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%80%D0%B0.-,tosdr,-.%20%D0%9F%D1%80%D0%B5%D0%B4%D0%BE%D1%81%D1%82%D0%B0%D0%BB%D0%B2%D1%8F%D0%B5%D1%82%20%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D1%83%D1%8E%20%D0%B8%D0%BB%D0%B8)</sup>
* [Web Archives.](https://chrome.google.com/webstore/detail/web-archives/hkligngkgcpcolhcnkgccglchdafcnao) Быстрый переход к сохранённым копиям сайта/его версиям на archive.org (Wayback Machine).
* [Allow Right Click.](https://webextension.org/listing/allow-right-click.html) Добавляет возможность выделять и копировать текст/контент на сайтах, которые это блокируют.
* [SponsorBlock.](https://sponsor.ajay.app/) Автоматический пропуск рекламы в видео, отрывки (таймкоды) которой указывает сообщество.
* [Return YouTube Dislike.](https://www.returnyoutubedislike.com/) Возвращает отображение количества дизлайков под видео.<sup>[`ℹ️`](https://www.returnyoutubedislike.com/faq)</sup>
* [Enchancer for YouTube.](https://chromewebstore.google.com/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle) Кастомизация страницы и плеера YouTube.

<details>

<summary>Enhancer for YouTube</summary>

Переходим в настройки расширения, активируем пункт «Пользовательская тема» и вставляем код. Сохраняем. Изменения применяются без необходимости в перезагрузке страницы.

Убираем новый уродливый градиент в плеере и элементах интерфейса:

```css
.ytp-swatch-background-color,
#progress.ytd-thumbnail-overlay-resume-playback-renderer,
#progress.yt-page-navigation-progress,
.yt-spec-avatar-shape--live-ring::after,
.ytProgressBarLineProgressBarPlayedRefresh,
.ytp-play-progress {
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
.ytp-cued-thumbnail-overlay,
.ytp-cued-thumbnail-overlay-image {
   background-size: contain !important;
   background-position: center !important;
   background-repeat: no-repeat !important;
}
```

Скрываем не относящиеся к поисковому запросу разделы ("Новые каналы для вас", "Новые видео для вас", "Зрители также посмотрели" и т.п.) на странице поиска:

```css
.ytd-search ytd-shelf-renderer:has([id="dismissible"]) {
   display: none !important;
}
```

</details>

* [БотНадзор для VK.](https://botnadzor.org/docs/extension) Подсвечивание комментариев от кремлеботов. 

### Темы

* [Just Black.](https://chrome.google.com/webstore/detail/just-black/aghfnjkcakhmadgdomlmlhhaocbkloab?hl=ru) Простая и минималистичная тема в тёмных тонах для браузеров на Chromium.  
* *(Windows 11)* Включаем эффект Mica в Microsoft Edge: переходим по ссылке `edge://flags/#edge-visual-rejuv-mica`, активируем флаг, перезапускаем браузер.
* [WaveFox.](https://github.com/QNetITQ/WaveFox) Кастомизация внешнего вида Firefox.
* [Geckium.](https://github.com/angelbruni/Geckium) CSS/JS тема для Firefox в стиле старых версий Chrome (~1.0-58).

### Прочие надстройки
* [Bettefox.](https://github.com/yokoffing/Betterfox) Подборка твиков для Firefox, ориентированных на производительность.
