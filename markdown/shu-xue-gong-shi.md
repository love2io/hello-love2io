# 数学公式

我们采用 [KaTeX](https://github.com/Khan/KaTeX) 数学公式库渲染数学公式。

KaTeX 由可汗学院出品，是一个易于使用，号称“最快”的数学公式渲染库。

## 行内公式
采用一对`$`符号包裹公式
```markdown
这是行内公式的演示$p(D) = \int p(D|w)P(w)dw$，它由一对$符号包裹。
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
  <p>这是行内公式的演示<span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi><mo>(</mo><mi>D</mi><mo>)</mo><mo>=</mo><mo>∫</mo><mi>p</mi><mo>(</mo><mi>D</mi><mi mathvariant="normal">∣</mi><mi>w</mi><mo>)</mo><mi>P</mi><mo>(</mo><mi>w</mi><mo>)</mo><mi>d</mi><mi>w</mi></mrow><annotation encoding="application/x-tex">p(D) = \int p(D|w)P(w)dw</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.805em;"></span><span class="strut bottom" style="height:1.11112em;vertical-align:-0.30612em;"></span><span class="base"><span class="mord mathit">p</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02778em;">D</span><span class="mclose">)</span><span class="mrel">=</span><span class="mop op-symbol small-op" style="margin-right:0.19445em;position:relative;top:-0.0005599999999999772em;">∫</span><span class="mord mathit">p</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02778em;">D</span><span class="mord mathrm">∣</span><span class="mord mathit" style="margin-right:0.02691em;">w</span><span class="mclose">)</span><span class="mord mathit" style="margin-right:0.13889em;">P</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02691em;">w</span><span class="mclose">)</span><span class="mord mathit">d</span><span class="mord mathit" style="margin-right:0.02691em;">w</span></span></span></span>，它由一对$符号包裹。</p>
</div>


## 行间公式
采用一对`$$`符号包裹公式
```markdown
这是行间公式的演示：
$$
p(D) = \int p(D|w)P(w)dw \tag{1.45}
$$
它由一对$$符号包裹。
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
  <p>这是行间公式的演示：<br><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>p</mi><mo>(</mo><mi>D</mi><mo>)</mo><mo>=</mo><mo>∫</mo><mi>p</mi><mo>(</mo><mi>D</mi><mi mathvariant="normal">∣</mi><mi>w</mi><mo>)</mo><mi>P</mi><mo>(</mo><mi>w</mi><mo>)</mo><mi>d</mi><mi>w</mi><mo><mo>(</mo><mspace width="0.333333em"></mspace><mtext>1.45</mtext><mo>)</mo></mo></mrow><annotation encoding="application/x-tex">
p(D) = \int p(D|w)P(w)dw \tag{1.45}
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:1.36em;"></span><span class="strut bottom" style="height:2.22225em;vertical-align:-0.86225em;"></span><span class="base"><span class="mord mathit">p</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02778em;">D</span><span class="mclose">)</span><span class="mrel">=</span><span class="mop op-symbol large-op" style="margin-right:0.44445em;position:relative;top:-0.0011249999999999316em;">∫</span><span class="mord mathit">p</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02778em;">D</span><span class="mord mathrm">∣</span><span class="mord mathit" style="margin-right:0.02691em;">w</span><span class="mclose">)</span><span class="mord mathit" style="margin-right:0.13889em;">P</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.02691em;">w</span><span class="mclose">)</span><span class="mord mathit">d</span><span class="mord mathit" style="margin-right:0.02691em;">w</span><span><span class="mspace quad"></span>(</span><span class="mord text"><span class="mord mathrm">1.45</span></span>)</span></span></span></span><br>它由一对$$符号包裹。</p>
</div>

## KaTeX 语法
更多 KaTeX 语法参考这个说明 [https://khan.github.io/KaTeX/function-support.html](https://khan.github.io/KaTeX/function-support.html)
