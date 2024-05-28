---
title: '张敬信回答了问题: R语言剔除数字的办法？'
date: '2024-05-28'
linkTitle: https://www.zhihu.com/question/657415147/answer/3513012280
source: 张敬信的知乎动态
description: <p data-pid="hDvsHixT">需要正则表达式。</p><div class="highlight"><pre><code
  class="language-ada"><span class="n">data</span><span class="p">.</span><span class="n">test</span>
  <span class="err">%</span><span class="o">&gt;</span><span class="err">%</span>
  <span class="n">mutate</span><span class="p">(</span><span class="n">across</span><span
  class="p">(</span><span class="n">everything</span><span class="p">(),</span> <span
  class="err">\</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
  <span class="n">str_remove</span><span class="p">(</span><span ...
disable_comments: true
---
<p data-pid="hDvsHixT">需要正则表达式。</p><div class="highlight"><pre><code class="language-ada"><span class="n">data</span><span class="p">.</span><span class="n">test</span> <span class="err">%</span><span class="o">&gt;</span><span class="err">%</span> <span class="n">mutate</span><span class="p">(</span><span class="n">across</span><span class="p">(</span><span class="n">everything</span><span class="p">(),</span> <span class="err">\</span><span class="p">(</span><span class="n">x</span><span class="p">)</span> <span class="n">str_remove</span><span class="p">(</span><span ...