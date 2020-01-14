# angular-project-startup

a project consist of points helping beginning new angular projects

# generating a new project

> ng new \<project name>

# adding angular material to the project

for installing angular material we need to just add the angular material dependecy to the project:

> ng add @angular/material

# adding bootstrap to the project

for installing bootstrap on the project execute commands below:

_Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery._

> npm install bootstrap

_this command will install bootstrap from npm_

after installing bootstrap successfully it's time to add bootstrap library to the exisiting project.

you have two options for adding bootstrap library to your project:

- adding bootstrap to the `angular.js` file to the styles section as I've shown that below:

```
"styles": [
              "./node_modules/@angular/material/prebuilt-themes/indigo-pink.css",
              "./node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.scss"
          ],
```

- Import directly in `src/style.css` or `src/ style.scss`:

```
@import '~bootstrap/dist/css/bootstrap.min.css';
```
