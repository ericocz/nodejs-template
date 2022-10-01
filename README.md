# nodejs-template

clone the project, and you can write nodejs right away. support typescript.

## 简介

这是一个 nodejs 项目模板，支持 prettier 代码格式化，支持使用 typescript，你可以配合任何 nodejs 框架使用。

-   husky 是在每次 git commit 操作时，自动 format 代码，保证团队代码风格统一
-   prettier 配合 vscode，在每次保存代码时，自动 format 代码
-   nodemon 在每次保存代码时，能自动重新启动一次 node 服务，有点类似前端的热更新
-   typescript 是 javascript 的超集，最重要的特性是静态类型校验

## 使用

-   开发使用下面命令，使用 nodemon 启动 nodejs 服务，支持热更新

```
    npm run dev
```

-   部署到服务器上，使用下面命令，先把 typescript 编译成 javascript，输出到 build 目录，然后用 nodejs 启动 build/index.js

```
    npm run start
```

## TODO

-   [ ] 支持 pm2 部署
