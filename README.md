# electron-vue-template
This repo is combination of [this](https://auth0.com/blog/electron-tutorial-building-modern-desktop-apps-with-vue-js/) and [this](https://github.com/SimulatedGREG/electron-vue/issues/855) solutions for updating electron in [simulatedgreg/electron-vue boilerplate](https://github.com/SimulatedGREG/electron-vue).

Project generated with parameters:

* Sass / Scc enabled
* axios
* vue-electron
* vue-router
* vuex
* ESLint (Standard)
* Unit testing Karma + Mocha
* end-toend testing Spectron + Mocha
* build with electron-builder

### For windows users:
if you need vue devtools extension, when uncomment strings 14 - 21 in `src/main/index.dev.js`, but when you have to delete `DevTools Extensions` file in `C:\Users\%USER%\AppData\Roaming\Electron` before every dev launch

Vue devtools on Mac and Linux not testet, but seems, that it is only windows related problem