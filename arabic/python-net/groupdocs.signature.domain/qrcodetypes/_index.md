---
title: "فئة QrCodeTypes"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "حاوية أنواع رمز QR."
type: docs
url: /ar/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

حاوية أنواع رمز QR.

يعرض نوع QrCodeTypes الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | يقوم بتحليل اسم نوع رمز QR ويعيد المثيل المقابل من QRCodeType. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | يعيد نوع QRCode المطابق لاسم نوع التحليل المعطى، أو None إذا كان الاسم غير معروف. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | جميع أنواع QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | كائن نوع Aztec QR-Code. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | كائن نوع DataMatrix QR-Code. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | كائن نوع QR QR-Code. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | كائن نوع GS1 DataMatrix QR-Code. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | كائن نوع GS1 QR-Code. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | كائن نوع HIBC LIC QR-Code. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | كائن نوع HIBC LIC Data Matrix QR-Code. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | كائن نوع HIBC LIC Aztec QR-Code. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | كائن نوع HIBC PAS QR-Code. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | كائن نوع HIBC PAS Data Matrix QR-Code. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | كائن نوع HIBC PAS Aztec QR-Code. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | كائن نوع Han Xin QR-Code. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | كائن نوع GS1 Han Xin QR-Code. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | كائن نوع RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | كائن نوع MicroQR. |

### مثال

```python
from groupdocs.signature.domain import QrCodeTypes

# استخدم تعداد نوع رمز QR عند إنشاء خيارات التوقيع
print(QrCodeTypes.QR)
```

### Guides
دليل المهام الذي يستخدم `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
