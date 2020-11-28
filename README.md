# Описание задачи:

* Ссылка на [Макет](https://www.figma.com/file/SRnMOjKIHy2LSh36b3K7c7/Test?node-id=0%3A1)
* Нужно сверстать 2 простеньких экрана, адаптив, макеты даны для 3 разрешений.
* Нельзя использовать готовые фреймворки.
* Результат на одной странице.

# Результат 

* [Демо](https://tiigrus.github.io/Light-company-test/)
* Скомпилированные файлы [здесь](https://github.com/TIIGRUS/Light-company-test/tree/gh-pages). 
* Потраченное время 6 часов 40 минут. 

# TARS-CLI

## Установка

TARS-CLI — Command Line Interface для сборщика верстки [TARS](https://github.com/tars/tars/blob/master/README_RU.md).

Для корректной работы необходимо установить TARS-CLI глобально:

`npm i -g tars-cli`

Возможно потребуются права суперюзера. Но желательно настроить систему так, чтобы этого не требовалось.

Если вы используете Node.js версии 5.x.x, убедитесь, что вы используете npm версии 3.3.10 и выше. В противном случае обновите npm:

```bash
npm i -g npm
```

Пользователям Windows необходимо выполнить еще пару шагов:

* перейти в C:\Program Files (x86)\nodejs или C:\Program Files\nodejs в cmd.exe или в любом другом терминале. Путь зависит от того, куда Node.js был установлен;
* запустите команду `npm install npm@latest`.

Возможно потребуются права суперюзера.

Начните свой проект с помощью:

```bash
tars init
```

## Команды TARS-CLI

Все команды запускаются по шаблону:

`tars` + `command-name` + `flags`

В любой момент можно запустить `tars --help` или `tars -h` или просто `tars`, без дополнительных комманд и флагов. Данная команда выведет информацию о всех доступных командах. Также можно добавить ключ `--help` или `-h` к любой команде, чтобы получить наиболее полное описание команды.

`tars -v` или `tars --version` выведет текущую установленную версию TARS-CLI и версию TARS в текущем проекте. Также будет выведена информация по обновлению, если оно доступно.

Практически во всех командах доступен интерактивный режим. В данном режиме вы сможете взаимодействовать с CLI через подобие графического интерфейса. При использовании интерактивного режима вам не нужно знать, какие флаги за что отвечают, так как вы общаетесь с CLI на естественном языке. Интерактивный режим легко отключить, если вам необходимо проводить автоматическое тестирование или что-то еще, что не требует присутствие человека.

### Command list

* [tars init](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-init) — инициализирует TARS.
* [tars dev](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-dev) — запускает dev-режим сборки.
* [tars build](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-build) — запускает build-режим сборки.
* [tars start](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-start-taskname) — запускает любой gulp-таск из локального gulpfile.
* [tars add-component](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-add-component-componentname) — добавляет компонент в markup/components.
* [tars add-page](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-add-page-pagename) — добавляет страницу в markup/pages.
* [tars update](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-update) — обновляет TARS-CLI.
* [tars update-project](https://github.com/tars/tars-cli/blob/master/docs/ru/commands.md#tars-update-project) — обновляет TARS В текущем проекте.

По любым вопросам можно обращаться по почте [tars.builder@gmail.com](tars.builder@gmail.com) или в [gitter](https://gitter.im/tars/tars-cli?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge)

[downloads-image]: http://img.shields.io/npm/dm/tars-cli.svg?style=flat-square
[npm-url]: https://npmjs.org/package/tars-cli
[npm-image]: http://img.shields.io/npm/v/tars-cli.svg?style=flat-square

[travis-image]: https://travis-ci.org/tars/tars-cli.svg?branch=master
[travis-link]: https://travis-ci.org/tars/tars-cli

[deps-image]: https://david-dm.org/tars/tars-cli.svg?style=flat-square
[deps-link]: https://david-dm.org/tars/tars-cli

[gitter-image]: https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg?style=flat-square
[gitter-link]: https://gitter.im/tars/tars-cli?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge
