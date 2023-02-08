# 💖 Hello, violetUI

![image](https://raw.githubusercontent.com/zhaoyuuu/violetUI/master/assets/readme-logo.png)

`violet-design` 是基于 React 框架的 UI 组件库。

## 📦 安装

### 使用 npm 安装

`npm install violet-design`

### 浏览器引入

在浏览器中使用 `script` 和 `link` 标签直接引入文件，并使用全局变量 `violet-design`。

## 🔨 示例

```js
import React from 'react';
import { Button } from 'violet-design';

const App = () => (
  <>
    <Button btnType="primary" size="lg">PRESS ME</Button>
  </>
);
```

### 按需加载

`violet-design` 默认支持基于 ES modules 的 tree shaking。
