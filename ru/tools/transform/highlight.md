# Подсветка кода

Для подсветки кода используется пакет [highlight.js](https://www.npmjs.com/package/highlight.js). Ознакомиться с перечнем доступных языков можно в [Github](https://github.com/highlightjs/highlight.js/tree/master/src/languages).

Чтобы установить пакет, выполните команду:
```shell
npm i highlight.js
```

## Подключить дополнительный язык {#add}

Вы можете передать дополнительный набор языков, который будет зарегистрирован для использования. 

Набор языков передается в виде объекта, у которого:

* ключ — имя языка.
* значение — функция, определяющая язык.

```javascript
const transform = require('@doc-tools/transform');
const customLang = require('./custom-lang');

const highlightLangs = { 'custom-lang': customLang };

const {result: {html, meta}, logs} = transform(content, {highlightLangs});
```
