---
title: '张敬信回答了问题: excle根据条件提取多个值？求函数？'
date: '2024-05-22'
linkTitle: https://www.zhihu.com/question/656336044/answer/3506138340
source: 张敬信的知乎动态
description: |-
  <p data-pid="dZrV4KgX">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="Z68fRa60"><b>准备数据</b>（或者直接从Excel文件读取 <code>df = readxl::read_xlsx("temp.xlsx")</code>）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"a16"</span><span ...
disable_comments: true
---
<p data-pid="dZrV4KgX">R 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="Z68fRa60"><b>准备数据</b>（或者直接从Excel文件读取 <code>df = readxl::read_xlsx("temp.xlsx")</code>）</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"a16"</span><span ...