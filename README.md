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

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/disable_logs.zip)

## Split Shade (BetterQS)
Эстетически правильная и удобная разметка панели быстрого доступа при горизонтальной ориентации экрана. [Превью.](https://github.com/begoniacommunity/list/blob/files/betterqs_preview.png)  

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/better_qs.zip)

## LSPosed No Logs
LSPosed с поддержкой Android 15+ без внутренних логов, что позволяет избежать обнаружения приложениями.  

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/lsposed_no-logs.zip)

## Disable Ripple On Unlock
Отключает анимацию волны при разблокировке экрана (Android 12+).

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/disable_ripple_on_unlock.apk)

## Wallpaper Zoom Animation Disabler
Отключает анимацию приближения/отдаления обоев при разблокировке экрана и запуске/сворачивании приложений (Android 11+).

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/wall_zoom_anim_disabler.zip)

## Magical OverlayFS
Поддерживает новые версии Magisk, APatch и KernelSU.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/magisk-overlayfs-v3.2.2-fixed.zip)  
[Ещё один актуализированный вариант](https://github.com/backslashxx/magic_overlayfs/tree/maintenance/magisk-module)
