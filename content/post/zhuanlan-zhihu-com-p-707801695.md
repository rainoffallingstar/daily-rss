---
title: '张敬信发表了文章: 【Tidyverse优雅编程】按数值连续递增分组'
date: '2024-07-09'
linkTitle: https://zhuanlan.zhihu.com/p/707801695
source: 张敬信的知乎动态
description: <p data-pid="kF3JFWyk">问题来自我的读者：</p><p data-pid="plOD6YUH">比如，有一列数值<code>x</code>，
  </p><figure data-size="normal"><img src="https://pic3.zhimg.com/v2-b3d9f827c009d7bfa58825489ecfe316.jpg"
  data-caption="" data-size="normal" data-rawwidth="214" data-rawheight="515" class="content_image"
  data-original-token="v2-e7d0f1b53235de0f04e3af0cae8c7188" referrerpolicy="no-referrer"></figure><p
  data-pid="8PDLzW90">都是逐段连续递增的，想要识别出分组来，即想添加这样一列表示分组的<code>g</code> 。</p><p data-pid="7u1-Fujp">很实用、又很难解决的小问题，当然笨方法逐元素
  <code>for</code> 循环可以解决。</p><hr><h2>1 解决问题</h2><p ...
disable_comments: true
---
<p data-pid="kF3JFWyk">问题来自我的读者：</p><p data-pid="plOD6YUH">比如，有一列数值<code>x</code>， </p><figure data-size="normal"><img src="https://pic3.zhimg.com/v2-b3d9f827c009d7bfa58825489ecfe316.jpg" data-caption="" data-size="normal" data-rawwidth="214" data-rawheight="515" class="content_image" data-original-token="v2-e7d0f1b53235de0f04e3af0cae8c7188" referrerpolicy="no-referrer"></figure><p data-pid="8PDLzW90">都是逐段连续递增的，想要识别出分组来，即想添加这样一列表示分组的<code>g</code> 。</p><p data-pid="7u1-Fujp">很实用、又很难解决的小问题，当然笨方法逐元素 <code>for</code> 循环可以解决。</p><hr><h2>1 解决问题</h2><p ...