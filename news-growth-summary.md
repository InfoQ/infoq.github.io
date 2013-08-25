---
layout: page
title: "技术应用状态纪实"
description: ""
---
{% include JB/setup %}

有的新闻事件不涉及到具体的某一次版本发布或战略发布，但是在过去的一段时间内，如一个月、三个月、半年内，有很多小进展的，这种情况就适合以技术应用状态纪实的方式进行报道。

几个典型的适用情况：

* 某技术标准，如HTML5的某个标准，发生了哪些进展
* 某个项目，如OpenStack，都新增了哪些成员和用户
* 某个技术组织，如国内的Ruby社区，都组织了哪些活动，有哪些成果

## 范文：[Google Dart新进展：Polymer代替Web UI](http://www.infoq.com/cn/news/2013/07/dart-polymer-web-ui)

标题：某某技术的名字在什么领域的综述（可以加一个年月时间戳在括号里）

第一部分：一句话说明这个技术在过去一段时间内发生的主要变化。

> Google Dart将舍弃Web UI，并用Polymer代替它。从表面上看，它们的主要差别是数据绑定和事件处理。

第二部分：列出已经发生的事件。

> Google的Dart团队已经开始将Polymer移植到Dart。许多组件已经完成并打包，包括observe、mdv、shadow_dom和polymer.dart。

第三部分：列出计划中的事件。

> 据Dart工程师John Messerly介绍，其余功能也将在不久的将来完成，包括：
> 
> * 声明式<polymer-element>和定制元素
> * 更多新的或最新的polyfill包，如html_imports
> * 删除polymer.dart的强制编译步骤，只需编辑、保存和刷新
> * 将Polymer UI元素引入Dart
> * 上述所有新亮点的最新文档

第四部分：列出这些变化可能对用户造成的影响，以及用户的反应。

> Dart切换新的UI框架使许多用户感到意外：
> 
> Thomas Løcke：我很高兴有了Polymer，但不要误会我的意思，失去Web UI 我很难过。我已经在Web UI上花费了大量时间。
> 
> Bernd Wessels：Polymer.dart之后是什么呢？ 难道Dart（Web开发的未来）的主要UI框架要基于一组松散的polyfill的集合？我对此表示怀疑。

最后：你总是可以找到一些相关资料推荐给读者：）

> 关于Polymer的更多细节可以阅读InfoQ的新闻：使用Google Polymer的Web组件。Google的另一个重要框架Angular.js正在移植到Dart。更多信息请查看这则新闻：AngularJS正在移植到Dart上 。