---
title: '张敬信发表了文章: 【R-mlr3新书节选】决策树II：CART算法'
date: '2024-07-02'
linkTitle: https://zhuanlan.zhihu.com/p/706690900
source: 张敬信的知乎动态
description: <p data-pid="tsqpNqZf">本文节选自我正在写的R新书：<b>《R机器学习：基于mlr3verse》，已与机械工业出版社签约出版，预计25年上市！敬请期待！</b></p><hr><h3>9.2.1
  CART算法</h3><p data-pid="WZzFmv5w">以上决策树算法，基于熵涉及大量对数运算，只能做分类。1984年，Breiman等提出了 CART（分类回归树）算法，用<code>Gini</code>指数来代替熵，递归地构建二叉树。</p><p
  data-pid="MrxQIMgC">离散型随机变量 <img src="https://www.zhihu.com/equation?tex=X" alt="X"
  eeimg="1" referrerpolicy="no-referrer"> 的概率分布为 <img src="https://www.zhihu.com/equation?tex=P%28X%3Dx_i%29%3Dp_i%2C+%5C%2C+k%3D1%2C%5C%2C+%5Ccdots%2C+%5C%2C+n"
  alt="P(X=x_i)=p_i, \, k=1,\, \cdots, \, n" eeimg="1" referrerpolicy="no-referrer
  ...
disable_comments: true
---
<p data-pid="tsqpNqZf">本文节选自我正在写的R新书：<b>《R机器学习：基于mlr3verse》，已与机械工业出版社签约出版，预计25年上市！敬请期待！</b></p><hr><h3>9.2.1 CART算法</h3><p data-pid="WZzFmv5w">以上决策树算法，基于熵涉及大量对数运算，只能做分类。1984年，Breiman等提出了 CART（分类回归树）算法，用<code>Gini</code>指数来代替熵，递归地构建二叉树。</p><p data-pid="MrxQIMgC">离散型随机变量 <img src="https://www.zhihu.com/equation?tex=X" alt="X" eeimg="1" referrerpolicy="no-referrer"> 的概率分布为 <img src="https://www.zhihu.com/equation?tex=P%28X%3Dx_i%29%3Dp_i%2C+%5C%2C+k%3D1%2C%5C%2C+%5Ccdots%2C+%5C%2C+n" alt="P(X=x_i)=p_i, \, k=1,\, \cdots, \, n" eeimg="1" referrerpolicy="no-referrer ...