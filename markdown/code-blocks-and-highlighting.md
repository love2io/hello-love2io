代码块和语法高亮
====

代码块
----

与原来使用缩进来添加代码块的语法不同，这里使用 \`\`\` \`\`\` 来包含多行代码：

<pre><code>```<br><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>code here<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span>
```
</code></pre>

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
"><pre><code><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>code here<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span>
</code></pre></div>

>三个 \`\`\` 要独占一行。

代码高亮
----

在上面的代码块语法基础上，在第一组 \`\`\` 之后添加代码的语言，如 'javascript' 或 'js'，即可将代码标记为 `JavaScript`：

<pre><code class="js">```js<br><span class="hljs-built_in">window</span>.addEventListener(<span class="hljs-string">'load'</span>, <span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>) </span>{
  <span class="hljs-built_in">console</span>.log(<span class="hljs-string">'window loaded'</span>);
});
```</code></pre>

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
"><pre><code class="js"><span class="hljs-built_in">window</span>.addEventListener(<span class="hljs-string">'load'</span>, <span class="hljs-function"><span class="hljs-keyword">function</span>(<span class="hljs-params"></span>) </span>{
  <span class="hljs-built_in">console</span>.log(<span class="hljs-string">'window loaded'</span>);
});
</code></pre></div>
