超链接
====

行内式
----

格式为 `[link text](URL 'title text')`。

① 普通链接：

```markdown
[Google](http://www.google.com/)
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
"><p><a href="http://www.google.com/" target="_blank">Google</a></p></div>

② 指向本地文件的链接：

```markdown
[icon.png](./images/icon.png)
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
"><p><a href="./images/icon.png">icon.png</a></p></div>

③ 包含 'title' 的链接:

```markdown
[Google](http://www.google.com/ "Google")
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
"><p><a href="http://www.google.com/" target="_blank" title="Google">Google</a></p></div>

>title 使用 ' 或 " 都是可以的。

参考式
----

参考式链接的写法相当于行内式拆分成两部分，并通过一个 *识别符* 来连接两部分。参考式能尽量保持文章结构的简单，也方便统一管理 URL。

① 首先，定义链接：

```markdown
[Google][link]
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
"><p><a href="http://www.google.com/" target="_blank" title="Google">Google</a></p></div>

第二个方括号内为链接独有的 *识别符*，可以是字母、数字、空白或标点符号。识别符是 *不区分大小写* 的；

② 然后定义链接内容：

```markdown
[link]: http://www.google.com/ "Google"
```

[link]: http://www.google.com/ "Google"

其格式为：`[识别符]: URL 'title'`。

>其中，URL可以使用 <\> 包括起来，title 可以使用 ""、''、() 包括（考虑到兼容性，建议使用引号），title 部分也可以换行来写；

>链接内容的定义可以放在同一个文件的 *任意位置*；

③ 也可以省略 *识别符*，使用链接文本作为 *识别符*：

```markdown
[Google][]
[Google]: http://www.google.com/ "Google"
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
"><p><a href="http://www.google.com/" target="_blank" title="Google">Google</a></p></div>

>参考式相对于行内式有一个明显的优点，就是可以在多个不同的位置引用同一个 URL。

自动链接
----

使用 `<>` 包括的 URL 或邮箱地址会被自动转换为超链接：

```markdown
<http://www.google.com/>

<123@email.com>
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
"><p><a href="http://www.google.com/" target="_blank">http://www.google.com/</a></p><p><a href="mailto:123@email.com">123@email.com</a></p></div>

该方式适合行内较短的链接，会使用 URL 作为链接文字。邮箱地址会自动编码，以逃避抓取机器人。 
