# Подготовительный день

## 1. VSCode

### Установить расширения

- Greenery
- PHP Intelephense
- Prettier
- SQLTools
- SQLTools MySQL/MariaDB/TiDB Driver
- IntelliSense for CSS class names in HTML
- HTML CSS Support
- PHP Server
- Path Intellisense
- Path Autocomplete
- vscode-icons
- Error Lens
- PHP DocBlocker
- Auto Rename Tag
- GitLens
- CSS Peek
- Format HTML in PHP
- Todo Tree
- Russian - Code Spell Checker
- Code Spell Checker

### Проверить VSCode

- Открывается папка проекта
- Работает встроенный терминал
- Работает поиск по файлам
- Работают подсказки PHP
- Работают подсказки HTML/CSS
- Работает форматирование
- Работают сниппеты

## 2. Git

### Проверить установку

- Выполнить `git --version`

### Настроить пользователя

- Выполнить `git config --global user.name "..."`
- Выполнить `git config --global user.email "..."`
- Проверить настройки через `git config --global --list`

## 3. XAMPP

### Проверить запуск

- Открыть XAMPP Control Panel
- Запустить Apache
- Запустить MySQL
- Убедиться, что Apache и MySQL запустились без ошибок

### Проверить в браузере

- Открыть `http://localhost/`
- Открыть `http://localhost/phpmyadmin/`

### Проверить PHP

- Создать файл `test.php` в папке `htdocs`
- Вставить в него `<?php phpinfo(); ?>`
- Открыть `http://localhost/test.php`
- Убедиться, что страница PHP открывается

## 4. База данных

### phpMyAdmin

- Открыть `http://localhost/phpmyadmin/`
- Проверить вход в phpMyAdmin
- Создать тестовую базу данных
- Создать тестовую таблицу
- Выполнить простой SQL-запрос
- Проверить импорт `.sql` файла

### Дополнительные программы

- Проверить запуск MySQL Workbench
- Проверить запуск DBeaver
- Проверить подключение к локальной MySQL/MariaDB

Параметры подключения обычно такие:

- Host: `127.0.0.1`
- Port: `3306`
- User: `root`
- Password: пустой, если не задан другой

## 5. Браузер

### Проверить

- Установлен Chrome или Edge
- Открывается `http://localhost/`
- Открывается сайт из папки `htdocs`
- Открываются DevTools через `F12`

### В DevTools проверить

- Console
- Network
- Application
- адаптивный режим

## 6. Финальная проверка

- VSCode установлен
- Все нужные расширения установлены
- Сниппеты работают
- Git установлен и настроен
- XAMPP установлен
- Apache запускается
- MySQL запускается
- `http://localhost/` открывается
- `http://localhost/phpmyadmin/` открывается
- PHP-файл из `htdocs` выполняется
- Тестовая БД создаётся
- SQL-файл импортируется
- DBeaver или MySQL Workbench подключается к локальной БД
- Браузер и DevTools работают
