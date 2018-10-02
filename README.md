# Core-and-Vue-boilerplate
This is a boilerplate for dotnet core MVC and Vue.js

In the principle, it should contain only the bare minimum of dependencies. 
- webpack bundles js, css, vue etc. into app.js file and place it under wwwroot,
- webpack-merge allows to merge webpack.dev.js or webpack.prod.js configuration with webpack.common.js,
- babel-loader translates JS files,
- css-loader, file-loader, sass-loader, vue-loader, vue-template-compiler process style and vue files,

This boilerplate uses Eslint as the linter for script files. It is not indispensable, but it allows to keep a high level of coding style.
- eslint the main processor,
- eslint-loader while webpacking the *.js files are lintered,
- eslint-plugin-vue used with *.vue files, 

# Run Dev
(in order to run tasks concurrently, the [Concurrently](https://www.npmjs.com/package/concurrently) must be installed 'npm install -g concurrently')

npm run dev

# Run Prod
npm run build
