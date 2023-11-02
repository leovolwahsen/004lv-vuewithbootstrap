## Step by step guide how to use bootstrap in vue3
```sh
1. npm init vue@latest projectname
```
```sh
2. cd projectname
```
```sh
3. npm i bootstrap
```
```sh
4. in file main.js add
   - import "bootstrap/dist/css/bootstrap.css";
   - import bootstrap from "bootstrap/dist/js/bootstrap.bundle.js";
   - createApp(App).use(bootstrap).mount('#app')
```
```sh
5. Add bootstrap code (dont need bootstrap-vue just the normal bootstrap)
```

# 004lv-vuewithbootstrap

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
