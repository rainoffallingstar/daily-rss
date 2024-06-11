---
title: '张敬信发表了文章: 【R-mlr3新书节选】数据集划分、重抽样、嵌套重抽样'
date: '2024-06-11'
linkTitle: https://zhuanlan.zhihu.com/p/702813239
source: 张敬信的知乎动态
description: <h2>1.2 如何使用数据集</h2><p data-pid="VeAcnHdZ">......</p><h3>1.2.2 数据集划分</h3><p
  data-pid="GGs4DWUY">将相同的数据用于训练模型和测试性能是一种不好的策略，因为这会导致过于乐观的性能估计。例如，一个过拟合的模型可能只需通过记住训练数据就可以对训练数据进行完美预测，但是对新数据可能只是随机猜测。</p><p
  data-pid="MNVtc8nJ">所以，数据集（或重抽样副本）通常先要划分为两部分：<b>训练集、测试集</b>。</p><ul><li data-pid="nFANKJxP"><b>训练集</b>是训练模型用的，用的时候需要再划分为：</li></ul><p
  data-pid="iaO4YsFG"> - <b>训练集</b>：用来训练模型参数的数据集，模型直接根据训练集来调整自身获得更好的预测效果。</p><p data-pid="vpHSTfHr">
  - <b>验证集</b>：用于在训练过程中验证模型的性能、收敛情况：</p><p data-pid="00smSikF"> + ...
disable_comments: true
---
<h2>1.2 如何使用数据集</h2><p data-pid="VeAcnHdZ">......</p><h3>1.2.2 数据集划分</h3><p data-pid="GGs4DWUY">将相同的数据用于训练模型和测试性能是一种不好的策略，因为这会导致过于乐观的性能估计。例如，一个过拟合的模型可能只需通过记住训练数据就可以对训练数据进行完美预测，但是对新数据可能只是随机猜测。</p><p data-pid="MNVtc8nJ">所以，数据集（或重抽样副本）通常先要划分为两部分：<b>训练集、测试集</b>。</p><ul><li data-pid="nFANKJxP"><b>训练集</b>是训练模型用的，用的时候需要再划分为：</li></ul><p data-pid="iaO4YsFG"> - <b>训练集</b>：用来训练模型参数的数据集，模型直接根据训练集来调整自身获得更好的预测效果。</p><p data-pid="vpHSTfHr"> - <b>验证集</b>：用于在训练过程中验证模型的性能、收敛情况：</p><p data-pid="00smSikF"> + ...