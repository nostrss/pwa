# 1.React Set up

> npx create-react-app pwa

# 2.Install gh-pages and package.json setting

> npm i gh-pages

```json
//package.json

"homepage": "http://nostrss.github.io/pwa",

"predeploy": "npm run build",
"deploy": "cp build/index.html build/404.html && gh-pages -d build"
```

# 3. Add service-worker

- service-worker.js
- serviceWorkerRegistration.js
