# TypeScriptElectronTemplate

## 项目介绍

### ✨这是什么？

 - 这是一个基于 TypeScript 和 Vue3 的 Electron 快速上手框架，因为现在使用Ts的Electron项目太少了，所以我们自己搭建了一共项目模板。
 - 上手极快，跟正常使用Vue3 + TypeScript一样，只不过在此基础上添加了Electron的功能。

### 💡️有什么优点？

 - 自动构建Windows、Mac、Linux三个平台的安装包，无需配置，只需一行命令。并且支持Github的Actions自动构建。 
 - 热更新模式，修改main.ts config.ts等文件后，无需重启，直接刷新页面即可。
 - Github相关项目少之又少，这个项目是我们自己搭建的，所以我们会持续更新，如果有问题，我们会及时修复。

> ### **⚠请确保您的 node 环境是大于或等于 20.11.1⚠**

## 🧑‍💻如何安装

```bash
# 使用yarn安装
yarn

# 启动之后，会随机生成一个端口号。
yarn dev 或者 npm run dev

# build命令在不同系统环境中，需要的的不一样，需要自己根据自身环境进行配置
# 将ts编译js
yarn build
# 进入编译后的文件夹
cd build/app
# 安装依赖
yarn install
# 编译成Electron
yarn make 

# 进入out就是编译后的文件
```
---
## 👥项目维护者
- [Wzp-2008 的 GitHub](https://github.com/Wzp-2008)
- [Dongyifengs 的 GitHub](https://github.com/Dongyifengs)
---
## ⚖️ 开源协议
- 本项目是面向大众的，所以我们会进行开源,请遵循相关开源协议 [MIT](https://github.com/Wzp-2008/TypeScriptElectronTemplate/blob/main/LICENSE) 的规则.
- 众人拾柴火焰高，开源需要依靠大家的努力，请自觉遵守开源协议，弘扬开源精神，共建开源社区！
---
## 🍀 鸣谢
<div align="center"><img alt="Logo" height="256" src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png?_gl=1*avq98w*_ga*NjQ5OTM0MzUxLjE2NDY1NTIyMzQ.*_ga_V0XZL7QHEB*MTY0Njk2NjY2Mi4zLjAuMTY0Njk2NjY2Mi4w" width="256"/></div>
---
### 更新日志
 - 2024-09-21: 新建项目文件，添加了基本的配置文件。