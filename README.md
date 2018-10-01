# Core-and-Vue-boilerplate
This is a boilerplate for dotnet core MVC and Vue.js

In the principle, it should contain only the bare minimum of dependencies. 
- webpack allows to process Vue files into app.js,
- webpack-merge allows to merge webpack.dev.js or webpack.prod.js configuration with webpack.common.js,
- babel-loader translates JS files,
- css-loader, file-loader, sass-loader, vue-loader, vue-template-compiler process style and vue files,

# Run Dev
webpack --config=webpack.dev.js 

# Run Prod
webpack --config=webpack.prod.js 
