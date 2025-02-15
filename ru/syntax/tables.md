# Таблицы

{% note tip %}

Для быстрого создания таблиц можно использовать онлайн-генераторы. Например, [Tables Generator](https://www.tablesgenerator.com/markdown_tables).

{% endnote %}

Таблица состоит из:
* строки с заголовками;
* разделительной строки;
* строк с данными.

Строка заголовков отделяется от ячеек таблицы тремя или более символами `-`. Колонки отделяются символами `|`.

```markdown
| Заголовок1  | Заголовок2  |
| ----------- | ----------- |
| Текст       | Текст       |
| Текст       | Текст       |
```

**Результат**

| Заголовок1  | Заголовок2  |
| ----------- | ----------- |
| Текст       | Текст       |
| Текст       | Текст       |

В ячейках таблицы можно использовать [строчное форматирование](./base.md#line), [ссылки](./links.md), [однострочные фрагменты кода](./code.md#inline), [изображения](./media.md#images).

## Выравнивание текста

Используйте символ `:` в разделительной строке для выравнивания текста в колонках по левому краю, правому краю или центру.

```markdown
| По левому краю  | По центру        | По правому краю |
| :---            |      :----:      |            ---: |
| Текст           | Текст            | Текст           |
| Текст           | Текст            | Текст           |
```

**Результат**

| По левому краю  |     По центру    | По правому краю |
| :---            |      :----:      |            ---: |
| Текст           | Текст            | Текст           |
| Текст           | Текст            | Текст           |
