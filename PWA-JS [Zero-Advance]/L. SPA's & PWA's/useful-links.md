# Useful Resources:

- create-react-app Page: https://github.com/facebookincubator/create-react-app
- Angular CLI Github Page: https://github.com/angular/angular-cli
- Overview over Angular Service Worker Usage: https://fluin.io/blog/angular-service-worker
- PWAs with Angular: https://medium.com/@amcdnl/service-worker-pwas-with-the-angular-cli-98a8f16d62d6
- Vue CLI PWA Template Page: https://github.com/vuejs-templates/pwa
- More about sw-precache-webpack-plugin: https://www.npmjs.com/package/sw-precache-webpack-plugin
- Important: If you DON'T want to replace sw-precache with Workbox but still want to add your own Service Worker logic, you have to use the importScripts[]  option on the sw-precache config to import your own Service Worker file into the generated one. This allows you to add your own logic.