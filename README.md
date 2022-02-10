# WebFont PT Root UI

Пакет для установки веб-шрифта: PT Root UI.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-pt-root-ui
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-pt-root-ui": "github:getscope/npm-webfont-pt-root-ui"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'PT Root UI', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-pt-root-ui/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-pt-root-ui/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-pt-root-ui/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-pt-root-ui/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-pt-root-ui/src/scss/_all-normal.scss";
```
