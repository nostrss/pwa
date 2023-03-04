# React Set up

> npx create-react-app pwa

# install gh-pages and package.json setting

> npm i gh-pages

```json
//package.json

"homepage": "http://nostrss.github.io/pwa",

"predeploy": "npm run build",
"deploy": "cp build/index.html build/404.html && gh-pages -d build"
```
