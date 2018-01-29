列表
====

无序列表
----

```markdown
* 可以使用 `*` 作为标记
+ 也可以使用 `+`
- 或者 `-`
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
"><ul><li>可以使用 <code>*</code> 作为标记</li></ul></div>

有序列表
----

```markdown
1. 有序列表以数字和 `.` 开始；
3. 数字的序列并不会影响生成的列表序列；
4. 但仍然推荐按照自然顺序（1.2.3...）编写。
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
"><ol><li>有序列表以数字和 <code>.</code> 开始；</li><li>数字的序列并不会影响生成的列表序列；</li><li>但仍然推荐按照自然顺序（1.2.3…）编写。</li></ol></div>

嵌套的列表
----

```markdown
1. 第一层
  + 1-1
  + 1-2
2. 无序列表和有序列表可以随意相互嵌套
  1. 2-1
  2. 2-2
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
"><ol><li>第一层<ul><li>1-1</li><li>1-2</li></ul></li><li>无序列表和有序列表可以随意相互嵌套<ol><li>2-1</li><li>2-2</li></ol></li></ol></div>

语法和用法
----

1. 无序列表项的开始是：符号 空格；
2. 有序列表项的开始是：数字 `.` 空格；
3. 空格至少为一个，多个空格将被解析为一个；
4. 如果仅需要在行前显示数字和 `.`：

```markdown
05\. 可以使用：数字\. 来取消显示为列表
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
"><p>05. 可以使用：数字\. 来取消显示为列表</p></div>

>`\*` 的语法专门用来显示 Markdown 语法中使用的特殊字符，参考 [字符转义](blackslash-escapes.md) 
