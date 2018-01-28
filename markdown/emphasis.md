Skip to content
This repository
Search
Pull requests
Issues
Marketplace
Explore
 @love2io
 Sign out
 Watch 0
  Unstar 2  Fork 400 love2io/Learning-Markdown
forked from LearnShare/Learning-Markdown
 Code  Pull requests 0  Projects 0  Insights  Settings
Learning-Markdown/article/syntax/ 
emphasis.md
   or cancel
    
 Edit file    Preview changes
1
强调
2
====
3
​
4
1\. 使用 `* *` 或 `_ _` 包括的文本会被转换为 `<em></em>` ，通常表现为斜体：
5
​
6
```markdown
7
这是用来 *演示* 的 _文本_
8
```
9
​
10
这是用来 *演示* 的 _文本_
11
​
12
2\. 使用 `** **` 或 `__ __` 包括的文本会被转换为 `<strong></strong>`，通常表现为加粗：
13
​
14
```markdown
15
这是用来 **演示** 的 __文本__
16
```
17
​
18
这是用来 **演示** 的 __文本__
19
​
20
3\. 用来包括文本的 `*` 或 `_` 内侧不能有空白，否则 `*` 和 `_` 将不会被转换（不同的实现会有不同的表现）：
21
​
22
```markdown
23
这是用来 * 演示* 的 _文本 _
24
```
25
​
26
这是用来 * 演示* 的 _文本 _
27
​
28
4\. 如果需要在文本中显示成对的 `*` 或 `_`，可以在符号前加入 `\` 即可：
29
​
30
```markdown
31
这是用来 \*演示\* 的 \_文本\_
32
```
33
​
34
这是用来 \*演示\* 的 \_文本\_
35
​
36
5\. `*`、`**`、`_` 和 `__` 都必须 *成对使用* 。
37
​
@love2io
Commit changes

Update emphasis.md

Add an optional extended description…
  Commit directly to the master branch.
  Create a new branch for this commit and start a pull request. Learn more about pull requests.
Commit changes  Cancel
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About