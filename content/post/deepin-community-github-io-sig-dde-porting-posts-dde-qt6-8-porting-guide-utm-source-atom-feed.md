---
title: DDE Qt 6.8 适配说明
date: '2024-10-25'
linkTitle: https://deepin-community.github.io/sig-dde-porting/posts/dde-qt6.8-porting-guide/?utm_source=atom_feed
source: Planet deepin | 简体中文
description: |-
  <h1 id="dde-qt-68-适配说明">DDE Qt 6.8 适配说明</h1>
  <p>Qt 6.8 发布已经有一段时间了，各个发行版尝试移植 DDE 时发现包括 dde-shell 在内的几个组件存在比较明显的问题，DDE 小组进行了相关的紧急修复。由于 DDE 部分项目也在分叉维护的状态，为了方便各位移植人员有效进行移植，故在此罗列相关注意事项。</p>
  <p><em>注：笔者所测试的环境为 Arch Linux，下述为 2024/10/25 testing 仓库状态下的测试结论。若未另行说明，则下述涉及到的项目名称仍然使用了与 DDE 对应项目原始仓库的名称，而非各个发行版下的包名。</em></p>
  <h2 id="分支与-tag-说明">分支与 tag 说明</h2>
  <p>因维护需要，对于部分 DDE 组件（dde-shell、dde-launchpad、dde-tray-loader），我们对 deepin 23 所使用的分支创建了名为 <code>release/beige</code> ...
disable_comments: true
---
<h1 id="dde-qt-68-适配说明">DDE Qt 6.8 适配说明</h1>
<p>Qt 6.8 发布已经有一段时间了，各个发行版尝试移植 DDE 时发现包括 dde-shell 在内的几个组件存在比较明显的问题，DDE 小组进行了相关的紧急修复。由于 DDE 部分项目也在分叉维护的状态，为了方便各位移植人员有效进行移植，故在此罗列相关注意事项。</p>
<p><em>注：笔者所测试的环境为 Arch Linux，下述为 2024/10/25 testing 仓库状态下的测试结论。若未另行说明，则下述涉及到的项目名称仍然使用了与 DDE 对应项目原始仓库的名称，而非各个发行版下的包名。</em></p>
<h2 id="分支与-tag-说明">分支与 tag 说明</h2>
<p>因维护需要，对于部分 DDE 组件（dde-shell、dde-launchpad、dde-tray-loader），我们对 deepin 23 所使用的分支创建了名为 <code>release/beige</code> ...