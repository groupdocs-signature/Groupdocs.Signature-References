---
title: "Mailmark2D 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "对嵌入 Royal Mail 2D Mailmark 中的文本进行编码和解码。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

对嵌入 Royal Mail 2D Mailmark 中的文本进行编码和解码。

Mailmark2D 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | 使用默认的主数据和次要数据值初始化 Royal Mail Mailmark 组合数据。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | 返回此对象的副本。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | 项目的类别。 |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | 客户使用的可选空间。 |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | DataMatrix 条形码的编码模式。默认值：`DataMatrixEncodeMode.c40`。 |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | 2D Mailmark 类型定义 Data Matrix 条形码的大小。 |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | 该属性保存带有 DPS 的收货地址邮政编码，对于内陆地址，其由区域（1‑2 个字符）、地区（1‑2 个字符）、区段（1 个字符）、单元（2 个字符）和 DPS（2 个字符）组成，必须符合有效的 PAF® 格式，且最大长度为 9 个字符。 |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | 每种产品类型的 Royal Mail Mailmark 条形码负载的标识符。 |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | 供应链 ID 中的唯一项目标识符，需要在每个 Mailmark 条形码上使用，以实现至少 90 天的唯一识别（最大值：99999999）。 |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | 无 DPS 的退回寄件人邮政编码。 |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | 指示请求的退回寄件人服务级别的标志。最大长度为 1。 |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | 参与邮件投递的唯一客户组。 |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | UPU 国家 ID（最大长度：4 个字符）。 |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | 与每个信息类型 ID 相关的条形码版本标识符。 |

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
