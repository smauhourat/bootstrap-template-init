## Paso a paso para generar un proyecto template de bootstrap

- **Node Installation:** [Install node js](https://nodejs.org/en/download/)
- **Initialize node project:**

  ```
  npm init --yes
  ```

* **Install dependencies:**

  1. Bootstrap

  ```
  npm install bootstrap
  ```

  2. Bootstrap dependecies (jquery and popper.js)

  ```
  npm install jquery popper.js
  ```

  3. Icons-Fontawesome

  ```
  npm install font-awesome
  ```

- **Install development dependencies:**

  1. Gulp (library to do tasks)

  ```
  npm install -D gulp gulp-cli gulp-sass node-sass
  ```

  2. Syncro Browser Test

  ```
  npm install -D browser-sync
  ```

- **Configure libraries**

  1. Create `gulpfile.js` file
  2.

### Fuentes:

    https://www.faztweb.com/contenido/bootstrap4-configuracion-profesional
    https://github.com/FaztWeb/bootstrap4-template-init
    https://themesberg.com/blog/tutorial/gulp-4-bootstrap-sass-browsersync
    https://github.com/johndavemanuel/bootstrap-gulp-starter-template/blob/master/gulpfile.js
