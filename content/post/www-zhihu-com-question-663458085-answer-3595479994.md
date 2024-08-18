---
title: '张敬信回答了问题: 在EXCEL表格中如何利用公式计算R1-R2,R4,R6-R7的数量？'
date: '2024-08-15'
linkTitle: https://www.zhihu.com/question/663458085/answer/3595479994
source: 张敬信的知乎动态
description: |-
  <p data-pid="dzHgxAP1"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="6wNFgn8K"><b>准备数据</b>（或者直接从 <code>Excel</code> 文件读取） ：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"A1-A500"</span><span class="p">,</span> <span ...
disable_comments: true
---
<p data-pid="dzHgxAP1"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="6wNFgn8K"><b>准备数据</b>（或者直接从 <code>Excel</code> 文件读取） ：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"A1-A500"</span><span class="p">,</span> <span ...