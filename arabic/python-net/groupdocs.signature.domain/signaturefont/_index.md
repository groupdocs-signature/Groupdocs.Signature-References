---
title: "فئة SignatureFont"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تحدد فئة SignatureFont خصائص الخط لتوقيع نصي."
type: docs
url: /ar/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

تحدد فئة SignatureFont خصائص الخط لتوقيع نصي.

يعرض نوع SignatureFont الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | يقوم بتهيئة SignatureFont بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | نمط الخط العريض. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | اسم عائلة الخط. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | نمط الخط المائل. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | حجم الخط. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | نمط الخط المشطوب. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | نمط الخط المسطر. |

### مثال

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
أدلة المهام التي تستخدم `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
