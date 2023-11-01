npm install --save-dev nodemon Or
npm i -D nodemon
because we want to run the server and restart it automatically when we make changes to the code
and it is dev-dependency because we don't need it in production

.gitkeep is a convention to keep an empty folder in git

package.json -> scripts -> dev: "nodemon src/index.js"
