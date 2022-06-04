# Week 1

[Keynote](https://docs.google.com/presentation/d/1ueYeLqAGyML2ZD_k5zguYwsYoI83sWACA9Q_pdgByMs/edit#slide=id.g13047660fc4_0_230)

## 前端、後端、全端

- UI/UX
- Frontend
- Backend
- Database
  - 後端的工作
- CI/CD
  - DevOps

## 基本技能

- HTML
- CSS
  - CSS Hacking
    - 為特殊的瀏覽器家不同的 tag
    - 現在前端核心只剩三個，不太再需要這個
- JavaScript
- Debugging tools
  - Chrome, Firefox debugging tool
- Node.js / npm
  - 後端的東西
  - 但現代寫前端很難不用到

## 前端生態圈

[Roadmap](https://github.com/kamranahmedse/developer-roadmap)

- JS Framework
  - React
  - Vue
  - Angular
- UI Framework
  - CSS first frameworks which
    don't come with JavaScript
    framework components by
    default
    - Bootstrap
    - Bulma
  - JS based and better to use
    with your framework based
    JavaScript applications
    - Tailwind CSS
    - Chakra UI
    - Material UI
    - Radix UI
- Bundler
- Task manager

## 開發環境

- Node.js / npm
  - nvm
    - node 版本切換管理
- npm / yarn
- editor

## 實作

- [React](https://reactjs.org/)
  - create-react-app
  - [create-react-app hello-react](./hello-react)
- [Vue](https://vuejs.org/)
  - @vue/cli
  - [vue create hello-vue](./hello-vue)
- [Angular](https://angular.io/)
  - @angular/cli
  - [ng new hello-angular](./hello-angular/)

## `package.json`

- `scripts`
  - 配合 `npm` 或 `yarn` 使用的執行腳本
- `dependency`
  - 專案 build 的時候需要的 package
- `devDependencies`
  - 專案開發時需要的 package

## 其他

- [HMR](https://webpack.js.org/concepts/hot-module-replacement/)
  - 修改時即時 Render
