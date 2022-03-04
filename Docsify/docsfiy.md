### docsify

#### 1、下载node.js,全局安装docsify

```
npm i docsify-cli -g
```

#### 2、初始化项目

```
docsify init ./docs
```

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

`index.html` 入口文件

`README.md` 会做为主页内容渲染

`.nojekyll` 用于阻止 GitHub Pages 会忽略掉下划线开头的文件

#### 3、本地预览网站

```bash
docsify serve
```

默认通过 http://localhost:3000访问





