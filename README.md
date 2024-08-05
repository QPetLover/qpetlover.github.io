# QPet Lover 文档

欢迎来到 [qpetlover.cn](https://qpetlover.cn) 的文档仓库，基于 [mkdocs-material](https://github.com/squidfunk/mkdocs-material) 构建。

## 文档修改指南（仓库开发者）

代码地址：[https://github.com/QPetLover/qpetlover.github.io](https://github.com/QPetLover/qpetlover.github.io)，修改自动触发部署和更新：

```bash
git clone git@github.com:QPetLover/qpetlover.github.io.git
cd qpetlover.github.io
# 创建个人分支
git checkout -b mybranch
## 文档修改 
## git add/commit ##
git push -u origin mybranch
```

## 文档结构

| 目录 | 说明 |
| --- | --- |
| `docs/` | 部署网页的源码位置 |
| `docs/index.md` | 主页 |
| `docs/source/` | 文档正文 |
| `docs/assets/` | 静态资源，如图片、样式等 |

## 本地预览

要在本地预览文档，请确保已安装 `mkdocs` 和 `mkdocs-material`：

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

## 贡献指南

我们欢迎任何形式的贡献！如果你有任何建议或发现了问题，请提交 Issue 或 Pull Request。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
