# [Solo](https://github.com/b3log/solo) [![Build Status](https://camo.githubusercontent.com/3a91735d578647431836fe0ec5f5d672835dba7e/68747470733a2f2f696d672e736869656c64732e696f2f7472617669732f62336c6f672f736f6c6f2e7376673f7374796c653d666c6174)](https://travis-ci.org/b3log/solo) [![Coverage Status](https://camo.githubusercontent.com/3e5b183e5f2e262cb9882e55500d40d6ddda4866/68747470733a2f2f696d672e736869656c64732e696f2f636f766572616c6c732f62336c6f672f736f6c6f2e7376673f7374796c653d666c6174)](https://coveralls.io/github/b3log/solo?branch=master) [![Apache License](https://camo.githubusercontent.com/f7601cc2aef545c494cea2c05e0422316218dfdb/687474703a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d617061636865322d6f72616e67652e7376673f7374796c653d666c6174)](http://www.apache.org/licenses/LICENSE-2.0) [![Download](https://camo.githubusercontent.com/e366ae3674c93acb84261e8294ef677cb11f031d/687474703a2f2f696d672e736869656c64732e696f2f62616467652f646f776e6c6f61642d253745372e354b2d626c75652e7376673f7374796c653d666c6174)](http://pan.baidu.com/share/link?shareid=541735&uk=3255126224)

