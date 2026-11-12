# Практика BIOS/UEFI

## 1. Навигация по UEFI

Открыл Main, Config, Security, Startup и Restart.

![Сведения о системе в Main](../../.github/assets/lesson_10/01-main.png)

## 2. Порядок загрузки

![Порядок загрузки в Startup → Boot](../../.github/assets/lesson_10/02-boot-order.png)

## 3. Secure Boot

![Secure Boot в положении Off](../../.github/assets/lesson_10/03-secure-boot.png)

## 4. Пароль супервизора

В **Security → Password → Supervisor Password** установил тестовый пароль. При попытке что то сделать требуется ввод пароля.

![Статус Supervisor Password — Enabled](../../.github/assets/lesson_10/04-supervisor-password.png)

## 5. Заводские настройки

В **Restart → Load Factory Defaults** подтвердил сброс. Невозможно нет в симуляторе.

![Диалог загрузки заводских настроек](../../.github/assets/lesson_10/05-factory-defaults.png)

## 6. Питание USB

В **Config → USB → Always On USB** выключил и снова включил постоянное питание USB.

![Always On USB в положении Off](../../.github/assets/lesson_10/06-always-on-usb.png)

## 7. Режим контроллера SATA/NVMe

Проверил **Config**. В симуляторе пункт Storage отсутствует.

![Пункты меню Config](../../.github/assets/lesson_10/07-storage-menu.png)

## 8. Временное меню загрузки F12

В **Startup → Boot device List F12 Option** выключил и снова включил опцию. F12 в симуляторе не открыл.

![Опция Boot device List F12 включена](../../.github/assets/lesson_10/08-f12-option.png)

## 9. Журнал событий

Simulator not support

![Строка BIOS Event log в Main](../../.github/assets/lesson_10/09-event-log.png)

## 10. Подготовка к переустановке ОС

Сбросил настройки, Secure Boot включён и тестовый пароль. Проверил Boot, нажал **F10 → Yes**. В симуляторе полностью проверить невозможно.

![Подтверждение Save and Exit](../../.github/assets/lesson_10/10-save-and-exit.png)