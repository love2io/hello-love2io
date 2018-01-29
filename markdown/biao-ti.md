标题
====

1. Setext 形式
----

```markdown
H1
====

H2
----
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
"><h1 id="h1">H1</h1><h2 id="h2">H2</h2></div>


>`=` 和 `-` 的数量是没有限制的。通常的做法是使其和标题文本的长度相同，这样看起来比较舒服。或者可以像我一样，用四个 `-` 或 `=`。  
>Setext 形式只支持 `h1` 和 `h2` 两种标题。

2. atx 形式
----

① 可以用对称的 `#` 包括文本：

```markdown
#### H4 ####

##### H5 #####
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
"><h4 id="h4">H4</h4><h5 id="h5">H5</h5></div>

② 也可以只在左边使用 `#`：

```markdown
#### H4

##### H5
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
"><h4 id="h4">H4</h4><h5 id="h5">H5</h5></div>


③ 成对的 `#` 左侧和只在左边使用的 `#` 左侧都不可以有任何空白，但其内侧可以使用空白。

```markdown
 ### 左侧使用了空格 ###

#### 内侧使用了空格
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
"><h3 id="-">左侧使用了空格</h3><h4 id="-">内侧使用了空格</h4></div>

>在这一点上，可能各种 Markdown 的实现会有不同的结果，不过仍然需要我们遵守语法规则。 
