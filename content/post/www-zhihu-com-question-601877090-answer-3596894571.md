---
title: '张敬信回答了问题: 如何将某一列的数字，在另一列都分成相应个数的1，但是其他列单元格的内容不变？'
date: '2024-08-16'
linkTitle: https://www.zhihu.com/question/601877090/answer/3596894571
source: 张敬信的知乎动态
description: |-
  <p data-pid="Rjbxkvtt"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="ScJ8ro1w">准备数据（或者直接从 <code>Excel</code> 文件读取）：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">A</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"cu2305"</span><span class="p">,</span> <span class="s">"bc2701"</spa ...
disable_comments: true
---
<p data-pid="Rjbxkvtt"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="ScJ8ro1w">准备数据（或者直接从 <code>Excel</code> 文件读取）：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">A</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"cu2305"</span><span class="p">,</span> <span class="s">"bc2701"</spa ...