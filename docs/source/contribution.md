# 贡献指南

目前账号还有很多功能没有完善，欢迎大家一起来改进。

## 添加教程文档

fork 仓库到自己的账号下，然后 clone 到本地。

```bash
# 改为 fork 的仓库地址
git clone git@github.com:QPetLover/qpetlover.github.io.git
cd qpetlover.github.io
```

 `source` 目录下添加文档，并在 `_sidebar.md` 中添加目录。

提交代码，然后创建 PR。

```bash
git add .
git commit -m "add new doc"
git push
```

本地预览：

```bash
mkdocs serve
```

## 其他

其他想法或建议，欢迎讨论。