# HE Paradise

**HE Paradise is a Windows utility that switches profiles already saved in a compatible keyboard's onboard memory.**

The project's declared hardware support is currently limited to compatible **Attack Shark** keyboards. Protocol research and entries in the device registry do not, by themselves, mean that every model or hardware revision has been physically tested.

## Current status

- **Physically tested:** Attack Shark R85 HE.
- **Other Attack Shark models:** under investigation; compatibility may vary by model, hardware revision and firmware. Check the compatibility information supplied with each release.
- **Other brands:** not currently included in the declared support scope. AJAZZ AK680 MAX has been tested internally but is not currently in the official compatibility list; testing one model does not imply support for the entire brand.
- **Attack Shark M36 HE:** not currently listed as supported; its onboard profile-selection protocol still needs confirmation.

## Current features

- Switches between profiles stored on the keyboard.
- **Automatic mode:** selects a profile based on the active Windows application.
- **Manual mode:** switches profiles using user-assigned global keyboard shortcuts.
- Maps app profiles to available onboard keyboard profile slots. The current app has a four-profile limit.
- Can run in the system tray and launch with Windows.

HE Paradise currently switches onboard profiles only. It does **not** configure actuation points, Rapid Trigger, lighting, macros, key remapping or firmware.

## Roadmap

The project aims to validate more Attack Shark models and later investigate additional keyboard families. Potential future configuration features include actuation, Rapid Trigger, lighting and other keyboard options. Each feature requires protocol research and hardware testing; these are plans, not features available in the current release.

## Getting started

1. Download a release package from the project's official release page when available.
2. Close the keyboard manufacturer's configuration utility before starting HE Paradise.
3. On first launch, review and accept the included EULA to continue.
4. Create app profiles, assign each an onboard profile slot, then choose Automatic or Manual mode.

Profiles and settings are stored in folders alongside `HEParadise.exe`. Keep these folders with the application when moving the portable package. Do not use HE Paradise during a keyboard firmware update. See [`DISCLAIMER.txt`](DISCLAIMER.txt) and the EULA included with the application for details.

## Price and support

HE Paradise is free to download and use. Optional support is available on [Ko-fi](https://ko-fi.com/heparadise); donations are not required and do not unlock features.

Questions or feedback: [heparadise.contact@gmail.com](mailto:heparadise.contact@gmail.com).

----

# HE Paradise

**HE Paradise — утилита для Windows, которая переключает профили, уже сохранённые во встроенной памяти совместимой клавиатуры.**

Сейчас публично заявлена поддержка только совместимых клавиатур **Attack Shark**. Исследование протокола и запись модели в реестре устройств сами по себе не означают, что каждая модель или аппаратная ревизия проверена на физическом устройстве.

## Текущий статус

- **Проверена на физическом устройстве:** Attack Shark R85 HE.
- **Другие модели Attack Shark:** совместимость изучается и может зависеть от модели, аппаратной ревизии и прошивки. Сверяйтесь со списком совместимости конкретного выпуска.
- **Другие бренды:** сейчас не входят в публично заявленную поддержку. AJAZZ AK680 MAX проверялась внутри проекта, но пока не входит в список официально поддерживаемых устройств; проверка отдельной модели не означает поддержку бренда целиком.
- **Attack Shark M36 HE:** пока не заявлена как поддерживаемая; протокол выбора встроенного профиля ещё нужно подтвердить.

## Что умеет сейчас

- Переключает профили, сохранённые в клавиатуре.
- **Автоматический режим:** выбирает профиль по активному приложению Windows.
- **Ручной режим:** переключает профили по заданным пользователем глобальным сочетаниям клавиш.
- Связывает профили приложения с доступными слотами встроенных профилей клавиатуры. В текущей версии можно создать до четырёх профилей приложения.
- Может работать в системном трее и запускаться вместе с Windows.

Сейчас HE Paradise только переключает встроенные профили. Приложение **не настраивает** точки срабатывания, Rapid Trigger, подсветку, макросы, переназначение клавиш или прошивку.

## Планы развития

Планируется проверить больше моделей Attack Shark и позднее исследовать совместимость с другими семействами клавиатур. В будущем могут появиться настройки точек срабатывания, Rapid Trigger, подсветки и других функций, но для каждой потребуются изучение протокола и проверка на реальном устройстве. Это планы, а не возможности текущего выпуска.

## Начало работы

1. Когда выпуск будет опубликован, скачайте пакет со страницы проекта.
2. Перед запуском HE Paradise закройте официальную программу настройки клавиатуры.
3. При первом запуске прочитайте и примите EULA, чтобы продолжить.
4. Создайте профили приложения, назначьте каждому слот встроенного профиля клавиатуры и выберите автоматический или ручной режим.

Профили и настройки хранятся в папках рядом с `HEParadise.exe`. При переносе портативной версии сохраняйте эти папки вместе с приложением. Не используйте HE Paradise во время обновления прошивки клавиатуры. Подробнее — в [`DISCLAIMER.txt`](DISCLAIMER.txt) и EULA, входящей в комплект.

## Стоимость и поддержка проекта

HE Paradise распространяется и используется бесплатно. Поддержать проект можно добровольно через [Ko-fi](https://ko-fi.com/heparadise); пожертвование не обязательно и не открывает дополнительные функции.

Вопросы и отзывы: [heparadise.contact@gmail.com](mailto:heparadise.contact@gmail.com).