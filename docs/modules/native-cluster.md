# Русский интерфейс нативной приборки

[Все модули](../../README.md)

Русские подписи и предупреждения водительской панели, а также правки разметки для нативного Linux HMI приборки.

## Скачать и установить

- [Установщик Windows x64](https://github.com/LuckDMST/qiyuan-q05-mods/releases/download/cluster-native-ru-2026-11-20_15/Qiyuan-Q05-B216-Cluster-RU-Windows.zip). Распакуйте ZIP и запустите `Start.cmd`. Python и ADB уже в комплекте.
- [Инструкция по установке и восстановлению](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/cluster-native-ru-2026-11-20_15).
- [Архив ресурсов Linux HMI для ручной установки](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/cluster-native-ru-2026-11-16_14).

Поддерживаемая сборка головного устройства B216 — `SWC.1371.RB216000004`.

Опубликованный установщик `_15` требует root-доступа к Android shell и root Linux HMI приборки. Rootless-кандидат `_02` собран локально, офлайн пройдены 41 транзакционный и 5 транспортных сценариев. Он не опубликован и не проверен на автомобиле; root Linux T-Box всё равно необходим для изменения ресурсов.

## Скриншоты до и после

Кадры сняты 20 ноября 2026 года на одном Qiyuan Q05 LU+ с ГУ B216. В каждой паре открыта одна и та же карточка. Автомобиль стоит в P, скорость 0 км/ч, выбран режим «Эко» и тёмная тема. Между съёмками изменились часы, заряд, температура и время поездки. Нажмите на кадр, чтобы открыть оригинал 1920×532.

| Экран | Штатные ресурсы | Русский перевод |
| --- | --- | --- |
| Мощность | [![Мощность: штатный экран](../../screenshots/cluster/release-2026-11-20_15/power-zh.png)](../../screenshots/cluster/release-2026-11-20_15/power-zh.png) | [![Мощность: русский перевод](../../screenshots/cluster/release-2026-11-20_15/power-ru.png)](../../screenshots/cluster/release-2026-11-20_15/power-ru.png) |
| Текущая поездка | [![Текущая поездка: штатный экран](../../screenshots/cluster/release-2026-11-20_15/trip-zh.png)](../../screenshots/cluster/release-2026-11-20_15/trip-zh.png) | [![Текущая поездка: русский перевод](../../screenshots/cluster/release-2026-11-20_15/trip-ru.png)](../../screenshots/cluster/release-2026-11-20_15/trip-ru.png) |
| Давление в шинах | [![Давление в шинах: штатный экран](../../screenshots/cluster/release-2026-11-20_15/tires-zh.png)](../../screenshots/cluster/release-2026-11-20_15/tires-zh.png) | [![Давление в шинах: русский перевод](../../screenshots/cluster/release-2026-11-20_15/tires-ru.png)](../../screenshots/cluster/release-2026-11-20_15/tires-ru.png) |
| Средняя скорость | [![Средняя скорость: штатный экран](../../screenshots/cluster/release-2026-11-20_15/average-speed-zh.png)](../../screenshots/cluster/release-2026-11-20_15/average-speed-zh.png) | [![Средняя скорость: русский перевод](../../screenshots/cluster/release-2026-11-20_15/average-speed-ru.png)](../../screenshots/cluster/release-2026-11-20_15/average-speed-ru.png) |

## Что проверили на машине

На архиве Linux HMI `2026-11-16_14` проверили перевод, предупреждения и состояния приборки, включая запас хода и заряд, давление в шинах и страницы самопроверки. Установщик `_15` содержит русские ресурсы той же версии.


## Экран во время зарядки

Кадр снят 20 ноября 2026 года во время зарядки. Это отдельный снимок для истории проекта, не часть сравнения штатных и русских ресурсов.

![Приборка на русском языке во время зарядки](../../screenshots/cluster/charging-2026-11-20.png)
