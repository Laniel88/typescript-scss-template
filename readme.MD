# Typescript Scss Template (no framework)

# Tools

To achieve that Webpack, with some plugins and loaders is used.
* ts-loader - loader for compiling .ts files and bundling it into bundle.js
* css-loader, sass-loader - loader for compiling styles , MiniCssExtractPlugin - for putting them into separate output css, scss file
* HtmlWebpackPlugin - plugin for fetching index.html entry point from sources and putting it into output folder.
* gh-pages - deploy tool for github pages

# How to install / run / build / deploy

* run `npm install` to fetch dependencies,
* run `npm start` to start local server,
* run `npm run build` to build production app - this will result in creating resources in `/dist` folder
* run `npm run deploy` to will build production app and deploy it to github pages

Then you only need to update titles, description and apps to start working on your own app.

# License

Creative Commons (CC) license