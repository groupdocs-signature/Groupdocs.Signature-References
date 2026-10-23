---
title: "فئة Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند."
type: docs
url: /ar/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.

تعرف على المزيد حول ميزات GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

نوع Signature يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | يُنشئ كائن Signature جديد باستخدام مستند مقدم كتيار. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام تيار المستند وخيارات التحميل. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام مستند مقدم عبر تيار و [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) اختيارية. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام تيار المستند، خيارات التحميل، وإعدادات التوقيع. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام مستند مقدم عبر مسار الملف. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | يُنشئ كائن Signature جديد باستخدام المستند المقدم عبر مسار الملف وخيارات التحميل. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام المستند المقدم عبر مسار ملف و [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) اختيارية. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام مستند مقدم عبر مسار ملف، خيارات التحميل، وإعدادات التوقيع. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | يحذف [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) المحدد من المستند. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | يحذف القائمة المقدمة من التوقيعات من المستند. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | يحذف التوقيعات من النوع المحدد من المستند. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | يحذف التوقيعات من القائمة المحددة لـ `SignatureType` من المستند. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | يحذف توقيعًا باستخدام معرف التوقيع المحدد الخاص به من المستند. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | يحذف التوقيعات المحددة من المستند. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | ينظف الموارد الداخلية المستخدمة بواسطة كائن التوقيع. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | ينشئ معاينة صفحات المستند. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | ينشئ معاينة للتوقيع بناءً على SignOptions المعطاة. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | يبحث عن التوقيعات في مستند باستخدام قائمة من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | يبحث عن التوقيعات في المستند باستخدام خيارات البحث المقدمة ويصفي النتائج بناءً على الشرط المحدد. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | يبحث عن أنواع التوقيع المحددة في المستند بقيمة `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | يبحث عن التوقيعات في المستند باستخدام جميع خيارات البحث المتاحة ويصفي النتائج بناءً على الشرط المحدد. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | يوقع المستند باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | يوقع مستندًا باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | يوقع المستند باستخدام SignOptions ويحفظ النتيجة إلى مسار الملف المحدد. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | يوقع المستند باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | يقوم بتحديث BaseSignature الممررة في المستند. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | يقوم بتحديث التوقيعات الممررة [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) في المستند. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويصفي النتائج بناءً على الشرط المحدد. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | يتحقق من توقيعات المستند باستخدام قائمة من بيانات VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويُفلتر النتائج باستخدام الشرط المحدد. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
دليل المهام الذي يستخدم `Signature`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### انظر أيضًا
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
