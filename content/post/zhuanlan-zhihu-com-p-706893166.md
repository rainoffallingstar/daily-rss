---
title: '张敬信发表了文章: 【R-mlr3新书节选】决策树案例：分类树预测泰坦尼克生存'
date: '2024-07-03'
linkTitle: https://zhuanlan.zhihu.com/p/706893166
source: 张敬信的知乎动态
description: <p data-pid="pt22r1yK">本文节选自我正在写的R新书：<b>《R机器学习：基于mlr3verse》，已与机械工业出版社签约出版，预计25年上市！敬请期待！</b></p><hr><h2>9.3.1
  分类树预测泰坦尼克生存</h2><p data-pid="fK4KLNjd">以经典的<code>titanic</code>数据集为例，它记录了泰坦尼克号上乘客的信息，包括性别、年龄、船舱等级、票价等，目标是预测乘客是否在泰坦尼克号沉没事件中生存下来（1表示生存，0表示死亡）。</p><p
  data-pid="fpQ4dlAJ">同时，借助管道技术，展示数据预处理、缺失值插补、特征工程、图学习器调参的流程化操作。</p><div class="highlight"><pre><code
  class="language-ada"><span class="n">library</span><span class="p">(</span><span
  class="n">tidyverse</span><span class="p">)</span> <span class="n">library</span><span
  class="p">(</span><span class="n">mlr3verse</span><span ...
disable_comments: true
---
<p data-pid="pt22r1yK">本文节选自我正在写的R新书：<b>《R机器学习：基于mlr3verse》，已与机械工业出版社签约出版，预计25年上市！敬请期待！</b></p><hr><h2>9.3.1 分类树预测泰坦尼克生存</h2><p data-pid="fK4KLNjd">以经典的<code>titanic</code>数据集为例，它记录了泰坦尼克号上乘客的信息，包括性别、年龄、船舱等级、票价等，目标是预测乘客是否在泰坦尼克号沉没事件中生存下来（1表示生存，0表示死亡）。</p><p data-pid="fpQ4dlAJ">同时，借助管道技术，展示数据预处理、缺失值插补、特征工程、图学习器调参的流程化操作。</p><div class="highlight"><pre><code class="language-ada"><span class="n">library</span><span class="p">(</span><span class="n">tidyverse</span><span class="p">)</span> <span class="n">library</span><span class="p">(</span><span class="n">mlr3verse</span><span ...