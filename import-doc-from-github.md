# 从 GitHub 导入文档

## 在 GitHub 新建文档 Repo

Love2.io 支持从 GitHub 导入文档。

默认取 GitHub 对应文档仓库的 maser 分支的最新内容。请务必保证该仓库 master 分支的根目录存在索引文件 SUMMARY.md（大小写敏感）。该索引文件记录了文档的各个章节的标题和对应源文件的链接。

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



