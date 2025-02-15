# Настройки сборки

Ниже перечислены настройки сборки. Их и [стандартные настройки YFM](../../settings.md) можно задать одним из способов:
* через ключи запуска при выполнении команды `yfm`.
* в [файле конфигурации](../../project/config.md).

Имя ключа запуска соответствует названию настройки.

Ключ запуска | Описание 
--- | --- 
`--input, -i` | Путь до директории проекта (обязательный параметр).
`--output, -o` | Путь до директории, предназначенной для выходных данных (обязательный параметр).
`--varsPreset` | Название используемого [пресета переменных](../../project/presets.md).
`--vars, -v` | Значения [переменных](../../syntax/vars.md).
`--strict, -s` | Запуск в строгом режиме.</br></br>Предупреждения YFM трактуются как ошибки. По умолчанию выключено.
`--quiet, -q` | Запуск в тихом режиме.</br></br>Не выводить логи в stdout. По умолчанию выключено.
`--config, -c` | Путь до [файла конфигурации](../../project/config.md).
`--singlePage` | Сборка проекта в виде одного HTML-файла. Подробнее в разделе [Одностраничная сборка](./singlepage.md).
`--output-format` | Формат генерации. По умолчанию HTML, но можно настроить [сборку в YFM](md2md.md).
`--apply-presets` | Подставлять значения переменных из пресетов при сборке в YFM.
`--add-system-meta` | Добавить переменные из секции system пресетов в [метаданные](../../syntax/meta.md#meta) файлов. По умолчанию выключено.
`--remove-hidden-toc-items` | Удалять скрытые страницы из результата сборки. По умолчанию выключено.
`--version` | Текущая версия.

Чтобы ознакомиться с полным списком ключей, выполните команду `yfm --help`.
