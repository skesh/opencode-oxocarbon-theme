# opencode-oxocarbon-theme

[Oxocarbon](https://github.com/nyoom-engineering/oxocarbon) theme for [opencode](https://opencode.ai).

## Install

```bash
mkdir -p ~/.config/opencode/themes
curl -o ~/.config/opencode/themes/oxocarbon.json \
  https://raw.githubusercontent.com/skesh/opencode-oxocarbon-theme/main/oxocarbon.json
```

Then select the theme in opencode settings:

```json
{
  "theme": "oxocarbon"
}
```

## Colors

Based on IBM Carbon's color palette with both dark and light variants.

| Role       | Dark   | Light  |
|------------|--------|--------|
| Primary    | `#78a9ff` | `#0f62fe` |
| Background | `#161616` | `#f2f4f8` |
| Panel      | `#262626` | `#dde1e6` |
| Text       | `#f2f4f8` | `#393939` |
| Accent     | `#08bdba` | `#08bdba` |
| Error      | `#fa4d56` | `#da1e28` |
 | Success    | `#42be65` | `#42be65` |

## Theme properties

### General UI

| Свойство | Где используется |
|----------|-----------------|
| `primary` | Акцентные элементы, ссылки, кнопки |
| `secondary` | Второстепенные акценты |
| `accent` | Выделение, подсветка активных элементов |
| `error` | Ошибки, опасные действия |
| `warning` | Предупреждения |
| `success` | Успешные операции |
| `info` | Информационные сообщения |
| `text` | Основной текст |
| `textMuted` | Приглушённый текст, плейсхолдеры |
| `background` | Основной фон |
| `backgroundPanel` | Фон панелей и сайдбаров |
| `backgroundElement` | Фон элементов (инпутов, кнопок) |
| `border` | Границы элементов |
| `borderActive` | Граница активного/фокусного элемента |
| `borderSubtle` | Тонкие разделители |

### Diff (изменения в коде)

| Свойство | Где используется |
|----------|-----------------|
| `diffAdded` | Цвет добавленных строк (текст) |
| `diffRemoved` | Цвет удалённых строк (текст) |
| `diffContext` | Цвет контекстных строк |
| `diffHunkHeader` | Заголовок hunk'а (`@@ ... @@`) |
| `diffHighlightAdded` | Подсветка добавленного текста внутри строки |
| `diffHighlightRemoved` | Подсветка удалённого текста внутри строки |
| `diffAddedBg` | Фон добавленных строк |
| `diffRemovedBg` | Фон удалённых строк |
| `diffContextBg` | Фон контекстных строк |
| `diffLineNumber` | Цвет номеров строк |
| `diffAddedLineNumberBg` | Фон номера добавленной строки |
| `diffRemovedLineNumberBg` | Фон номера удалённой строки |

### Markdown

| Свойство | Где используется |
|----------|-----------------|
| `markdownText` | Основной текст |
| `markdownHeading` | Заголовки |
| `markdownLink` | Ссылки |
| `markdownLinkText` | Текст ссылки |
| `markdownCode` | Инлайн-код |
| `markdownBlockQuote` | Цитаты |
| `markdownEmph` | Курсив |
| `markdownStrong` | Жирный текст |
| `markdownHorizontalRule` | Разделители (`---`) |
| `markdownListItem` | Маркеры списков |
| `markdownListEnumeration` | Номера нумерованных списков |
| `markdownImage` | Изображения |
| `markdownImageText` | Alt-текст изображений |
| `markdownCodeBlock` | Блоки кода |

### Syntax highlighting

| Свойство | Где используется |
|----------|-----------------|
| `syntaxComment` | Комментарии |
| `syntaxKeyword` | Ключевые слова (`if`, `for`, `return`) |
| `syntaxFunction` | Имена функций и методов |
| `syntaxVariable` | Переменные, параметры |
| `syntaxString` | Строки |
| `syntaxNumber` | Числа |
| `syntaxType` | Типы, классы |
| `syntaxOperator` | Операторы (`+`, `->`, `=`) |
| `syntaxPunctuation` | Пунктуация (скобки, запятые) |
