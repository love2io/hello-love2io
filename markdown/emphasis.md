强调
====

1\. 使用 `* *` 或 `_ _` 包括的文本会被转换为 `<em></em>` ，通常表现为斜体：

```markdown
这是用来 *演示* 的 _文本_
```

<div style="
    border: 1px solid #eee;
    border-radius: 2px;
    padding: 25px 35px;
    margin-top: 1em;
    margin-bottom: 40px;
    line-height: 1.5em;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    overflow-x: auto;
"><p>这是用来 <em>演示</em> 的 <em>文本</em></p></div>

2\. 使用 `** **` 或 `__ __` 包括的文本会被转换为 `<strong></strong>`，通常表现为加粗：

```markdown
这是用来 **演示** 的 __文本__
```

<div style="
    border: 1px solid #eee;
    border-radius: 2px;
    padding: 25px 35px;
    margin-top: 1em;
    margin-bottom: 40px;
    line-height: 1.5em;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    overflow-x: auto;
"><p>这是用来 <strong>演示</strong> 的 <strong>文本</strong></p></div>

3\. 用来包括文本的 `*` 或 `_` 内侧不能有空白，否则 `*` 和 `_` 将不会被转换（不同的实现会有不同的表现）：

```markdown
这是用来 * 演示* 的 _文本 _
```

<div style="
    border: 1px solid #eee;
    border-radius: 2px;
    padding: 25px 35px;
    margin-top: 1em;
    margin-bottom: 40px;
    line-height: 1.5em;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    overflow-x: auto;
"><p>这是用来 <em> 演示</em> 的 <em>文本 </em></p></div>

4\. 如果需要在文本中显示成对的 `*` 或 `_`，可以在符号前加入 `\` 即可：

```markdown
这是用来 \*演示\* 的 \_文本\_
```

<div style="
    border: 1px solid #eee;
    border-radius: 2px;
    padding: 25px 35px;
    margin-top: 1em;
    margin-bottom: 40px;
    line-height: 1.5em;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    overflow-x: auto;
"><p>这是用来 *演示* 的 _文本_</p></div>

5\. `*`、`**`、`_` 和 `__` 都必须 *成对使用* 。
