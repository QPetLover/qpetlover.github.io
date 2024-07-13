# docs

[qpetlover.cn](https://qpetlover.cn) 的主页源码，基于 [docsify](https://docsify.js.org/#/zh-cn/) 构建。

## 文档修改指南

代码地址：[https://github.com/cubenlp/docs](https://github.com/cubenlp/docs)，修改自动触发部署和更新：

```bash
git clone git@github.com:QPetLover/qpetlover.github.io.git
cd qpetlover.github.io
# 创建个人分支
git checkout -b mybranch
## 文档修改 
## git add/commit ##
git push -u origin mybranch
```

文档结构如下：

| 目录 | 说明 |
| --- | --- |
| `docs/` | 部署网页的源码位置 |
| `docs/index.html` | 主页 |
| `docs/source/` | 文档正文 |
| `docs/_navbar.md` | 顶部导航栏 |
| `docs/_sidebar.md` | 文档的目录，与 `source` 内容对应 |
| `docs/_coverpage.md` | 封面页 |
| `docs/assets/` | 静态资源，如图片、样式等 |

## 本地预览

```bash
npm i docsify-cli -g
docsify serve docs
```