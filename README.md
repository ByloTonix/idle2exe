<h1 align="center">IDLE2Exe</h1>
<h4 align="center">IDLE - официальная среда разработки от разработчиков Python. По умолчанию она запускается через pythonw.exe, что делает невозможным назначить её приложением по умолчанию для .py и редактировать их двойным кликом. Чтобы исправить это, была создана инструкция для исправления.</h4>

## В чём суть: 

- **В файлах Python в папке \Lib\idlelib есть файл idle.bat. В нём нужно заменить CurrentDir на прямые пути к pythonw.exe и idle.pyw (1 - в папке Lib, 2 - в Lib\idlelib). Пример того, как должен выглядеть idle.bat, есть загрузках репозитория.**

Для конвертации **.bat в .exe** можно использовать программу от **[Tokyoneon](https://github.com/tokyoneon/B2E)**, а иконку взять из C:\Program Files\Python39\Lib\idlelib\Icons. В папке C:\Program Files\Python39\Lib\idlelib\ есть **idle.bat** от **самих разработчиков Python**, но чтобы при конвертации полученный .exe заработал, необходимо указать прямой путь к **pythonw.exe и idle.pyw**, или **использовать мой .bat**.

## Использование:
**Windows:**
- Скачайте **.exe-файл** по **[ссылке](https://github.com/MatroCholo/exeidle/releases)**
- Запустите и/или в меню "Открыть с помощью" выберите скачанный exe-файл.

## Обратная связь:
- Telegram: https://t.me/MatroCholo
