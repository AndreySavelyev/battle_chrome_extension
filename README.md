# Hexlet battles
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/kaize/battle_chrome_extension/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
[![Build Status](https://travis-ci.org/Hexlet/battle_chrome_extension.svg?branch=master)](https://travis-ci.org/Hexlet/battle_chrome_extension)

## Описание:

Расширение Chrome для Hexlet battles

## Требования:

- node + npm

## Установка:

```
make
```


## Установка расширения:
- Перейти на ```chrome://extensions/```;
- Проверить, что установлен "Режим разработчика" (чекбокс в правом верхнем углу);

 
__Для работы в develop-окружении:__
 
- Выбрать "Загрузить распакованное расширение...";
- Выбрать папку ```dev``` в корневой папке расширения;
- Запустить сервер командой ```make develop``` в терминале. Сервер должен быть запущен постоянно во время работы.
- При изменении js-файлов расширение обновится автоматически. Для применения изменений в ```manifest.json``` сервер необходимо перезапустить.

__Для установки релизной версии:__

- Перетащить архив расширения из папки ```dist``` в окно браузера;
- Согласиться на установку.

_Или_

- Выбрать "Загрузить распакованное расширение...";
- Выбрать папку ```build``` в корневой папке расширения.