# 使用方法

在你的项目根目录下创建 .eslintrc.js，根据不同情况，将代码复制到文件中：

## prettier 配置

创建 `.prettierrc` 文件

```json
{
  "singleQuote": true,
  "trailingComma": "es5",
  "printWidth": 100,
  "proseWrap": "never"
}
```

## Javascript

```bash
npm install --save-dev eslint babel-eslint @diamondyuan/eslint-config-javascript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/javascript"]
};
```

### prettier

```bash
npm install --save-dev eslint-config-prettier prettier eslint-plugin-prettier
```

```bash
yarn add --dev eslint-config-prettier prettier eslint-plugin-prettier
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react-javascript", "prettier"],
  plugins: ["prettier"],
  rules: {
    "prettier/prettier": "error"
  }
};
```

## React

```bash
npm install --save-dev eslint babel-eslint eslint-plugin-react eslint-plugin-react-hooks @diamondyuan/eslint-config-react
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react"]
};
```

### prettier

```bash
npm install --save-dev eslint-config-prettier prettier eslint-plugin-prettier
```

```bash
yarn add --dev eslint-config-prettier prettier eslint-plugin-prettier
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react", "prettier", "prettier/react"],
  plugins: ["prettier"],
  rules: {
    "prettier/prettier": "error"
  }
};
```

## TypeScript

```bash
npm install --save-dev eslint babel-eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin @diamondyuan/eslint-config-typescript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/typescript"]
};
```

### prettier

```bash
npm install --save-dev eslint-config-prettier prettier eslint-plugin-prettier
```

```bash
yarn add --dev eslint-config-prettier prettier eslint-plugin-prettier
```

```javascript
module.exports = {
  extends: [
    "@diamondyuan/typescript",
    "prettier",
    "prettier/@typescript-eslint"
  ],
  plugins: ["prettier"],
  rules: {
    "prettier/prettier": "error"
  }
};
```

## React TypeScript

```bash
npm install --save-dev eslint typescript babel-eslint eslint-plugin-react eslint-plugin-react-hooks @typescript-eslint/parser @typescript-eslint/eslint-plugin @diamondyuan/eslint-config-react-typescript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react-typescript"]
};
```

### prettier

```bash
npm install --save-dev eslint-config-prettier prettier eslint-plugin-prettier
```

```bash
yarn add --dev eslint-config-prettier prettier eslint-plugin-prettier
```

```javascript
module.exports = {
  extends: [
    "@diamondyuan/react-typescript",
    "prettier",
    "prettier/@typescript-eslint",
    "prettier/react"
  ],
  plugins: ["prettier"],
  rules: {
    "prettier/prettier": "error"
  }
};
```
