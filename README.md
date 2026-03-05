[![PyPI 上的软件包](https://img.shields.io/pypi/v/jam.py-v7.svg)](https://pypi.org/project/jam.py-v7) ![支持的 Python 版本](https://img.shields.io/pypi/pyversions/python3-saml.svg) [![文档状态](https://readthedocs.org/projects/jampy-docs-v7/badge/)](https://jampy-docs-v7.readthedocs.io) [![下载量](https://static.pepy.tech/badge/jam.py-v7)](http://pepy.tech/project/jam.py-v7)


## Jam.py 是一个 Web 前端应用程序生成器，可与现有数据库和新创建的数据库一起使用。
## 支持 Monaco 编辑器和 Databricks！

## 这是 jam.py 的分支，旨在继续提供支持和开发，因为 Andrew 已从 jam.py 项目退休。V7 现已全面发布。请在以下链接中找到 v5 master 分支的存档：https://github.com/jam-py-v5/jam-py/

## LLMS-full.txt 已发布：
https://jampy-docs.readthedocs.io/projects/V7/zh-cn/latest/llms-full.txt 
和 
https://jampy-docs.readthedocs.io/projects/V7/zh-cn/latest/llms.txt

内置所有功能且事件驱动！什么是 EDA：

"事件驱动框架，也称为事件驱动架构（EDA），是一种软件组件通过状态变化或事件进行通信和响应的设计模式。" Jam.py 中的一切都可以是一个事件。例如鼠标点击，或按下 CRTL+Ins、CTRL+Del 或您定义的任何操作。

与其他产品的主要区别在于，整个应用程序都被包含在一个 **单个 SQLite3 文件** 中。并且可以 **加密**！

另一个关键区别是能够 **直接在应用程序构建器中将任何 Python 过程在后端运行** ——包括流行的库，如 Matplotlib、Pandas 和 NumPy —— 而结果在浏览器中显示。Python 过程可以在服务器上 **同步** 或 **异步** 运行。

此外，使用来自任何受数据库支持的 **导入表格** 功能，可提供 **即时 Web 前端**。无需编写任何代码，并且 **身份验证一键即可完成**！

希望这能激发您的兴趣！谢谢。

## 安装和启动

```
pip install jam.py-v7
jam-project.py
server.py
```

[![Jam.py 演示](https://github.com/platipusica/jampy-docs-v7-zh-cn/blob/main/_static/builder_animation.gif?raw=true)](https://github.com/platipusica/jampy-docs-v7-zh-cn/blob/main/_static/builder_animation.gif)


[![Jam.py 演示](https://github.com/platipusica/jampy-docs-v7-zh-cn/blob/main/_static/demo_zh_cn.png?raw=true)](https://northwind.pythonanywhere.com)



一些关于如何设置 Jam.py 和创建应用程序的短视频：

* [使用 Jam.py 框架在 7 分钟内从头到尾创建 CRM Web 数据库应用程序](https://youtu.be/vY6FTdpABa4)
* [使用表单对话框设置 Jam.py 应用程序的界面](https://youtu.be/hvNZ0-a_HHw)

较长的视频：
包含管理后台和复杂内部逻辑的 [视频](https://youtu.be/qkJvGlgoabU)。

PythonAnywhere 上的在线演示（如果显示"即将推出！"，请反馈 issue 以便启动应用程序）：

- [SAP 主题演示](https://jampyapp.pythonanywhere.com)
- [基于 MS Access 模板的个人账户分类账](https://msaccess.pythonanywhere.com)

  以下两个应用程序演示了 Matplotlib、Pandas、NumPy 和 RFM 分析（即最近性、频率和货币价值），直接从 MS Access 模板迁移而来：
  
- [基于 MS Access 模板的 NorthWind Traders V7 DEV（进行中）](https://northwind2.pythonanywhere.com)
- [基于 MS Access 模板的 NorthWind Traders V7（进行中）](https://northwind.pythonanywhere.com)

  
- [包含意大利语和英语翻译的 ERP POC 演示](https://sem.pythonanywhere.com)
- [基于 MS Access 的 Sir Edward Elgar 唱片目录 - 或任何唱片目录](https://elgar.pythonanywhere.com/)
- [资产/零件应用程序（进行中，目前为 Jam V7 演示）](https://jampy.pythonanywhere.com)
- [机器学习（进行中）](https://mlearning.pythonanywhere.com)
- [面向巴西市场的汽车零件销售（葡萄牙语）](https://carparts.pythonanywhere.com)
- [基于 MS Access DB 的资源调配和计费应用程序（进行中）](https://resourcingandbilling.pythonanywhere.com)
- [基于 MS Access DB 的职位跟踪应用程序（进行中）](https://positionstracking.pythonanywhere.com)
- [看板/任务应用程序，V7](https://kanban.pythonanywhere.com)
- [资产库存应用程序，V7（进行中）](https://assetinventory.pythonanywhere.com)
- [Google 身份验证，V7](https://ipam2.pythonanywhere.com)
- [IP 管理 V7（进行中）](https://ipmgmt.pythonanywhere.com)
- [面向巴西市场的集成管理系统 - IMS（葡萄牙语）](https://imsmax.pythonanywhere.com)
- [物料清单，源自 https://github.com/mpkasp/django-bom 作为无代码，V7（进行中）](https://billsofmaterials.pythonanywhere.com)


Jam.py 备用网站：

https://jampyapplicationbuilder.com/

## 主要特性

Jam.py 是一个面向对象、事件驱动的框架，具有层次结构、模块化设计和
非常紧密的 DB/GUI 耦合。Jam.py 的服务器端使用 [Python](https://www.python.org) 编写，
客户端使用 [JavaScript](https://developer.mozilla.org/en/docs/Web/JavaScript)、
[jQuery](https://jquery.com) 和 [Bootstrap](https://getbootstrap.com/docs/5.0/)。

* 简单、清晰且高效的 IDE。开发在应用程序构建器中进行，
  这是一个完全使用 Jam.py 编写的应用程序。

* "全在浏览器中"的框架。使用 Jam.py，您只需要浏览器中的两个页面，
  一个用于项目，另一个用于应用程序构建器。
  在应用程序构建器中更改后，转到项目，刷新页面，
  即可查看结果。

* 支持 SQLite、PostgreSQL、MySQL、Firebird、MSSQL 和
  Oracle 数据库。框架的概念允许您在
  不更改项目的情况下从一种数据库迁移到另一种数据库。

* 身份验证、授权、会话管理、角色和权限。

* 自动化地创建和修改数据库表以及生成 SQL 查询。

* 数据感知控件。

* 开放式框架。您可以使用任何 JavaScript/Python 库。

* 内容丰富、大信息量的报告。基于 [LibreOffice](https://www.libreoffice.org)
  模板的 Band-oriented 报告生成器。

* 图表。您可以使用免费的 [jsCharts](http://www.jscharts.com) 库
  或任何 JavaScript 图表库来创建图表，以展示和分析您的应用程序数据。

* 允许保存用户所做的审计追踪/变更历史记录

* 预定义的 css 主题。

* 本地开发和测试，远程更新。Jam.py 具有导出和导入
  实用程序，允许开发人员将所有元数据（数据库结构、
  项目参数和代码）存储在一个文件中，该文件可以加载到另一个
  应用程序中以应用所有更改。

## 文档

V7 的所有更新文档在线地址为
https://jampy-docs.readthedocs.io/projects/V7/zh-cn/latest

请访问 https://jampy-docs.readthedocs.io/projects/V7/zh-cn/latest/intro/install.html 了解 Python 和
框架的安装，或 https://jampy-docs.readthedocs.io/projects/V7/zh-cn/latest/intro/new_project.html 了解如何创建
新项目。

Jam.py 应用程序设计技巧，请访问 https://jampy-application-design-tips.readthedocs.io/

如需一般讨论、想法或类似内容，请访问邮件组 https://groups.google.com/g/jam-py 或
FB 页面 https://www.facebook.com/groups/jam.py/（目前已暂停）

## 赞助

Jam.py 正在筹集资金，以保持软件对所有人免费，我们需要整个社区的支持才能实现。[在 Github 上赞助 Jam.py](https://github.com/sponsors/platipusica) 以表示您的支持。

## 许可证

Jam.py 使用 BSD 许可证。

## 原作者

Andrew Yushev

另请参阅参与此项目的 [贡献者](http://jam-py.com/contributors.html) 列表。

## 维护者

[crnikaurin](https://github.com/crnikaurin), [platipusica](https://github.com/platipusica)
