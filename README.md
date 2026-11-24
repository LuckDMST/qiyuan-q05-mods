# Changan Qiyuan Q05 LU+ — русификация и модули

Этот проект помогает пользоваться русским интерфейсом на центральном экране и приборке Changan Qiyuan Q05 Laser Ultra Plus. Здесь собраны Android-модули, установщик для приборки, аудиопримеры и понятные инструкции.

Откройте страницу нужного модуля: там указаны требования, установка и то, что уже проверено. Модули и установщик рассчитаны на ГУ B216; отдельные функции ещё требуют проверки.

## Установить модуль

1. Откройте страницу нужного модуля и скачайте файл из раздела «Скачать».
2. Проверьте требования. Для Android-модулей нужны ГУ B216 и настроенный LSPosed.
3. Установите файл по инструкции модуля и включите только указанные приложения.
4. Проверяйте результат на стоянке.

| Что нужно | Страница и загрузка |
| --- | --- |
| Перевести меню, настройки и климат | [Русский интерфейс](docs/modules/russian-ui.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/russian-ui-code349) |
| Показать карты на приборке | [Навигация на приборке](docs/modules/cluster-navigation.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/yandex-cluster-0.56-test) |
| Настроить плитки и разделение экрана | [Интерфейс и настройки](docs/modules/interface-tweaks.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/interface-tweaks-code52) |
| Исправить размер окна EzMod | [Рабочая область](docs/modules/app-workspace.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/app-workspace-code7) |
| Перевести реплики TSpeech голосом Алисы | [Русская озвучка](docs/modules/russian-voice.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/alice-voice-code10) |
| Перевести нативную приборку | [Инструкция и установщик Windows x64](docs/modules/native-cluster.md) · [Скачать](https://github.com/LuckDMST/qiyuan-q05-mods/releases/tag/cluster-native-ru-2026-11-21_04) |

Другие материалы: [русские реплики внешнего громкоговорителя](docs/modules/exterior-charge-voice.md), [перевод кругового обзора](docs/modules/avm-magisk.md), [голосовой ввод Dicio](docs/modules/dicio-voice-input.md).

## Скриншоты

[Примеры перевода на центральном экране](screenshots/russian-ui/README.md) · [Приборка до и после перевода](docs/modules/native-cluster.md#скриншоты-до-и-после)

![Настройки автомобиля, раздел «Вождение»](screenshots/russian-ui/01-driving.png)

## Таблицы перевода

В папке [translations](translations/) лежат TSV-файлы с русскими строками для приложений автомобиля. Название файла соответствует Android-пакету приложения. Если редактируете таблицу, сохраняйте имена ресурсов, индексы, исходные строки и параметры форматирования.

Если нашли ошибку, [создайте Issue](https://github.com/LuckDMST/qiyuan-q05-mods/issues). Укажите модель автомобиля, версию модуля, путь к экрану и текст ошибки. Перед отправкой снимка скройте VIN, номера, имена, контакты и данные аккаунтов.

## Благодарности

- [Павлу](https://gitverse.ru/PavelAravin/q05ru) — за помощь с получением root-доступа к головному устройству.
- Автору проекта [changan-a06-ru-assistant](https://github.com/voronoff2803/changan-a06-ru-assistant) — за работу над голосовым помощником. Этот проект я изучал при разработке решения.
- Активным участникам обсуждения на [форуме 4PDA](https://4pda.to/forum/index.php?showtopic=1123480) — за участие и обмен опытом по теме проекта.
