# 🚫 Обход блокировок

## VPN
* [**Настройка личного сервера.**](https://github.com/reddxae/unrestrict) Это платно (совсем не дорого), но надёжно. Рекомендуем использовать Promo (~1,1€/мес.) или Shared (~5€/мес.) VPS в европейских локациях от хостинга [aéza.](https://aeza.net/)

___
Варианты ниже могут быть менее безопасными (например, по части вашей анонимизации перед интернет-провайдером, так и с подозрением на утечку трафика третьим лицам) и сильно менее надёжными (уязвимые к блокировкам или попросту нестабильные). 
___

## [Умный обход DPI](https://github.com/ValdikSS/GoodbyeDPI)
Обход систем глубокой проверки пакетов на [ТСПУ.](https://www.ordercom.ru/analitika/suvenirans#:~:text=%C2%AB%D0%A2%D0%A1%D0%9F%D0%A3%C2%BB%2C%20%E2%80%94%20%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2%D0%B0,5.1.)

### Windows
1. [Скачиваем последнюю версию GoodbyeDPI со страницы релизов.](https://github.com/ValdikSS/GoodbyeDPI/releases)
2. Переносим папку в любую точку на диске, откуда впоследствии папку удалять не будем.
3. Берём свежие листы:
   * Под VPN заходим по адресу [antizapret.prostovpn.org/domains-export.txt](https://antizapret.prostovpn.org/domains-export.txt) и сохраняем файл в раннее скачанную папку с именем `russia-blacklist.txt`.
4. В зависимости от ваших предпочтений, от имени администратора запускаем:
   * `1_russia_blacklist.cmd`
   * `1_russia_blacklist_dnsredir.cmd` c перенаправлением DNS-резолвера на DNS Яндекса.

Это установит сервис GoodbyeDPI в Windows, он будет запускаться автоматически вместе с системой. Чтобы удалить, воспользуйтесь `service_remove.cmd`.

[Обсуждение обхода замедления YouTube в России](https://github.com/ValdikSS/GoodbyeDPI/issues/378)

### Android
* [DPI Tunnel.](https://github.com/nomoresat/DPITunnel-android) Для работы необходимы root-права. Запускается как отдельный сервис (не через VPN) и работает в фоне. Есть два режима: HTTP (преимущественно для браузеров, работает по всей системе) и Прозрачный для конкретных приложений. Можно задать собственные списки переопределения IP-адресов для крупных заблокированных сайтов (например, Instagram), поддерживается туннелирование и настройка профилей под конкретных операторов, что, как правило, не требуется.

<details>

<summary>Обход блокировки сервисов Meta</summary>

Сохраните список в текстовый файл и выгрузите его в приложение (тапом по иконке выгрузки), пункты будут заполнены автоматически.
За подборку спасибо [inkanusgray.](https://4pda.to/forum/index.php?showuser=4007197)

```
edge-chat.facebook.com 157.240.200.16
graph.facebook.com 157.240.200.16
mbasic.facebook.com 157.240.200.16
touch.facebook.com 157.240.200.16
instagram.com 157.240.200.174
www.instagram.com 157.240.200.174
b.i.instagram.com 157.240.200.174
facebook.com 157.240.200.35
www.facebook.com 157.240.200.35
fb.com 157.240.200.35
m.facebook.com 157.240.200.35
api.instagram.com 157.240.200.63
i.instagram.com 157.240.200.63
graph.instagram.com 157.240.200.63
static.cdninstagram.com 157.240.200.63
edge-chat.instagram.com 157.240.200.63
scontent-hel3-1.cdninstagram.com 157.240.200.63
scontent.cdninstagram.com 157.240.200.63
l.instagram.com 157.240.200.63
threads.net 157.240.200.63
www.threads.net 157.240.200.63
scontent-hel3-1.xx.fbcdn.net 157.240.200.14
static.xx.fbcdn.net 157.240.200.14
scontent.xx.fbcdn.net 157.240.200.14
connect.facebook.net 157.240.200.14
gateway.facebook.com 157.240.200.3
gateway.instagram.com 157.240.200.3
gateway.threads.net 157.240.200.3
```

</details>

Не рекомендуется использовать глобальный режим в DPI Tunnel на Android ввиду агрессивной реакции банковских приложений (например, Mir Pay автоматически стирает все карты и блокирует все функции). Вместо этого используйте прозрачный режим с выборочным туннелированием необходимых приложений.

* [ByeDPIAndroid.](https://github.com/dovecoteescapee/ByeDPIAndroid/) Не нужны root-права: обход DPI работает через VPN, локально пропуская трафик через [ByeDPI.](https://github.com/hufrea/byedpi)
* [Плагин ByeDPI для NekoBox.](https://github.com/hufrea/byedpi-neko/releases)

[Варианты для других платформ можно найти здесь.](https://github.com/ValdikSS/GoodbyeDPI#similar-projects)

<details>

<summary>Другое</summary>

## Tor
Вкратце то, что из себя представляет сеть Tor, можно описать как огромную систему прокси-серверов, позволяющую устанавливать анонимное сетевое соединение из любой точки Интернета.
* [Tor Browser.](https://tor.calyxinstitute.org/download/) Самый простой и очевидный юзкейс Tor в оформлении фирменного браузера, также включающего в себя различные уровни защиты от трекеров и другой слежки. 
* [Tor Bridges.](https://bridges.torproject.org/) Запрос мостов для обхода блокировки сети Tor (необходимо для России). Мосты можно получить по электронной почте, отправив пустое письмо на адрес bridges@torproject.org (только с ящиков Gmail).
* [Tor Control Panel.](https://github.com/abysshint/tor-control-panel/blob/main/README.ru.md#readme-top) Управление и мониторинг сети Tor в Windows (Tor Expert Bundle).

## Прокси
Списки бесплатных прокси (они могут быть небезопасны!). Такими стоит пользоваться только в крайнем случае.  
* [hidemyname](https://hidemy.io/ru/proxy-list/)  
* [SPYS.ONE](https://spys.one/)

### [MTProto для Telegram](https://core.telegram.org/mtproto)
* [Рекомендуем поднять собственный MTProto.](https://github.com/reddxae/unrestrict#mtproto)
* [MTProxyStar.](https://t.me/MTProxyStar) Свежие прокси. Низкий пинг, работают стабильно.

</details>
