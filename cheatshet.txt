//YOU CAN CREATE A REACT APP FROM SCRATCH 
npm init 
npm i react react-dom 
npm install @babel/core
npm i @babel/preset-env
npm i @babel/preset-react
npm i babel-loader   //for any js and jsx file loading

npm i webpack
npm i webpack-cli
npm i webpack-dev-server

npm i html-webpack-plugin   //for connct html file to webpack

npm i css-loader style-loader    //for css loading 
npm i file-loader //for any file loading 

//add this snippet in package.json file 
 "scripts": {
    "start": "webpack-dev-server --hot --open",
    "build": "webpack --config webpack.config.js  --mode prodcution"   //change mode to any like none prodcution and devlopment
  },


//npm run build -----------------for prodcution build


OTHERWISE  A BEAUTIFUL  CREATE-REACT-APP IS ------npm create-react-app nameofproject