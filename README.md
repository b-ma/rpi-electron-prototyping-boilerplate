ES6 Prototyping Boilerplate
=======================================================


## Available Commands

```
npm run [command]
```

- `transpile`: transpile all files from `es6` folder to `dist` folder
- `bundle`: run `transpile` command and creates a browserifyed bundle _(entry point: `dist/main.js`)_
- `watch`:
  * creates a static file server
  * transpile files in `es6` folder on save
  * rebundle application on page load
- `serve`: run the static file server only _(kind of presentation mode)_


## Requirements

The boilerplate uses `babel` and `browserify` in order to transpile from es6 / CommonJS syntax to browser compliant es5.

**These packages should be installed globally**

Documentation for these modules can be found here:
- [https://babeljs.io/](https://babeljs.io/)
- [http://browserify.org/](http://browserify.org/)

You may also take a look at:
- [https://babeljs.io/docs/usage/runtime/](https://babeljs.io/docs/usage/runtime/)

## System Install / Update

install node from [https://nodejs.org/download/](https://nodejs.org/download/)

```
npm update npm
sudo npm install -g n
n stable
sudo npm install -g npm-workspace
sudo npm install -g browserify
sudo npm install -g babel
```

If problems with running global `babel` and `browserify` look at this issue:
[http://stackoverflow.com/questions/12594541/npm-global-install-cannot-find-module](http://stackoverflow.com/questions/12594541/npm-global-install-cannot-find-module)

(add `export NODE_PATH=/usr/local/lib/node_modules:$NODE_PATH` in your `.bash_profile`)


## TODOS

- install `sass` ?