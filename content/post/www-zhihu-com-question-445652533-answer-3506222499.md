---
title: '张敬信回答了问题: 如何在pandas 列值中找出连续增加的行？'
date: '2024-05-22'
linkTitle: https://www.zhihu.com/question/445652533/answer/3506222499
source: 张敬信的知乎动态
description: |-
  <p data-pid="E-oMmXio">R 语言 <code>tidyverse</code> 解法。</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span ...
disable_comments: true
---
<p data-pid="E-oMmXio">R 语言 <code>tidyverse</code> 解法。</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span ...