# Проект «Мишка» от [HTML Academy](https://htmlacademy.ru/)

[![Build status][travis-image]][travis-url] [![Dependency status][dependency-image]][dependency-url]

Вёрстка: [Андрей Грачев](https://github.com/andreysgra/)

[Демо проекта](https://andreysgra.github.io/mishka/)

---

## Как использовать

`npm install` - установка зависимостей.

`npm start` - сборка проекта в режиме разработки и запуск локального сервера.

`npm run build` - финальная сборка проекта.

`npm run deploy` - финальная сборка проекта и размещение его в [GitHub Pages](https://pages.github.com).

`npm run dist` - финальная сборка проекта и упаковка его в zip-архив.

`npm test` - запуск теста на наличие стилистических ошибок.

---

## Структура проекта

```bash
.
├── build/            # каталог сборки проекта (cоздаётся автоматически)
├── dist/             # каталог, в котором архивируется собранный проект (cоздаётся автоматически)
├── gulpfile.js/      # каталог задач для Gulp
├── source/           # каталог для размещения исходных файлов проекта
│   ├── fonts/        # каталог шрифтов
│   ├── img/          # каталог растровых и векторных изображений
│   │   └── icons/    # каталог векторных изображений для генерации векторного спрайта
│   ├── js/           # каталог JS файлов
│   ├── styles/       # каталог файлов стилей
│   └── index.html    # файл разметки страницы
├── .babelrc          # файл конфигурации Babel
├── .editorconfig     # файл конфигурации настроек редактора
├── .eslintrc.json    # файл конфигурации ESLint
├── .gitattributes    # файл атрибутов Git
├── .gitignore        # файл исключений Git
├── .npmrc            # файл конфигурации npm
├── .stylelintrc.json # файл конфигурации stylelint
├── .travis.yml       # файл конфигурации Travis CI
├── package.json      # файл npm зависимостей и настроек проекта
├── package-lock.json # lock-файл npm
├── README.md         # документация проекта
└── Specification.md  # техническое задание
```

[travis-image]: https://travis-ci.org/andreysgra/mishka.svg?branch=master
[travis-url]: https://travis-ci.org/andreysgra/mishka
[dependency-image]: https://david-dm.org/andreysgra/mishka/dev-status.svg?style=flat-square
[dependency-url]: https://david-dm.org/andreysgra/mishka?type=dev
