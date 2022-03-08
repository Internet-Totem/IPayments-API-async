# IPayments API (асинхронный)


Пример асинхронного Telegram бота для взаимодействия с [IPayments API](https://telegra.ph/IPayments-API-02-09)

## Введение

Пример полностью готового и рабочего Telegram бота работающего на асинхронном коде (aiogram) для взаимодействия с IPayments API (создание, оплата и отмена счетов).

### Синхронный код

Точно такой же пример, но написанный на синхронном коде (aiogram -> **pyTelegramBotAPI**; aiohttp -> **requests**) можно посмотреть [здесь](https://github.com/Internet-Totem/IPayments-API-sync).


## Начало работы

Для того, чтобы использовать создайте своего Telegram бота и приложение в IPayments (подробно о том, как создать приложение [написано здесь](https://telegra.ph/Lets-Start-02-17)).
После получения токенов вставьте их в соответствующие поля в main.py.

### Необходимые библиотеки

- aiogram
- aiohttp
- asyncinit


### Запуск

```
python3 main.py
```

## Где посмотреть код в действии

Помимо того, что вы можете запустить этот код у себя, вы можете посмотреть как он работает в нашем [Demo Shop](http://t.me/IPayments_demoshop_bot).

> Все средства потраченные в Demo Shop будут обратно зачислены на баланс в IPayments


## Заключение

Это простой бот, в котором можно посмотреть как работают основные методы [IPayments API](https://telegra.ph/IPayments-API-02-09).
