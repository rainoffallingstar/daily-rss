---
title: '张敬信回答了问题: excel怎么从多个组合中找出没出现过的组合？'
date: '2024-06-14'
linkTitle: https://www.zhihu.com/question/658797952/answer/3530640222
source: 张敬信的知乎动态
description: |-
  <p data-pid="sXMzHQjl">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="PqUMXvDf"><b>准备数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_xlsx</span><span class="p">(</span><span class="s">"temp/temp.xlsx"</span><span class="p">,</span> <span class="n">col_names</span> <span class="o">=</span> <span class="kc">FALSE</span><span ...
disable_comments: true
---
<p data-pid="sXMzHQjl">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="PqUMXvDf"><b>准备数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_xlsx</span><span class="p">(</span><span class="s">"temp/temp.xlsx"</span><span class="p">,</span> <span class="n">col_names</span> <span class="o">=</span> <span class="kc">FALSE</span><span ...