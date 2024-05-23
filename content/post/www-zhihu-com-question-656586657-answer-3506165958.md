---
title: '张敬信回答了问题: 如何计算出EXCEL表格中的日期列表中与系统当前时间在大于24小时的个数？'
date: '2024-05-22'
linkTitle: https://www.zhihu.com/question/656586657/answer/3506165958
source: 张敬信的知乎动态
description: |-
  <p data-pid="JcchlMmI">R 语言 tidyverse 优雅数据思维解法。</p><p data-pid="41STX74v"><b>编一个小数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span> <span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"2024-05-21 16:05:59"</span><span class="p">,</span> <span class="s">"2024-05-20 11:15:39"</span><span ...
disable_comments: true
---
<p data-pid="JcchlMmI">R 语言 tidyverse 优雅数据思维解法。</p><p data-pid="41STX74v"><b>编一个小数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span> <span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"2024-05-21 16:05:59"</span><span class="p">,</span> <span class="s">"2024-05-20 11:15:39"</span><span ...