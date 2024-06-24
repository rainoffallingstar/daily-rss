---
title: '张敬信回答了问题: 如何根据日期整理统计单号？'
date: '2024-06-24'
linkTitle: https://www.zhihu.com/question/659653789/answer/3540486112
source: 张敬信的知乎动态
description: |-
  <p data-pid="JMyTHvnD"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="err">%</span><span class="o">&gt;</span><span class="err">%</span> <span class="n">summarise</span><span class="p">(</span><span class="n">B</span> <span class="o">=</span> <span class="n">str_c</span><span class="p">(</span><span class="n">B</span><span class="p">,</span> <span class="n">collapse</span> ...
disable_comments: true
---
<p data-pid="JMyTHvnD"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="err">%</span><span class="o">&gt;</span><span class="err">%</span> <span class="n">summarise</span><span class="p">(</span><span class="n">B</span> <span class="o">=</span> <span class="n">str_c</span><span class="p">(</span><span class="n">B</span><span class="p">,</span> <span class="n">collapse</span> ...