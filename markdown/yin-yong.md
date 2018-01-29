引用
====

1. 引用内容
----

在段落或其他内容前使用 `>` 符号，就可以将这段内容标记为 '引用' 的内容（`<blockquote>`）：

```markdown
>引用内容
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
"><blockquote><p>引用内容</p></blockquote></div>

2. 多行引用
----

```markdown
>多行引用
>可以在每行前加 `>`
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
">
<blockquote><p>多行引用<br>可以在每行前加 <code>&gt;</code></p></blockquote></div>

```markdown
>如果仅在第一行使用 `>`，
后面相邻的行即使省略 `>`，也会变成引用内容
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
"><blockquote><p>如果仅在第一行使用 <code>&gt;</code>，<br>后面相邻的行即使省略 <code>&gt;</code>，也会变成引用内容</p></blockquote></div>

```markdown
>如果引用内容需要换行，  
>可以在行尾添加两个空格
>
>或者在引用内容中加一个空行
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
"><blockquote><p>如果引用内容需要换行，<br>可以在行尾添加两个空格</p>
<p>或者在引用内容中加一个空行</p></blockquote></div>

3. 嵌套引用
----

```markdown
>也可以在引用中
>>使用嵌套的引用
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
"><blockquote><p>也可以在引用中</p><blockquote><p>使用嵌套的引用</p></blockquote></blockquote></div>

4. 其他 Markdown
----

```markdown
>在引用中可以使用使用其他任何 *Markdown* 语法
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
"><blockquote><p>在引用中可以使用使用其他任何 <em>Markdown</em> 语法 </p></blockquote></div>
