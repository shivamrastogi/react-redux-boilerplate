##Steps:
( In case if anyone wants to set it up by own )

1. Run `npm init -y`
2. Run `npm i webpack webpack-cli webpack-dev-server -D`
3. Run `npm i react react-dom -S`
4. Run `npm i babel-core babel-loader babel-preset-env babel-preset-react -D`
5. Run `npm i css-loader style-loader -D`
6. Run `npm i html-webpack-plugin -D`
7. Replace scripts in package.json with 
    `
    "start": "webpack-dev-server --mode development --open",
    "build": "webpack --mode production"
    `
8. Create **src** folder and create **index.js** and **index.html**.
9. Copy content of index.js and index.html from above project.
10. Copy webpack.config.js and paste it parallel to src.
11. Run `npm run start`