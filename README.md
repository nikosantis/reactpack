# reactpack

Iniciar proyecto
git init

Instalar React
npm install --save react react-dom

Instalar Babel

npm install @babel/core @babel/preset-env @babel/preset-react babel-loader --save-dev 
configurar .babelrc

{
  ""presets"": [
    ""@babel/preset-env"",
    ""@babel/preset-react""
  ],
}

Usando WebPack

npm install webpack webpack-cli html-webpack-plugin html-loader  --save-dev
configurar webpack.config.js

Instalar Server

npm install webpack-dev-server --save-dev 

Instalar SASS

npm install mini-css-extract-plugin css-loader node-sass sass-loader --save-dev 

configurar mini-css-extract-plugin

Instalar Eslint

npm install eslint babel-eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y --save-dev 
configurar .eslintrc


