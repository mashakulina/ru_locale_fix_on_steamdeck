Данный скрипт позволяет избавиться от параметра `HOST_LC_ALL=ru_RU.UTF-8 %command%` для запуска игр на русском языке в `Game mode`.<br/>
Скрипт прописывает в файл `environment` параметры RU локализации.<br/>
Создает резервную копию файла `environment`, помещая его по пути `\etc` (`\etc\environment.bak`).<br/>
**ВНИМАНИЕ**! Для запуска данного скрипта нужен `sudo` пароль (пароль администратора). Если ранее пароль не был установлен, то это можно сделать через консоль, используя команду `passwd`.

## Смена локализации
## Установка
1. Тапнуть правой кнопкой на [RuLocaleFix.desktop](https://raw.githubusercontent.com/mashakulina/ru_locale_fix_on_steamdeck/main/RuLocaleFix.desktop) 
2. Сохранить через `Save as` (`Сохранить ссылку как`) на рабочем столе

## Запуск
1. Тапнуть два раза на файл `RuLocaleFix.desktop`
2. Ввести `sudo` пароль во всплывшем окне
3. Дождаться перезагрузки Steam Deck

## Восстановление исходного файла
Восстанавливает файл `environment` из bak файла.Удаляет старую версию файла.
### Установка
1. Тапнуть правой кнопкой на [environment_recovery.desktop](https://raw.githubusercontent.com/mashakulina/ru_locale_fix_on_steamdeck/main/environment_recovery.desktop) 
2. Сохранить через `Save as` (`Сохранить ссылку как`) на рабочем столе

### Запуск
1. Тапнуть два раза на файл `environment_recovery.desktop`
2. Ввести `sudo` пароль во всплывшем окне
3. Дождаться перезагрузки Steam Deck

### Дополнительно
После обновления Steam OS файл может быть сброшен до исходного состояния (если игра запустилась из Game mode на английском зяыке). В таком случае нужно повторить запуск `RuLocale.desktop`.
