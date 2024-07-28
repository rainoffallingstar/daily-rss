---
title: '张敬信回答了问题: 如何在 Excel 中指定行，求和其所在行指定数的总数？'
date: '2024-07-22'
linkTitle: https://www.zhihu.com/question/662145194/answer/3569753519
source: 张敬信的知乎动态
description: |-
  <p data-pid="UZG7xTmJ"><code>R</code>语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="dAWtvfmo">从截图原样的 <code>excel</code> 文件<b>读取数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_excel</span><span class="p">(</span><span class="s">"temp.xlsx"</span><span class="p">,</span> <span class="n">col_names</span> <span ...
disable_comments: true
---
<p data-pid="UZG7xTmJ"><code>R</code>语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="dAWtvfmo">从截图原样的 <code>excel</code> 文件<b>读取数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_excel</span><span class="p">(</span><span class="s">"temp.xlsx"</span><span class="p">,</span> <span class="n">col_names</span> <span ...