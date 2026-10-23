---
title: "فئة TextSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع النص."
type: docs
url: /ar/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

يمثل خيارات توقيع النص.

اعرف المزيد

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

نوع TextSignOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | ينشئ مثيلاً جديدًا من فئة TextSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | ينشئ مثيلاً جديدًا من فئة TextSignOptions بالنص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | إعدادات خلفية التوقيع. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | إعدادات الحدود. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | خط التوقيع. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | لون المقدمة للتوقيع. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | عنوان حقل النموذج النصي لوضع توقيع النص فيه. يمكن استخدامه فقط عندما تكون الخاصية `signature_implementation` مُعينة إلى `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | The نوع حقل النموذج الذي يتم وضع توقيع النص فيه. هذه الخاصية تنطبق فقط عندما يتم تعيين `signature_implementation` إلى `TextSignatureImplementation.FORM_FIELD` (أي TextToFormField). القيمة الافتراضية هي `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | ارتفاع التوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية، أو مليمترات). الوحدة تحددها الخاصية `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | محاذاة التوقيع الأفقية على صفحة المستند. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | الموضع X الأيسر للتوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية، أو مليمترات كما هو معرف في الخاصية `MeasureType` LocationMeasureType). يعمل إذا لم يتم تحديد المحاذاة الأفقية. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص `left` و `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | المسافة بين التوقيع وحواف المستند. تُطبق فقط عندما يتم تحديد المحاذاة الأفقية أو العمودية. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للهامش. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | الخاصية الأصلية. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | موقع الشكل يحدد أين يجب عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | نوع الشكل لوضع النص. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | معرّف فريد للتوقيع، يمكن استخدامه في خيارات التحقق ومدعوم فقط للمستندات PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | نوع تنفيذ توقيع النص. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | نص التوقيع. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | المحاذاة الأفقية للنص داخل التوقيع، مدعومة فقط لتنفيذات توقيع الصورة والتعليق (انظر الخاصية `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | محاذاة النص رأسياً داخل التوقيع. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | الموضع Y العلوي للتوقيع على صفحة المستند، معبرًا عنه بوحدات القياس (بكسل، نسبة مئوية، أو مليمترات). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | شفافية التوقيع، قيمة عائمة بين 0.0 (معتم) و 1.0 (شفاف). القيمة الافتراضية هي 0.0 (معتم). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | المحاذاة العمودية للتوقيع على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | عرض التوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية، أو مليمترات؛ انظر الخاصيتين `MeasureType` و `SizeMeasureType`). |
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
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
دليل المهام الذي يستخدم `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
