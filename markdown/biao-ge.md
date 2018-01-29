表格
====

单元格和表头
----

使用 `|` 来分隔不同的单元格，使用 `-` 来分隔表头和其他行：

```markdown
name | age
---- | ---
LearnShare | 12
Mike |  32
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
"><table><thead><tr><th>name</th><th>age</th></tr></thead><tbody><tr><td>LearnShare</td><td>12</td></tr><tr><td>Mike</td><td>32</td></tr></tbody></table></div>

为了美观，可以使用空格对齐不同行的单元格，并在左右两侧都使用 `|` 来标记单元格边界：

```markdown
|    name    | age |
| ---------- | --- |
| LearnShare |  12 |
| Mike       |  32 |
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
"><table><thead><tr><th>name</th><th>age</th></tr></thead><tbody><tr><td>LearnShare</td><td>12</td></tr><tr><td>Mike</td><td>32</td></tr></tbody></table></div>

>为了使 Markdown 更清晰，`|` 和 `-` 两侧需要至少有一个空格（最左侧和最右侧的 `|` 外就不需要了）。

对齐
----

在表头下方的分隔线标记中加入 `:`，即可标记下方单元格内容的对齐方式：

+ `:---` 代表左对齐
+ `:--:` 代表居中对齐
+ `---:` 代表右对齐

```markdown
| left | center | right |
| :--- | :----: | ----: |
| aaaa | bbbbbb | ccccc |
| a    | b      | c     |
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
"><table><thead><tr><th style="text-align:left">left</th><th style="text-align:center">center</th><th style="text-align:right">right</th></tr></thead><tbody><tr><td style="text-align:left">aaaa</td><td style="text-align:center">bbbbbb</td><td style="text-align:right">ccccc</td></tr><tr><td style="text-align:left">a</td><td style="text-align:center">b</td><td style="text-align:right">c</td></tr></tbody></table></div>

>如果不使用对齐标记，单元格中的内容默认左对齐；表头单元格中的内容会一直居中对齐（不同的实现可能会有不同表现）。

插入其他内容
----

表格中可以插入其他 Markdown 中的行内标记：

```markdown
|     name     | age |             blog                |
| ------------ | --- | ------------------------------- |
| _LearnShare_ |  12 | [LearnShare](http://xianbai.me) |
| __Mike__     |  32 | [Mike](http://mike.me)          |
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
"><table><thead><tr><th>name</th><th>age</th><th>blog</th></tr></thead><tbody><tr><td><em>LearnShare</em></td><td>12</td><td><a href="http://xianbai.me" target="_blank">LearnShare</a></td></tr><tr><td><strong>Mike</strong></td><td>32</td><td><a href="http://mike.me" target="_blank">Mike</a></td></tr></tbody></table></div>
