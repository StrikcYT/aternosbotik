# Афк бот для атерноса
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/StrikcYT/AternosBotik)

Бот, который может прогружать сервер, который стоит на атерносе.

Есть 2 основные команды:
    
* Двигайся
* Настройки

Префикс для команд по умолчанию - $

### Команда "Двигайся":
Бот начинает двигаться.

### Команда "Настройки":
С помощью этой команды можно настроить ник, задержку движения и автоматический перезаход на сервер.

По умолчанию:

* Ник - AternosBot,
* Задержка движения - 10 секунд,
* Автоматический перезаход - Включён.

Если бот стоит на Heroku и автоматический перезаход выключён, то бот все равно перезайдёт на сервер (со сброшенными настройками)  

---------------------
Для работы бота на Heroku стоит настроить такие конфиг переменные:

* server -> Айпи сервера,
* port -> Порт сервера (не обязательно),
* nick -> Ник (не обязательно),
* dsbot -> Токен бота в дискорде (не обязательно).

