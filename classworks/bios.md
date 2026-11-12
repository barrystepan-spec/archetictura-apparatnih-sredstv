**Практика BIOS/UEFI**

### 1. Навигация по UEFI
Открыл разделы Main, Config, Security, Startup и Restart.

![Сведения о системе в Main](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/01-main.png)

### 2. Порядок загрузки
![Порядок загрузки в Startup → Boot](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/02-boot-order.png)

### 3. Secure Boot
![Secure Boot в положении Off](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/03-secure-boot.png)

### 4. Пароль супервизора
В разделе **Security → Password → Supervisor Password** задал тестовый пароль. После этого при любых изменениях требуется его ввод.

![Статус Supervisor Password — Enabled](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/04-supervisor-password.png)

### 5. Заводские настройки
В **Restart → Load Factory Defaults** подтвердил сброс. В симуляторе выполнить полный сброс невозможно.

![Диалог загрузки заводских настроек](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/05-factory-defaults.png)

### 6. Питание USB
В **Config → USB → Always On USB** отключил и снова включил постоянное питание USB-портов.

![Always On USB в положении Off](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/06-always-on-usb.png)

### 7. Режим контроллера SATA/NVMe
Проверил раздел **Config**. Пункт Storage в симуляторе отсутствует.

![Пункты меню Config](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/07-storage-menu.png)

### 8. Временное меню загрузки F12
В **Startup → Boot device List F12 Option** отключил и снова включил эту опцию. Клавиша F12 в симуляторе не сработала.

![Опция Boot device List F12 включена](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/08-f12-option.png)

### 9. Журнал событий
Симулятор не поддерживает эту функцию.

![Строка BIOS Event log в Main](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/09-event-log.png)

### 10. Подготовка к переустановке ОС
Сбросил настройки, включил Secure Boot и оставил тестовый пароль. Проверил Boot, нажал **F10 → Yes**. Полностью проверить процедуру в симуляторе нельзя.

![Подтверждение Save and Exit](https://github.com/DXlol112/Hardware-Architecture_class/blob/add/lesson-10/.github/assets/lesson_10/10-save-and-exit.png)