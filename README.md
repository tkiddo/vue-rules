# souche-vue-rules

## 安装

```
npm install souche-vue-rules -D
```

## 使用

```js
// .eslintrc.js
module.exports = {
  extends: [require.resolve('souche-vue-rules/src/eslint')]
};
```

```js
// .prettierrc.js
const { prettier } = require('souche-vue-rules');

module.exports = {
  ...prettier
};
```
