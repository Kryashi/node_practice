# Node Practice
This repository is to learn NodeJs, with examples while I'm study.

### Install Project
To execute the project you will need to clone
`git clone git@github.com:RodrigoKobayashi/node_practice.git`

After clone, install [Nodemon](https://nodemon.io/)
`npm install -g nodemon`

Inside project directory, run:
`npm install`

Start project:
`nodemon app.js`

Open the browser in **localhost:3000**

### Day Log:
**This day log is just to show what I'm doing during the study days**
* Day 1
    * Start Project, create app to start server
* Day 2 
    * Create modules pages/routes, write the ReadMe.md
* Day 3
    * Configure MySQL DbConnection and show result in /noticias
* Day 4
    * Fix local MySQL Ubuntu, request /noticias and /noticia, create a model to use in routes
    * This solve my problem with MySQL `ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';`
* Day 5
    * Post request, save body in BD, redirect to /noticias
* Day 6
    * Class refactor, express-validator (have some problem in app.use(expressValidator))

### Courses Link
* [Curso Completo do Desenvolvedor NodeJs e MongoDB](https://www.udemy.com/course/curso-completo-do-desenvolvedor-nodejs/learn/lecture/5652568#content)