---
title: '张敬信回答了问题: 怎么用Excel最简单的函数进行获取对应的门店，需要获取对应区域的销售前几名的店铺名称？'
date: '2024-07-11'
linkTitle: https://www.zhihu.com/question/661210964/answer/3559095264
source: 张敬信的知乎动态
description: |-
  <p data-pid="58F3-5vz">R 语言 tidyverse 优雅数据思维解法。</p><p data-pid="obxyTFtz"><b>读取数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
  <span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_excel</span><span class="p">(</span><span class="s">"temp.xls"</span><span class="p">)</span>
  <span class="n">df</span></code></pre></div><figure data-size="normal"><img src="https://pic1.zhimg.com/v2-4e93c ...
disable_comments: true
---
<p data-pid="58F3-5vz">R 语言 tidyverse 优雅数据思维解法。</p><p data-pid="obxyTFtz"><b>读取数据：</b></p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">readxl</span><span class="p">::</span><span class="n">read_excel</span><span class="p">(</span><span class="s">"temp.xls"</span><span class="p">)</span>
<span class="n">df</span></code></pre></div><figure data-size="normal"><img src="https://pic1.zhimg.com/v2-4e93c ...