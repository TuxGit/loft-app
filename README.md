# loft-app

Простой шаблон для создания фронтенд-проекта на технологиях БЭМ, SCSS, Jade и Gulp

## Структура проекта

    .
    ├── dist
    ├── src
    |   ├── styles
    |   |   ├── main.scss
    |   ├── js
    |   |   ├── main.js
    |   ├── templates
    |   |   ├── index.jade
    ├── tasks
    |   ├── build.js
    ├── gulpfile.js
    ├── package.json

Папка *dist* предназначена для хранения скомпилированных файлов, исходные файлы находятся в папке *src*. В файле *package.json* хранятся необходимые для проекта зависимости, а в файле *gulpfile.js* - настройки выполнения Gulp. Для удобства использования все задачи Gulp помещены в разные файлы и находятся в папке *tasks*.