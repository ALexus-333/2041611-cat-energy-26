# Личный проект «Кэт энерджи»

* Студент: [Aleksey Yakovlev](https://up.htmlacademy.ru/adaptive/26/user/2041611).
* Наставник: [Mikhail Savotikov](https://htmlacademy.ru/profile/id98316).

---

**Обратите внимание, что папка с вашими исходными файлами — `source/`.**

Полезный файл:

- [Contributing.md](Contributing.md) — руководство по внесению изменений.

_Не удаляйте и не обращайте внимание на файлы:_<br>
_`.editorconfig`, `.gitattributes`, `.gitignore`, `.stylelintrc`, `.travis.yml`, `package-lock.json`, `package.json`._

---

## В проекте

- Adaptive layout
- Flexbox
- BEM naming
- LESS
- Gulp (autoprefixer, css/js concatenation and minification, svg/images optimization, webp, svgsprite)
- Inline svg sprite (symbol + use)
- Adaptive images (picture + srcset + media queries)
- Retina images
- GIT VCS

---

## Как использовать

`npm install` - установка зависимостей.

`npm start` - сборка проекта в режиме разработки и запуск локального сервера.

`npm run build` - финальная сборка проекта.

---

## Структура проекта

```bash
.
├── build/                # каталог сборки проекта (cоздаётся автоматически)
├── source/               # каталог для размещения исходных файлов проекта
│   ├── css/              # каталог файлов стилей
│   ├── fonts/            # каталог шрифтов
│   ├── img/              # каталог растровых и векторных изображений
│        └── favicons/    # каталог растровых и векторных изображений для выбора нужной фавиконки
│   │    └── sprites/     # каталог векторных изображений для генерации векторного спрайта
│   ├── js/               # каталог JS файлов
│   └── index.html        # файл разметки страницы
├── .editorconfig         # файл конфигурации настроек редактора
├── .gitattributes        # файл атрибутов Git
├── .gitignore            # файл исключений Git
├── .stylelintrc.json     # файл конфигурации stylelint
├── gulpfile.js           # каталог задач для Gulp
├── README.md             # документация проекта
├── package-lock.json     # lock-файл npm
├── package.json          # файл npm зависимостей и настроек проекта
```

---
