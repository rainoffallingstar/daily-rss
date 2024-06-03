---
title: '量子位发表了文章: ICML2024高分！魔改注意力，让小模型能打两倍大的模型'
date: '2024-06-03'
linkTitle: https://zhuanlan.zhihu.com/p/701356541
source: 量子位的知乎动态
description: <blockquote data-pid="vQviGZJW">彩云科技团队 投稿<br>量子位 | 公众号 QbitAI</blockquote><p
  data-pid="ANKQXfby">改进Transformer核心机制注意力，让<b>小模型能打两倍大的模型</b>！</p><p data-pid="qhqMNw1F">ICML
  2024高分论文，彩云科技团队构建<b>DCFormer</b>框架，替换Transformer核心组件多头注意力模块（MHA），提出<b>可动态组合的多头注意力</b>（DCMHA）。</p><p
  data-pid="UGQJDWTz">DCMHA解除了MHA注意力头的查找选择回路和变换回路的固定绑定，让它们可以根据输入动态组合，从根本上提升了模型的表达能力。</p><p
  data-pid="KUla70xJ">可以近似理解为，原来每层有固定的H个注意力头，现在用几乎同样的参数量和算力，可按需动态组合出多至HxH个注意力头。</p><p
  data-pid="ACKiXWm7">DCMHA即插即用，<b>可在任何Transformer架构中替换MHA</b>，得到通用、高 ...
disable_comments: true
---
<blockquote data-pid="vQviGZJW">彩云科技团队 投稿<br>量子位 | 公众号 QbitAI</blockquote><p data-pid="ANKQXfby">改进Transformer核心机制注意力，让<b>小模型能打两倍大的模型</b>！</p><p data-pid="qhqMNw1F">ICML 2024高分论文，彩云科技团队构建<b>DCFormer</b>框架，替换Transformer核心组件多头注意力模块（MHA），提出<b>可动态组合的多头注意力</b>（DCMHA）。</p><p data-pid="UGQJDWTz">DCMHA解除了MHA注意力头的查找选择回路和变换回路的固定绑定，让它们可以根据输入动态组合，从根本上提升了模型的表达能力。</p><p data-pid="KUla70xJ">可以近似理解为，原来每层有固定的H个注意力头，现在用几乎同样的参数量和算力，可按需动态组合出多至HxH个注意力头。</p><p data-pid="ACKiXWm7">DCMHA即插即用，<b>可在任何Transformer架构中替换MHA</b>，得到通用、高 ...