[![Solo](https://camo.githubusercontent.com/8b05fd0a7e2f66e143869bcb795ccb20b6374276/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303034323132383238)](https://camo.githubusercontent.com/8b05fd0a7e2f66e143869bcb795ccb20b6374276/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303034323132383238)

- [简介](https://github.com/b3log/solo#%E7%AE%80%E4%BB%8B)
- [功能](https://github.com/b3log/solo#%E5%8A%9F%E8%83%BD)
- [安装](https://github.com/b3log/solo#%E5%AE%89%E8%A3%85)
- [技术](https://github.com/b3log/solo#%E6%8A%80%E6%9C%AF)
- [文档](https://github.com/b3log/solo#%E6%96%87%E6%A1%A3)
- [版本历史](https://github.com/b3log/solo#%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2)
- [贡献](https://github.com/b3log/solo#%E8%B4%A1%E7%8C%AE)
- [Terms](https://github.com/b3log/solo#terms)
- [鸣谢](https://github.com/b3log/solo#%E9%B8%A3%E8%B0%A2)
- [界面截图](https://github.com/b3log/solo#%E7%95%8C%E9%9D%A2%E6%88%AA%E5%9B%BE)[后台](https://github.com/b3log/solo#%E5%90%8E%E5%8F%B0)[编辑器](https://github.com/b3log/solo#%E7%BC%96%E8%BE%91%E5%99%A8)[内置的皮肤](https://github.com/b3log/solo#%E5%86%85%E7%BD%AE%E7%9A%84%E7%9A%AE%E8%82%A4)[社区贡献的皮肤](https://github.com/b3log/solo#%E7%A4%BE%E5%8C%BA%E8%B4%A1%E7%8C%AE%E7%9A%84%E7%9A%AE%E8%82%A4)

[![Activities](https://camo.githubusercontent.com/58c030d951f058608ff151be1b361bbe69de6d6f/68747470733a2f2f6772617068732e776166666c652e696f2f62336c6f672f736f6c6f2f7468726f7567687075742e737667)](https://waffle.io/b3log/solo/metrics/throughput)

## 简介

[Solo](https://github.com/b3log/solo) 是一款**一个命令**就能搭建好的 Java 开源博客系统，并内置了 15+ 套精心制作的皮肤。除此之外，Solo 还有着非常活跃的[社区](https://hacpai.com/b3log)，文章分享到社区后可以让很多人看到，产生丰富的交流互动。

## 功能

Solo 沉淀至今的**每一个功能你应该都会用到**。我们不会将只有“20%”用户使用的功能添加进来，只有这样才能保持博客系统本该有的纯净，足够轻量才能带来简约的使用体验。

- Markdown / TinyMCE / KindEditor
- 自定义导航（页面、链接）
- 草稿夹
- 评论/回复邮件提醒
- 随机文章 / 相关文章 / 置顶 / 更新提醒
- 自定义文章永久链接
- 自定义站点 SEO 参数
- 自定义公告 / 页脚
- 多个签名档
- 代码高亮
- [多皮肤，多端适配](https://github.com/b3log/solo-skins/tree/master/skin-preview) / [社区皮肤](https://github.com/b3log/solo-third-skins/tree/master/skin-preview)
- 多语言 / 国际化
- 上传七牛云
- 友情链接管理
- 多用户写作，团队博客
- SQL 文件导出
- 插件系统
- Atom / RSS 订阅
- Sitemap
- MetaWeblog API
- CDN 静态资源分离

如果有新版可用，升级过程也是非常简单的，只需要重新部署新版本就可以，不用运行额外的任何脚本。

另外，如果你想让我们将 Solo 修改为 CMS，我们只能对你说：“出门[右转](https://github.com/WordPress/WordPress)”。

## 安装

JDK 环境准备好之后[下载](http://pan.baidu.com/share/link?shareid=541735&uk=3255126224)最新的 Solo 包解压，进入解压目录执行：

- Windows: `java -cp WEB-INF/lib/*;WEB-INF/classes org.b3log.solo.Starter`
- Unix-like: `java -cp WEB-INF/lib/*:WEB-INF/classes org.b3log.solo.Starter`

执行完成后顺利的话你就可以看到 Solo 的初始化界面了 ![:tada:](https://assets-cdn.github.com/images/icons/emoji/unicode/1f389.png)

详细的配置请浏览[用户指南](https://github.com/b3log/solo/wiki/standalone_mode)。如果你碰到问题，请提 [issue](https://github.com/b3log/solo/issues/new) 或到[社区](https://hacpai.com/tag/Solo)发帖，我们会尽量在第一时间帮助你解决问题。

另外，如果你想用 Solo 但又不想自己维护服务器，那可以尝试购买我们搭建好的 Solo 直接[使用](http://b3log.org/services/#solo)。

## 技术

- 后端框架：为了尽量降低服务器的内存占用，顺带尝试[一些技术构想](https://hacpai.com/article/1403847528022)，我们开发了 [Latke](https://github.com/b3log/latke) 框架，并在此基础上构建了 Solo、Sym、XiaoV 等产品。这些产品反过来也会对框架提出需求，这是一个相互促进，共同演化的良性发展过程
- 前端框架：Solo 的前端部分为了降低复杂度， 只依赖于 jQuery、编辑器、代码高亮等组件。管理后台的 SPA 框架、皮肤响应式 UI 都是我们自己实现的

**没有最好的轮子，只有最适合的轮子。** BTW，如果你想研究如何制造 Web 轮子，Solo 是一个不错的入口。

另外，为了保证 Solo 的质量，我们也做了很多努力，包括：

- 统一规范的编码风格
- 完善的 javadoc 注释
- 严格的分支、缺陷追踪管理
- 不断完善的单元测试用例

## 文档

- [用户指南](https://github.com/b3log/solo/wiki/standalone_mode)：安装、配置、常见问题
- [开发指南](https://github.com/b3log/solo/wiki/Pre_dev)：开发环境、项目结构、框架说明
- [皮肤开发](https://github.com/b3log/solo/wiki/Develop_steps)：开发步骤、模版变量
- [插件开发](https://docs.google.com/document/pub?id=15H7Q3EBo-44v61Xp_epiYY7vK_gPJLkQaT7T1gkE64w&pli=1)：插件机制、处理流程

## 版本历史

Solo 的**第一个版本发布于 2010 年**，我们对每个版本都进行了详细的变更记录，[这里](http://solo.b3log.org/CHANGE_LOGS.html)可以看到 Solo 成长的全貌。

每一次开发新版本时我们都会在开发分支上进行，尽量避免给其他开发者们带来困扰。因为我们知道只有专业和尽责才能让 Solo 这个开源项目走得更远，**谁让你我的征途是星辰和大海呢！**

## 贡献

Solo 的主要作者是 [Daniel](https://github.com/88250) 与 [Vanessa](https://github.com/Vanessa219)，所有贡献者可以在[这里](https://github.com/b3log/solo/graphs/contributors)看到。

我们非常期待你加入到这个项目中，无论是使用反馈还是代码补丁，都是对 Solo 一份满满的爱 ![:heart:](https://assets-cdn.github.com/images/icons/emoji/unicode/2764.png)

## Terms

- This software is open sourced under the Apache License 2.0
- You can not get rid of the "Powered by [B3log 开源](http://b3log.org/)" from any page, even which you made
- If you want to use this software for commercial purpose, please mail to [support@liuyun.io](mailto:support@liuyun.io) for a commercial license request
- Copyright © b3log.org, all rights reserved
* [ ] 
## 鸣谢

Solo 的诞生离不开以下开源项目：

- [jQuery](https://github.com/jquery/jquery)：使用最广泛的 JavaScript 工具库
- [CodeMirror](https://github.com/codemirror/CodeMirror)：Markdown 编辑器内核
- [KindEditor](https://github.com/kindsoft/kindeditor)：一个富文本编辑器
- [TinyMCE](https://github.com/tinymce/tinymce)：又一个富文本编辑器
- [SyntaxHighlighter](https://github.com/syntaxhighlighter/syntaxhighlighter)：一个代码高亮库
- [Highlight.js](https://github.com/isagalaev/highlight.js)：又一个代码高亮库
- [emojify.js](https://github.com/Ranks/emojify.js)：前端 Emoji 处理库
- [jsoup](https://github.com/jhy/jsoup)：Java HTML 解析器
- [pegdown](https://github.com/sirthias/pegdown)：Java Markdown 处理库
- [Apache Commons](http://commons.apache.org/)：Java 工具库集
- [emoji-java](https://github.com/vdurmont/emoji-java)：Java Emoji 处理库
- [FreeMarker](http://freemarker.org/)：好用的 Java 模版引擎
- [H2](https://github.com/h2database/h2database)：Java SQL 数据库
- [Jetty](https://github.com/eclipse/jetty.project)：轻量级的 Java Web 容器
- [Latke](https://github.com/b3log/latke)：简洁高效的 Java Web 框架
- [NetBeans](https://netbeans.org/)：全宇宙暂时排名第三的 IDE

------

Logo 征集中....

------

## 界面截图

### 后台

- Admin - Post (TinyMCE/Markdown) [![Admin - Post (TinyMCE/Markdown)](https://camo.githubusercontent.com/cebd957b1d3bf37a195cebd023fdfbd3b2e13594/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303033393035303833)](https://camo.githubusercontent.com/cebd957b1d3bf37a195cebd023fdfbd3b2e13594/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303033393035303833)
- Admin - Skins[![Admin - Skins ](https://camo.githubusercontent.com/0da7e6053c84674fee858b4f380ed25c0f68a4e0/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303033383535313134)](https://camo.githubusercontent.com/0da7e6053c84674fee858b4f380ed25c0f68a4e0/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393039303033383535313134)

### 编辑器

[![editor](https://cloud.githubusercontent.com/assets/873584/20144758/9e70995e-a6d8-11e6-9bf8-1872994b4ff0.gif)](https://cloud.githubusercontent.com/assets/873584/20144758/9e70995e-a6d8-11e6-9bf8-1872994b4ff0.gif)

### 内置的皮肤

- [next](https://github.com/b3log/solo-skins/tree/master/next) [![next](https://github.com/b3log/solo-skins/raw/master/skin-preview/next.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/next.jpg?raw=true)
- [yilia](https://github.com/b3log/solo-skins/tree/master/yilia) [![yilia](https://github.com/b3log/solo-skins/raw/master/skin-preview/yilia.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/yilia.jpg?raw=true)
- [finding](https://github.com/b3log/solo-skins/tree/master/finding) [![finding](https://github.com/b3log/solo-skins/raw/master/skin-preview/finding.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/finding.jpg?raw=true)
- [metro-hot](https://github.com/b3log/solo-skins/tree/master/metro-hot) [![metro-hot](https://github.com/b3log/solo-skins/raw/master/skin-preview/metro-hot.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/metro-hot.jpg?raw=true)
- [timeline](https://github.com/b3log/solo-skins/tree/master/timeline) [![timeline](https://github.com/b3log/solo-skins/raw/master/skin-preview/timeline.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/timeline.jpg?raw=true)
- [ease](https://github.com/b3log/solo-skins/tree/master/ease) [![ease](https://github.com/b3log/solo-skins/raw/master/skin-preview/ease.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/ease.jpg?raw=true)
- [mobile](https://github.com/b3log/solo-skins/tree/master/mobile) 
  [![mobile](https://github.com/b3log/solo-skins/raw/master/skin-preview/mobile.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/mobile.jpg?raw=true)
- [andrea](https://github.com/b3log/solo-skins/tree/master/andrea) [![andrea](https://github.com/b3log/solo-skins/raw/master/skin-preview/andrea.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/andrea.jpg?raw=true)
- [classic](https://github.com/b3log/solo-skins/tree/master/classic) [![classic](https://github.com/b3log/solo-skins/raw/master/skin-preview/classic.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/classic.jpg?raw=true)
- [community](https://github.com/b3log/solo-skins/tree/master/community) [![community](https://github.com/b3log/solo-skins/raw/master/skin-preview/community.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/community.jpg?raw=true)
- [favourite](https://github.com/b3log/solo-skins/tree/master/favourite) [![favourite](https://github.com/b3log/solo-skins/raw/master/skin-preview/favourite.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/favourite.jpg?raw=true)
- [tree-house](https://github.com/b3log/solo-skins/tree/master/tree-house) [![tree-house](https://github.com/b3log/solo-skins/raw/master/skin-preview/tree-house.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/tree-house.jpg?raw=true)
- [i-nove](https://github.com/b3log/solo-skins/tree/master/i-nove) [![i-nove](https://github.com/b3log/solo-skins/raw/master/skin-preview/i-nove.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/i-nove.jpg?raw=true)
- [neoease](https://github.com/b3log/solo-skins/tree/master/neoease) [![neoease](https://github.com/b3log/solo-skins/raw/master/skin-preview/neoease.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/neoease.jpg?raw=true)
- [owmx-3.0](https://github.com/b3log/solo-skins/tree/master/owmx-3.0) [![owmx-3.0](https://github.com/b3log/solo-skins/raw/master/skin-preview/owmx-3.0.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/owmx-3.0.jpg?raw=true)
- [bruce](https://github.com/b3log/solo-skins/tree/master/bruce) [![bruce](https://github.com/b3log/solo-skins/raw/master/skin-preview/bruce.jpg?raw=true)](https://github.com/b3log/solo-skins/blob/master/skin-preview/bruce.jpg?raw=true)

### 社区贡献的皮肤

- [bootstyle](https://github.com/b3log/solo-third-skins/tree/master/bootstyle) [![bootstyle](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/bootstyle.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/bootstyle.jpg?raw=true)
- [dashu03](https://github.com/b3log/solo-third-skins/tree/master/dashu03) [![dashu03](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/dashu03.png?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/dashu03.png?raw=true)
- [community-bubbles](https://github.com/b3log/solo-third-skins/tree/master/community-bubbles) [![community-bubbles](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/community-bubbles.png?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/community-bubbles.png?raw=true)
- [Dot-B](https://github.com/b3log/solo-third-skins/tree/master/Dot-B) [![Dot-B](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/Dot-B.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/Dot-B.jpg?raw=true)
- [Shawn](https://github.com/b3log/solo-third-skins/tree/master/Shawn) [![Shawn](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/Shawn.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/Shawn.jpg?raw=true)
- [Coda](https://github.com/b3log/solo-third-skins/tree/master/Coda) [![Coda](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/Coda.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/Coda.jpg?raw=true)
- [5styles](https://github.com/b3log/solo-third-skins/tree/master/5styles) [![5styles](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/5styles.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/5styles.jpg?raw=true)
- [idream](https://github.com/b3log/solo-third-skins/tree/master/idream) [![idream](https://github.com/b3log/solo-third-skins/raw/master/skin-preview/idream.jpg?raw=true)](https://github.com/b3log/solo-third-skins/blob/master/skin-preview/idream.jpg?raw=true)