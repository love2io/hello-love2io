# 从 GitHub 导入文档

## 在 GitHub 新建文档 Repo

Love2.io 目前仅支持从 GitHub 导入的方式发布文档。所以作者需要先在 GitHub 建立一个 Repo 用于撰写文档。

当从 GitHub 导入文档 Repo 后，Love2.io 默认会取该 Repo master 分支的最新 Commit 的文件内容。

## 建立文档索引文件 SUMMARY.md

发布的文档会默认取 master 分支最新 Commit 对应的 SUMMARY.md 文件作为该文档的索引。请务必保证该仓库 master 分支的根目录存在索引文件 SUMMARY.md（文件名大小写敏感）。该索引文件记录了文档的各个章节的标题和对应源文件的链接。

SUMMARY.md 文件示例

```Markdown
* [第一章](chapter1.md)
* [第二章](chapter2/chapter2.md)
    * [第一节](chapter2/section1.md)
    * [第二节](chapter2/section2.md)
* 第三章
    * [第一节](chapter3/section1.md)
* 第四章
    * [第一节](chapter4/section1.md)
```

![](/assets/Jietu20180122-102511.jpg)

