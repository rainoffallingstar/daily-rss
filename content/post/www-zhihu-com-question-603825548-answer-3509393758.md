---
title: '张敬信回答了问题: 如何将两个EXCEL表中数据做对比找出差异？'
date: '2024-05-25'
linkTitle: https://www.zhihu.com/question/603825548/answer/3509393758
source: 张敬信的知乎动态
description: |-
  <p data-pid="8iST5oKV">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="IQQpaub-">假设你两个表分别叫 <code>temp1.xlsx</code>，<code>temp2.xlsx</code>，第一列列名叫 类别</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">library</span><span class="p">(</span><span class="n">readxl</span><span class="p">)</span>
  <span class="n">df1</span> <span class="o">=</span> <span class="n">read_xlsx</span><span class="p">(</span><span class="s">"temp1.xlsx"</span><span ...
disable_comments: true
---
<p data-pid="8iST5oKV">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="IQQpaub-">假设你两个表分别叫 <code>temp1.xlsx</code>，<code>temp2.xlsx</code>，第一列列名叫 类别</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">library</span><span class="p">(</span><span class="n">readxl</span><span class="p">)</span>
<span class="n">df1</span> <span class="o">=</span> <span class="n">read_xlsx</span><span class="p">(</span><span class="s">"temp1.xlsx"</span><span ...