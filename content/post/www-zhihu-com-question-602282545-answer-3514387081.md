---
title: '张敬信回答了问题: 在Excel中，如何从一串不在左边的半角字符串中提取数字？'
date: '2024-05-29'
linkTitle: https://www.zhihu.com/question/602282545/answer/3514387081
source: 张敬信的知乎动态
description: |-
  <p data-pid="5EiMq15z">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="rK20e2on"><b>准备数据</b>（或者直接从Excel文件读取）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"/100g"</span><span class="p">,</span><span class="s">"/100ml"</span><span ...
disable_comments: true
---
<p data-pid="5EiMq15z">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="rK20e2on"><b>准备数据</b>（或者直接从Excel文件读取）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"/100g"</span><span class="p">,</span><span class="s">"/100ml"</span><span ...