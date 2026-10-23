---
title: "فئة Border"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل مظهر الحدود."
type: docs
url: /ar/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

يمثل مظهر الحدود.

نوع Border يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | ينفذ واجهة IClonable. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | لون حد التوقيع. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | نمط حد التوقيع. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | شفافية حد التوقيع، تتراوح من 0.0 (معتم) إلى 1.0 (شفاف)، القيمة الافتراضية 0 (معتم). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | رؤية الحد. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | وزن حد التوقيع. |

### مثال

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
أدلة المهام التي تستخدم `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
