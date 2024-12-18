## Проект Bootstrap + Webpack

Проект Bootstrap + Webpack как в документации.

- блок навигации;
- функционал мобильного меню (в мобильном меню ссылки показываются при нажатии на кнопку);
- главный блок. Высота равняеться высоте экрана (viewport). В качестве фона видео в теге "video". Затемнение фона с видео.
- блок с заголовком "Каталог";
- блок с карточками. Выровнены карточки по высоте, если в одной из них контента больше. Кнопка "Купить" при этом внизу карточки.

## Технологический стек

<div align="center">
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 5px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="40" /></a>  
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 5px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="40" /></a>  
<a href="https://getbootstrap.com/docs/3.4/javascript/" target="_blank"><img style="margin: 5px" src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" alt="Bootstrap" height="40" /></a>  
<a href="https://webpack.js.org/" target="_blank"><img style="margin: 5px" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/webpack-colored.svg" alt="Webpack" height="40" /></a>
</div>

## Структура проекта

```bash
.
project-bootstrap/
├── src/
│   ├── js/
│   │   └── main.js
│   ├── scss/
│   │   └── styles.scss
│   └── index.html
├── package-lock.json
├── package.json
└── webpack.config.js
```

## Начало работы

### Предварительные условия

Убедитесь, что у вас установлен **Node.js**. Вы можете проверить его версию, выполнив команду:

```bash
node -v
```

Установка

Склонируйте репозиторий:

```bash
git clone https://github.com/AlenaBukhtarevich/project-bootstrap.git
cd папка/project-bootstrap
```

Установите зависимости:

```bash
npm install
```

Запустите сервер разработки:

```bash
npm start
```

Перейдите по адресу http://localhost:8080 в вашем браузере.
