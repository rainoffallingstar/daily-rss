---
title: '张敬信回答了问题: excel怎么统计一列数字单双各个个数？'
date: '2024-11-20'
linkTitle: https://www.zhihu.com/question/4544852825/answer/36344004612
source: 张敬信的知乎动态
description: |-
  <p data-pid="ERHhI0nT">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="ucJ8NoqT"><b>准备数据：</b>因为从Excel文件读取的话是数据框，所以就模拟数据框了</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">set</span><span class="p">.</span><span class="n">seed</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span ...
disable_comments: true
---
<p data-pid="ERHhI0nT">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="ucJ8NoqT"><b>准备数据：</b>因为从Excel文件读取的话是数据框，所以就模拟数据框了</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">set</span><span class="p">.</span><span class="n">seed</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span ...