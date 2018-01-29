图像
====

插入图片的语法和插入超链接的语法基本一致，只是在最前面多一个 `!`。也分为行内式和参考式两种。

行内式
----

```markdown
![GitHub](https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding")
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
"><p><a href="//avatars2.githubusercontent.com/u/3265208?v=3&amp;s=100" target="_blank"><img src="//avatars2.githubusercontent.com/u/3265208?v=3&amp;s=100" alt="GitHub" style="max-width:100%;"></a></p></div>

方括号中的部分是图片的替代文本，括号中的 'title' 部分和链接一样，是可选的。

参考式
----

```markdown
![GitHub][github]

[github]: https://avatars2.githubusercontent.com/u/3265208?v=3&s=100 "GitHub,Social Coding"
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
"><p><a href="//avatars2.githubusercontent.com/u/3265208?v=3&amp;s=100" target="_blank"><img src="//avatars2.githubusercontent.com/u/3265208?v=3&amp;s=100" alt="GitHub" style="max-width:100%;"></a></p></div>

指定图片的显示大小
----

Markdown 不支持指定图片的显示大小，不过可以通过直接插入`<img />`标签来指定相关属性：

```html
<img src="https://avatars2.githubusercontent.com/u/3265208?v=3&s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />
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
"><p><img src="https://avatars2.githubusercontent.com/u/3265208?v=3&amp;s=100" alt="GitHub" title="GitHub,Social Coding" width="50" height="50"></p></div>
