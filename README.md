Здесь хранятся версии модулей, которые мы сделали сами/модифицировали, а так же те, что трудно найти на просторах Интернета. 

## Disable Logs
Модифицированная версия [модуля от mrfrost475.](https://4pda.to/forum/index.php?showtopic=915158&st=220#entry105651495)

Что сделано:

- Удалены опасные перманентные чистки / изменения, приводящие к обнаружению ресетпропов.
- Убрана очистка кэша превью фотографий.
- Убрано отключение logd, чтобы предотвратить внутренний логоспам в LSPosed.
- Отключены логи говернора.
- Добавлено предупреждение с запросом подтверждения установки по нажатии кнопки громкости.
- По умолчанию отключен tcpdump, если он вам нужен, закомментируйте строку `stop tcpdump` в `service.sh`.

>
> [!CAUTION]
> На некоторых прошивках модуль приводит к бутлупу или перезагрузке в fastboot. Пожалуйста, сохраните важные данные перед установкой, а лучше и вовсе проверьте работоспособность на чистой системе перед использованием на основном сетапе.

[Скачать модуль](https://github.com/reddxae/list/blob/files/disable_logs.zip)

## Split Shade (широко известен как BetterQS)
Удобная разметка панели быстрого доступа и уведомлений при горизонтальной ориентации экрана. [Превью.](https://github.com/reddxae/list/blob/files/betterqs_preview.png)  

Что сделано:
- Убран бесполезный сброс варианта выреза в экране на nocutout.
- Упрощение скриптов, поддержка KernelSU.

[Скачать модуль](https://github.com/reddxae/list/blob/files/split-shade.zip)

## Disable Ripple On Unlock
Отключает анимацию волны при разблокировке экрана (Android 12+).

[Скачать модуль (LSPosed)](https://github.com/reddxae/list/blob/files/disable_ripple_on_unlock.apk)

## Wallpaper Zoom Animation Disabler
Отключает анимацию приближения/отдаления обоев при разблокировке экрана и запуске/сворачивании приложений (Android 11+).

[Скачать модуль](https://github.com/reddxae/list/blob/files/wall_zoom_anim_disabler.zip)

## Magical OverlayFS
Поддерживает новые версии Magisk, APatch и KernelSU.

[Скачать модуль](https://github.com/reddxae/list/blob/files/magisk-overlayfs-v3.2.2-fixed.zip)  
