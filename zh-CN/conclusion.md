---
layout: default
title: 祝贺您！
number: 8
locale: zh-CN
---

您已完成所有课程！

信不信由你，我们才刚刚开始探索Markdown可以实现的目标。Markdown有许多“扩展”实现，它们支持表格，定义列表，脚注等格式。由于它们不是标准的，因此对于学习基础知识不是必需的，正如我们在此处介绍的那样。

如果您想了解有关Markdown实现的更多信息，欢迎探索其他Markdown应用教程。这里仅仅是少数：

{% for link in site.data.resources.links %}
* <{{ link }}>
{% endfor %}
