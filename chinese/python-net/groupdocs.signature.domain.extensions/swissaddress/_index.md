---
title: "SwissAddress 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示债权人或债务人的地址。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

表示债权人或债务人的地址。

您可以设置街道、门牌号、邮政编码和城镇（结构化地址类型），或者设置地址行 1 和 2（组合地址元素类型）。

SwissAddress 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | 地址行 1（包含街道名称、门牌号或邮政信箱）是可选的，仅用于组合元素地址。 |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | 地址第2行（包含邮政编码和城镇）在组合元素地址中是必填的。 |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | 两字母 ISO 国家代码。除非整个地址全部为 null 或空值，否则国家代码是必填的。 |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | 门牌号。此字段仅用于结构化地址，可选。 |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | 名称，可为自然人的名和姓，或法人的公司名称。 |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | 邮政编码。此字段仅用于结构化地址。对于此类型，必填。 |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | 地址的街道（不含门牌号）；可选，仅用于结构化地址。 |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | 城镇或城市，仅用于结构化地址，并且在此类型中为必填。 |

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
