---
title: '张敬信回答了问题: 如何把Excel的A列指定的内容批量提取到B列？'
date: '2024-11-21'
linkTitle: https://www.zhihu.com/question/808054335/answer/36735987193
source: 张敬信的知乎动态
description: |-
  <p data-pid="vpwWWRPH"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="SyYgJ7Qd"><b>准备数据</b>（或直接从 <code>Excel</code> 文件读取）：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"你好A开心"</span><span class="p">,</span><span ...
disable_comments: true
---
<p data-pid="vpwWWRPH"><code>R</code> 语言 <code>tidyverse</code> 优雅数据思维解法。</p><p data-pid="SyYgJ7Qd"><b>准备数据</b>（或直接从 <code>Excel</code> 文件读取）：</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">tibble</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">c</span><span class="p">(</span><span class="s">"你好A开心"</span><span class="p">,</span><span ...