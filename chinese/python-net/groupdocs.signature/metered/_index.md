---
title: "Metered 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "管理计量（按使用付费）许可。"
type: docs
url: /zh/python-net/groupdocs.signature/metered/
is_root: false
weight: 40
---


## Metered class

管理计量（按使用付费）许可。

Metered 许可证根据实际消耗计费（通常是页面或
已处理的文档）。在应用启动时一次性设置公私钥对
应用启动时；包装器会将使用情况报告回 GroupDocs
后台的许可证服务器。

Metered 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_consumption_credit](/signature/python-net/groupdocs.signature/metered/get_consumption_credit/) | 返回迄今为止消耗的积分数量。 |
| [get_consumption_quantity](/signature/python-net/groupdocs.signature/metered/get_consumption_quantity/) | 返回迄今为止处理的数据量。 |
| [set_metered_key](/signature/python-net/groupdocs.signature/metered/set_metered_key/#public_key-private_key) | 使用给定的公私钥对激活计量计费。 |

### 另见
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
