# electronjs-project

- Inflearn :: [[Electron #1] Electron + React로 만드는 타이머 앱 (With Zustand)](https://www.inflearn.com/course/자바스크립트-gui-개발-1-elec/dashboard)
- Notion :: [[Electron #1] Electron + React로 만드는 타이머 앱 (With Zustand)](https://trusting-apparel-eb8.notion.site/Electron-1-Electron-React-With-Zustand-18daac19ed70808c8e7adbd2dc0334e3)

---

```shell
# ~/
$ mkdir ~/electronjs-project
$ mkdir frontend
$ mkdir electron
$ cd frontend
$ npm create vite@latest . -- --template react
$ npm install
$ npm run dev
(h + enter)
(o + enter)
(q + enter)
```

```shell
# ~/electronjs-project/frontend
$ npm install tailwindcss @tailwindcss/vite --legacy-peer-deps
$ vim vite.config.js
$ rm src/App.css
$ vim src/index.css
(https://marketplace.cursorapi.com/items/?itemName=dsznajder.es7-react-js-snippets)
(https://marketplace.cursorapi.com/items/?itemName=esbenp.prettier-vscode)
(https://marketplace.cursorapi.com/items/?itemName=bradlc.vscode-tailwindcss)
$ vim .vscode/settings.json
{
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "prettier.tabWidth": 4
}
$ vim src/App.jsx
(`> Snippet search` or `Shift + CMD + R`)
(% rafce)
$ npm run dev
$ vim src/index.css
$ npm run dev
```

```shell
# ~/electronjs-project
$ npm install electon --save-dev
$ cd electron
$ touch index.js preload.js package.json
$ vim index.js
$ vim preload.js
$ vim package.json
$ cd frontend && npm run dev
$ cd electron && npm run start
```

```shell
# ~/electronjs-project
$ npm init -y
$ npm install concurrently
$ vim package.json
$ npm run dev
```

```shell
# ~/electronjs-project
$ cd frontend
$ npm install zustand --legacy-peer-deps
$ npm install react --legacy-peer-deps
$ mkdir -p src/Shared/Stores
$ touch src/Shared/Stores/ThemeStore.js
$ vim src/Shared/Stores/ThemeStore.js
$ npm install
$ cd ..
$ npm run dev
```
