---
title: '张敬信回答了问题: Excel如何将一长串字符拆分成每三个字符一格？'
date: '2024-05-30'
linkTitle: https://www.zhihu.com/question/448938602/answer/3514834358
source: 张敬信的知乎动态
description: |-
  <p data-pid="EDMLUWPG">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="fcavZuUV"><b>准备数据</b>（或者直接从Excel读取）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"OST1NF1SG2NF2ST4AA57"</span><span class="p">,</span> <span class="s">"M5A75FC6X171 ...
disable_comments: true
---
<p data-pid="EDMLUWPG">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="fcavZuUV"><b>准备数据</b>（或者直接从Excel读取）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"OST1NF1SG2NF2ST4AA57"</span><span class="p">,</span> <span class="s">"M5A75FC6X171 ...