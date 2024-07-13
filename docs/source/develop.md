# 开发指南

## 添加教程文档

fork 仓库到自己的账号下，然后 clone 到本地。

```bash
# 改为 fork 的仓库地址
git clone git@github.com:QPetLover/qpetlover.github.io.git
cd qpetlover.github.io
```

在 `source` 下添加文档，并在 `_sidebar.md` 中添加目录。

提交代码，然后创建 PR。

```bash
git add .
git commit -m "add new doc"
git push
```

## 本地预览

```bash
npm i docsify-cli -g
docsify serve docs
```