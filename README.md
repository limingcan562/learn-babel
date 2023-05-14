

## 介绍

### 目录`know-babel-package`  
> 此文件夹存放：**了解`Babel`主要几个包**所涉及的案例

- `no-preset` 不利用预设编译
- `use-preset` 利用预设编译
- `compile-stage-1` 如何编译小于`stge-4`的语法
- `know-babel-polyfill` 初识 `@babel/polyfill`组成
- `import-regenerator-runtime` 感受手动引入`regenerator-runtime`包
- `no-import-regenerator-runtime` 感受不需要手动引入`regenerator-runtime`包
- `helper-functions` 什么是辅助函数
- `no-use-tranform-runtime` 不使用`@babel/plugin-transform-runtime`
- `use-transform-runtime` 使用`@babel/plugin-transform-runtime`

该目录`Babel`版本：
- `@babel/core`最新版本是：`7.20.12`
- `@babel/preset-env`最新版本是：`7.20.2`

### 目录`know-babel-config`  
> 此文件夹存放：**了解`Babel`如何配置** 所涉及的案例

- `preset-env-targets-config` 感受`@babel/preset-env`如何减少`ES6+`语法编译
- `preset-env-useBuiltIns-config` 体验`@babel/preset-env`配置`useBuiltIns`各值表现形式
- `preset-env-template-config` 配置`ES6+`在`IE 11`运行
- `use-third-party-library-problem` 使用第三方库时的问题
- `transform-runtime-config` 感受`@babel/plugin-transform-runtime`各配置项

该目录`Babel`版本：
- `@babel/core`最新版本是：`7.20.12`
- `@babel/preset-env`最新版本是：`7.20.2`

### 目录`new-babel-config`  
> 此文件夹存放：用`babel-plugin-polyfill-corejs3`来代替`Babel`旧的配置方法，相当于是`Babel`新的配置方法

- `entry-global` 感受新的配置方法`entry-global`可以替代旧的配置方法`useBuiltIns: entry`
- `usage-global` 感受新的配置方法`usage-global`可以替代旧的配置方法`useBuiltIns: usage`
- `usage-pure` 感受新的配置方法`usage-pure`可以替代，开发第三方库时的旧的配置方法
- `transform-runtime-targets-problem` 感受以前`@babel/transform-runtime`不能识别`targets`问题

该目录`Babel`版本：
- `@babel/core`最新版本是：`7.21.8`
- `@babel/preset-env`最新版本是：`7.21.5`

## 相关文章
[去查看](https://juejin.cn/column/7185787287601905701)
