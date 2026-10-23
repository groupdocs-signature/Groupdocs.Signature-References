---
title: "SignatureSettings 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示用于自定义 Signature 行为的设置。"
type: docs
url: /zh/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

表示用于自定义[`Signature`](/signature/python-net/groupdocs.signature/signature/)行为的设置。

SignatureSettings 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | 使用默认值初始化默认的 SignatureSettings 实例。 |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | 使用 Logger 实现初始化默认的 SignatureSettings 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | 文档处理期间使用的默认区域性。默认值为 "en-US"。 |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | 指示是否在元数据列表中包含标准文档元数据签名（如作者、所有者、创建日期和修改日期）的标志。 |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | 决定哪些类型的消息会传递给 [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) 的日志级别标志。 |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | 用于记录（错误、警告、跟踪）的日志实现。 [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/)。 |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | 决定当 Delete 方法没有受影响的签名可删除时，是否重新保存源文档的标志。 |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | 决定当 `Update` 方法没有签名可更新时，是否重新保存源文档的标志。 |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | 决定是否在文档信息结果中包含已删除的签名的标志。每个 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) 都有一个 `Deleted` 标志来指示它是否已被删除。 |

### 另见
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
