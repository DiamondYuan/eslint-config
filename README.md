## 使用方法

在你的项目根目录下创建 .eslintrc.js，根据不同情况，将代码复制到文件中：

### 标准规则

```bash
npm install --save-dev eslint babel-eslint @diamondyuan/eslint-config-javascript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/javascript"]
};
```

### React

```bash
npm install --save-dev eslint babel-eslint eslint-plugin-react @diamondyuan/eslint-config-react
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react"]
};
```

### TypeScript

```bash
npm install --save-dev eslint babel-eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin @diamondyuan/eslint-config-typescript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/typescript"]
};
```

### React TypeScript

```bash
npm install --save-dev eslint typescript babel-eslint eslint-plugin-react @typescript-eslint/parser @typescript-eslint/eslint-plugin @diamondyuan/eslint-config-react-typescript
```

```javascript
module.exports = {
  extends: ["@diamondyuan/react-typescript"]
};
```
