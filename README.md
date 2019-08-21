# framework7-authentication-demo

This is the source code for my tutorial video on [how to signup, login and logout users in Framework7 using Firebase](framework7-authentication-demo).

My blog: http://www.timo-ernst.net

My twitter: http://www.twitter.com/timo_ernst

## NPM Scripts

* `npm start` - run development server
* `npm run build-prod` - build web app for production
* `npm run build-dev` - build web app using development mode (faster build without minification and optimization)

## WebPack

There is a webpack bundler setup. It compiles and bundles all "front-end" resources. You should work only with files located in `/src` folder. Webpack config located in `build/webpack.config.js`.

Webpack has specific way of handling static assets (CSS files, images, audios). You can learn more about correct way of doing things on [official webpack documentation](https://webpack.js.org/guides/asset-management/).
