---
title: "فئة Padding"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل معلومات الحشو أو الهامش المرتبطة بالعنصر."
type: docs
url: /ar/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

يمثل معلومات الحشو أو الهامش المرتبطة بالعنصر.

يعرض نوع Padding الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | ينشئ مثيلاً جديداً من فئة Padding بقيم صفرية. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | ينشئ مثيلاً جديداً من فئة Padding باستخدام حجم الحشو المقدم لجميع الحواف. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | ينشئ مثيلاً جديداً من فئة Padding باستخدام أحجام الحشو المقدمة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | يحصل على نسخة من هذا الكائن. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | قيمة الحشو لجميع الحواف. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | قيمة الحشو للحافة السفلية. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | الحشو المدمج للحافتين اليمنى واليسرى. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | قيمة الحشو للحافة اليسرى. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | قيمة الحشو للحافة اليمنى. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | قيمة الحشو للحافة العلوية. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | الحشو المدمج للحافتين العلوية والسفلية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | يوفر كائن Padding بدون أي حشو. |

### مثال

```python
from groupdocs.signature.domain import Padding

# حشو موحد بقيمة 5 وحدات على جميع الجوانب
uniform = Padding(5)

# حشو محدد على اليمين والأسفل
custom = Padding(right=40, bottom=60)
```

### Guides
دلائل المهام التي تستخدم `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
