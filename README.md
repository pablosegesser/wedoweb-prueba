# Bootstrap 4 boilerplate with sass and gulp 4
A Bootstrap 4.3.1 boilerplate with font-awesome, sass, gulp 4 tasks, browserSync (with hot-reloading). You can override bootstrap sass variables by placing those variables in `bootstrap-4-sass-gulp-4-boilerplate/assets/scss/_bootstrap_variable_overrides.scss`

## Pre-requisite
- [Node.js](https://nodejs.org/en/download/ "Node Js")
-  NPM (Comes with Node.js)
- [Gulp 4](https://gulpjs.com/ "Gulp")

Install Gulp cli

     $ npm install --global gulp-cli
     

## Getting started

1. Clone repository:
`git clone https://github.com/JayeshLab/bootstrap-4-sass-gulp-4-boilerplate.git`

2. Change directory:
`cd bootstrap-4-sass-gulp-4-boilerplate`
    
3. Install all dependencies and libraries:
   `npm install`

4. Run Gulp Task:
  - `gulp`      - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

  - `gulp dev`  - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).
   
   
   
   
   
## WeDoWeb

1. Para levantar el maquetado primero hay que ejecutar desde consola npm install. 

2. Luego ejecutar en consola gulp server para que levante el servidor en la carpeta dist que es donde está alojado el código ya optimizado. En caso de no poder levantarlo en un server el archivo index.html de la carpeta dist se puede ver normalmente en el navegador. También agregue el comando gulp server que levanta directamente el index optimizado en un server local para acelerar.
