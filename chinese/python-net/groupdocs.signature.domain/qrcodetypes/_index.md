---
title: "QrCodeTypes 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "QR 码类型容器。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

QR 码类型容器。

QrCodeTypes 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | 解析 QR 码类型名称并返回相应的 QRCodeType 实例。 |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | 返回与给定解析类型名称匹配的 QRCode 类型，如果名称未知则返回 None。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | 所有 QRCode 类型。 |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Aztec QR-Code 类型对象。 |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | DataMatrix QR-Code 类型对象。 |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | QR QR-Code 类型对象。 |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | GS1 DataMatrix QR-Code 类型对象。 |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | GS1 QR-Code 类型对象。 |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | HIBC LIC QR-Code Type 对象。 |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | HIBC LIC Data Matrix QR-Code Type 对象。 |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | HIBC LIC Aztec QR-Code Type 对象。 |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | HIBC PAS QR-Code Type 对象。 |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | HIBC PAS Data Matrix QR-Code Type 对象。 |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | HIBC PAS Aztec QR-Code Type 对象。 |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Han Xin QR-Code Type 对象。 |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | GS1 Han Xin QR-Code Type 对象。 |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | RectMicroQR Type 对象。 |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | MicroQR Type 对象。 |

### 示例

```python
from groupdocs.signature.domain import QrCodeTypes

# 在创建签名选项时使用 QR code type 枚举
print(QrCodeTypes.QR)
```

### Guides
使用 `QrCodeTypes` 的任务指南：

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
