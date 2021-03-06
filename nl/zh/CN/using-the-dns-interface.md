---
copyright:
  years: 1994, 2017
lastupdated: "2017-11-29"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 如何使用 DNS 界面

执行以下步骤，以通过 IBM Cloud 客户门户网站使用 DNS 界面：

* 浏览至[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/)。
* 选择**网络 -> DNS -> 转发区域**
* 选择要管理的域，或选择页面右侧的**添加 DNS 区域**按钮。

## DNS 界面概述
通过在客户门户网站上使用“DNS 界面”，您将具有完整功能来管理 DNS 的所有方面。在界面的任何屏幕中，使用屏幕顶部的静态菜单栏，可以执行每种类型的 DNS 管理。

## 管理 DNS
访问门户网站中的 DNS 界面时，会将您直接路由到**管理 DNS** 屏幕，该屏幕支持您查看、编辑或删除与帐户关联的任何现有主 DNS。

* 要添加新记录，只需填写**添加新记录**下提供的字段，然后单击**添加记录**按钮即可。
* 要修改现有记录，请单击包含该记录的行，随后该行将转换为**编辑**方式。将设置更改为所需的值，然后单击**更新**。
* 要删除记录，请选择该记录右侧的红色圆圈，然后在提示时单击**是**。

## 辅助 DNS

* 浏览至[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/)。
* 选择**网络 -> DNS -> 辅助区域**

在此屏幕中，可以添加或修改辅助 DNS 设置。

* 要添加新记录，请选择**添加区域**，填写字段，然后选择**添加**。
* 要除去辅助 DNS 记录，或将其转换为主记录，请使用页面右侧的**操作**下拉列表，然后选择相应的选项。

## 逆向 DNS

执行以下步骤，以通过门户网站导航来使用 DNS 界面：

* 浏览至[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/)。
* 选择**网络 -> DNS -> 逆向记录**
* 在下拉菜单中，选择或输入要更改其逆向 DNS 的 IP 地址，然后选择**查看 IP**
  * 要添加记录，请输入要用于逆向 DNS 条目的主机名。
  * 为记录设置 TTL（生存时间）。
  * 一旦确定了信息，请选择**保存**。

可以通过单击页面右侧的**编辑此子网中所有 IP 的 RDNS** 来修改整个子网。

* 在此页面中，选择要更新的 IP 所在的行。
* 在各字段中输入信息，然后选择**更新**。“注释”字段是可选的。

## 传播检查

* 浏览至[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/)。
* 选择**网络 -> 工具**。

在装入的页面上，可以从多个工具中进行选择；要检查域名在 DNS 服务器中的传播情况，请使用底部选项。

* 在各字段中输入相应的信息，然后选择**检查 DNS**。
* 片刻之后，右侧的框将使用域的当前 DNS 信息进行更新。
