# Ice Cream — Team Web Development Project

A responsive website for an ice cream brand, developed as a team project during my web development training.

## Live Demo

[View the live website](https://hanna-serdjuk.github.io/icecream-project/)

## About the Project

The Ice Cream project is a team-developed website created to practise front-end development, teamwork, and collaboration using Git and GitHub.

As the **Team Lead**, I was responsible for coordinating the team's work, helping resolve conflicts, and contributing to the development of several sections of the website.

## My Role and Contributions

**Role: Team Lead & Front-End Developer**

- **Header** — developed the website header and navigation section.
- **Footer** — implemented the footer section.
- **Customer Reviews** — developed the customer reviews section.
- **Locations** — implemented the locations section.
- **Team Coordination** — coordinated team tasks, monitored progress, and helped keep the work organized.
- **Conflict Resolution** — helped resolve disagreements within the team and find solutions that worked for everyone.

## Technologies

- HTML5
- CSS3 / Sass
- JavaScript
- Parcel
- Git
- GitHub

## Key Learnings

- Developing and styling website sections
- Creating responsive web layouts
- Collaborating on a shared codebase
- Using Git and GitHub in a team environment
- Coordinating tasks and supporting team members
- Resolving conflicts and finding constructive solutions
- Taking responsibility as a Team Lead

## Project Links

- [Live Demo](https://hanna-serdjuk.github.io/icecream-project/)
- [GitHub Repository](https://github.com/Hanna-Serdjuk/icecream-project)

## Author

**Hanna Serdjuk**  

[GitHub Profile](https://github.com/Hanna-Serdjuk)


# Parcel boilerplate

## Скрытые файлы

Включите отображение скрытых файлов и папок в проводнике своей операционной системы, иначе вы не
сможете выбрать и скопировать себе файлы настроек проекта, имена которых начинаются с точки.

## Зависимости

На компьютере должена быть установлена LTS-версия [Node.js](https://nodejs.org/en/) со всеми
дополнительными инструментами кроме **Chocolatey** - его ставить не нужно.

## Перед началом работы

Один раз на проект установить все зависимости.

```shell
npm ci
```

### Разработка

Запустить режим разработки.

```shell
npm run dev
```

Во вкладке браузера перейти по адресу [http://localhost:1234](http://localhost:1234).

### Деплой

Сборка будет автоматически собирать и деплоить продакшен версию проекта на GitHub Pages, в ветку
`gh-pages`, каждый раз когда обновляется ветка `main`. Например, после прямого пуша или принятого
пул-реквеста. Для этого необходимо в файле `package.json` отредактировать поле `homepage` и скрипт
`build`, заменив `имя_пользователя` и `имя_репозитория` на свои.

```json
"homepage": "https://имя_пользователя.github.io/имя_репозитория",
"scripts": {
  "build": "parcel build src/*.html --public-url /имя_репозитория/"
},
```

На всякий случай стоит зайти в настройки репозитория `Settings` > `Pages` и убедиться что продакшен
версии файлов раздаются из папки `/root` ветки `gh-pages`.

Через какое-то время живую страницу можно будет посмотреть по адресу указанному в отредактированном
свойстве `homepage`, например
[https://goitacademy.github.io/parcel-project-template](https://goitacademy.github.io/parcel-project-template).

## Файлы и папки

- Все паршалы файлов стилей должны лежать в папке `src/sass` и импортироваться в
  `src/sass/main.scss`
- Изображения добавляйте в папку `src/images`, заранее оптимизировав их. Сборщик просто копирует
  используемые изображения чтобы не нагружать систему оптимизацией картинок, так как на слабых
  компьютерах это может занять много времени.
