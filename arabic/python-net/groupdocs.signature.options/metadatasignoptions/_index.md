---
title: "فئة MetadataSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع البيانات الوصفية."
type: docs
url: /ar/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

يمثل خيارات توقيع البيانات الوصفية.

اعرف المزيد

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

نوع MetadataSignOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | يُنشئ مثيلاً جديدًا من فئة MetadataSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | يُنشئ مثيلاً جديدًا من [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) مع البيانات الوصفية. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | إضافة مثيل MetadataSignature موجود إلى المجموعة. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | ينشئ ImageMetadataSignature جديدًا بالمعلمات المحددة ويضيفه إلى المجموعة. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | ينشئ PdfMetadataSignature جديدًا بالمعلمات المحددة ويضيفه إلى المجموعة. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | تنفيذ [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) المستخدم لتشفير جميع توقيعات البيانات الوصفية في مجموعة الخيارات هذه. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | توقيعات البيانات الوصفية المرتبطة بالتوقيع. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | سيتم وضع التوقيع على جميع صفحات المستند. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | مظهر التوقيع الإضافي. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | نوع المستند لخيارات التوقيع (`DocumentType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | امتدادات التوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | خوارزمية التجزئة المستخدمة للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | رقم صفحة المستند للتوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | الخيارات لتحديد الصفحات التي سيتم توقيعها. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | نوع التوقيع (`SignatureType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | موضع ترتيب Z لتوقيع النص، الذي يحدد ترتيب عرض التوقيعات المتداخلة. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### مثال

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
