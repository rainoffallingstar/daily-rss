---
title: 'Cosven赞同了回答: 为什么我觉得doris数据库这么难用。。。?'
date: '2024-10-17'
linkTitle: https://www.zhihu.com/question/502448538/answer/3360749666
source: Cosven的知乎动态
description: <blockquote data-pid="3j0KlK3k"> 上个月某一天流量晚高峰的时候，Doris 集群突然出现告警，CPU 使用率高于
  90%，从七点初到八点多，持续了一个多小时。这是之前没有遇到过的，影响了线上环境直播功能很大一部分的数据查询，算是一次比较严重的事故。当天晚上的集群维护我没有参与，第二天才开始排查故障原因，下面是梳理了整个排查的思路和过程。</blockquote><p
  data-pid="zmXIuc5l">在开始之前，先说一下我们的集群情况，版本是 1.2.7，集群是3 FE、3 BE，其中 FE 是 1 个 Follower
  和 2 个 Observer，每个 BE 是 16 核 64G。</p><h3>现象</h3><p data-pid="IgIGApNc">晚上 19 点 12
  分开始，BE 的 CPU 使用率持续爆满</p><div class="highlight"><pre><code ...
disable_comments: true
---
<blockquote data-pid="3j0KlK3k"> 上个月某一天流量晚高峰的时候，Doris 集群突然出现告警，CPU 使用率高于 90%，从七点初到八点多，持续了一个多小时。这是之前没有遇到过的，影响了线上环境直播功能很大一部分的数据查询，算是一次比较严重的事故。当天晚上的集群维护我没有参与，第二天才开始排查故障原因，下面是梳理了整个排查的思路和过程。</blockquote><p data-pid="zmXIuc5l">在开始之前，先说一下我们的集群情况，版本是 1.2.7，集群是3 FE、3 BE，其中 FE 是 1 个 Follower 和 2 个 Observer，每个 BE 是 16 核 64G。</p><h3>现象</h3><p data-pid="IgIGApNc">晚上 19 点 12 分开始，BE 的 CPU 使用率持续爆满</p><div class="highlight"><pre><code ...