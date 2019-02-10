# Пилотный выпуск React Challenge: сортировка и поиск данных

[Статья на сайте](http://jsraccoon.ru/react-challenge-sort-and-search)

[Демо приложения](http://jsraccoon.ru/react-challenge-sort-and-search)

Что делать:

* Форкнуть этот репозиторий
* Склонировать свой форк `git clone https://github.com/<ваш_аккаунт_на_гитхабе>/react-challenge-sort-and-search`
* Открыть папку `cd react-challenge-sort-and-search`
* Установить все зависимости `npm install`
* Запустить галп `gulp`
* Вы восхитительны и готовы к челенджу!

## Таски для галпа

* Дефолтный (просто `gulp`): запускает browsersync и решрешит при изменении js, css и html. Браузер должен открыть самостоятельно.
* Деплой (`gulp deploy`): пушит всё, что находится в папке `public` в ветку `gh-pages`. В результате сайт можно показать другу

## Удачи!

node : 5.6.0

"gulp": "github:gulpjs/gulp#4.0",

**fix** that worked for me:
update package.json line 42
from `"gulp": "gulpjs/gulp#4.0",` to ` "gulp": "4.0",`
