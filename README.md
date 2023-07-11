######
Add a new Spin version

1. Create build folder in react-custom-roulette
2. Rename the folder to spinapp (for example)
3. Add the folder to dist of this app
4. Fix urls when we use react-custom-roulette to spinapp
5. Rename index.html file of spinapp to spin.html
6. Move this file to dist/
7. Copy this dist folder to a Hosting

######

# Webpack boilerplate with SASS(SCSS), HTML modules, Babel
## Features
* Easy to start `yarn install` + `yarn start` (`npm install` + `npm start`)
* Don't worry about webpack config, just code
* Custom HTML Modules plugin\
* HTML hot reload(Livereload)
* SCSS (SASS)
* jQuery already installed
* Babel
  * ES6
  * ES7
  * Class syntax + Class properties
  * etc
* Autoprefixer
* Minifier
* PostCSS
* Eslint (airbnb-base config)
* Eslinting on the fly (while dev)
* Pretty console output (Friendly errors webpack plugin)

## Adding libraries to JS
1. Find the desired library at https://www.npmjs.com/ (example: https://www.npmjs.com/package/moment)
2. Install `yarn add moment` or `npm install moment`
3. Import library into your code `import moment from 'moment'`
4. Use it

## Usage
Installation
```
npm install
or
yarn
```
Start dev server for development
```
npm start
or 
yarn start-yarn
```
Build
```
npm run build
or
yarn build
```

3d slider https://www.cssscript.com/3d-carousel-mouse-touch/