---
title: deepin 25 preview DDE 移植简要指南
date: '2025-01-16'
linkTitle: https://deepin-community.github.io/sig-dde-porting/posts/deepin-25-preview-dde-porting-guide/?utm_source=atom_feed
source: Planet deepin | 简体中文
description: |-
  <p><em>编辑的话请把自己的名字加到作者名单里</em></p>
  <p>即将发布（你阅读到这个文章的时候可能已经发布了）的 deepin 25 preview 将会包含对应的新版 DDE。为了方便各个其它发行版的包维护者可以更方便的移植 DDE 到对应的发行版，这里提供一篇简要的移植指南，用以描述常见的移植问题和解决方案。</p>
  <blockquote>
  <p>下面对项目名称的称呼均以 GitHub 对应的原始仓库名为准。
  &#123;.note}</p>
  </blockquote>
  <h2 id="概览">概览</h2>
  <p>相对于 deepin 23，在 deepin 25 中，包括桌面、通知中心在内的大部分旧的 DDE 桌面组件已转化为 dde-shell 插件形式，以供更好的跨显示环境兼容性。包括控制中心在内的组件也已开始提供全新设计以及基于 QML 的全新界面。同时，我们也对 Qt、DTK 进行了更多完善，以供 DDE 组件以及 Treeland 能够更好的运行。</p>
  <p>由于这些项目的版本间互相影响，我们建议移植人员参照 ...
disable_comments: true
---
<p><em>编辑的话请把自己的名字加到作者名单里</em></p>
<p>即将发布（你阅读到这个文章的时候可能已经发布了）的 deepin 25 preview 将会包含对应的新版 DDE。为了方便各个其它发行版的包维护者可以更方便的移植 DDE 到对应的发行版，这里提供一篇简要的移植指南，用以描述常见的移植问题和解决方案。</p>
<blockquote>
<p>下面对项目名称的称呼均以 GitHub 对应的原始仓库名为准。
&#123;.note}</p>
</blockquote>
<h2 id="概览">概览</h2>
<p>相对于 deepin 23，在 deepin 25 中，包括桌面、通知中心在内的大部分旧的 DDE 桌面组件已转化为 dde-shell 插件形式，以供更好的跨显示环境兼容性。包括控制中心在内的组件也已开始提供全新设计以及基于 QML 的全新界面。同时，我们也对 Qt、DTK 进行了更多完善，以供 DDE 组件以及 Treeland 能够更好的运行。</p>
<p>由于这些项目的版本间互相影响，我们建议移植人员参照 ...