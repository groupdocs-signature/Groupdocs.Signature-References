---
title: "فئة BarcodeSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع الباركود."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

يمثل خيارات توقيع الباركود.

اعرف المزيد

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

نوع BarcodeSignOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالنص. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | ينشئ مثيلاً جديدًا من فئة BarcodeSignOptions بالنص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | محاذاة النص في صورة الباركود الناتجة. القيمة الافتراضية هي None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | نوع الباركود. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | لون المقدمة لأشرطة الباركود؛ قد يسبب استخدامه مشاكل في التحقق، لذا استخدمه بحذر. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | ارتفاع منطقة التوقيع على صفحة المستند بوحدات قياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType` لنوع قياس الحجم. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | محاذاة الصورة أفقياً على صفحة المستند. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | المسافة بين عناصر الباركود وحدود الصورة الناتجة. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | الموضع X الأيسر لمنطقة التوقيع على صفحة المستند، معبرًا عنه بوحدات قياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص اليسرى والعليا. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | المسافة المحددة افتراضياً بين الصورة وحواف المستند (تطبق عندما يتم ضبط المحاذاة الأفقية أو العمودية). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | نوع قياس الهامش (بكسل، نسب مئوية أو مليمترات). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | العلم الذي يشير إلى ما إذا كان يجب استرجاع محتوى صورة الباركود لتوقيع موضع على صفحة المستند. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون الخاصية `return_content` مفعلة. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | زاوية الدوران باتجاه عقارب الساعة. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | الموضع Y العلوي لمنطقة التوقيع على صفحة المستند بوحدات قياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | شفافية توقيع الباركود، تتراوح من 0.0 (معتم بالكامل) إلى 1.0 (شفاف بالكامل)؛ القيمة الافتراضية هي 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | المحاذاة العمودية لصورة الباركود على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | عرض منطقة التوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية، أو مليمترات) كما هو معرف في `MeasureType`. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | سيتم وضع التوقيع على جميع صفحات المستند. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | مظهر التوقيع الإضافي. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | إعدادات خلفية التوقيع. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | إعدادات الحدود. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | نوع المستند لخيارات التوقيع (`DocumentType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | امتدادات التوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | خط التوقيع. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | عنوان حقل النموذج النصي لوضع توقيع النص فيه. يمكن استخدامه فقط عندما تكون الخاصية `signature_implementation` مضبوطة على `TextSignatureImplementation.FORM_FIELD`. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | نوع حقل النموذج لوضع توقيع النص فيه. هذه الخاصية تنطبق فقط عندما تكون الخاصية `signature_implementation` مضبوطة على `TextSignatureImplementation.FORM_FIELD` (أي TextToFormField). القيمة الافتراضية هي `FormTextFieldType.ALL_TEXT_TYPES`. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | خوارزمية التجزئة المستخدمة للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | الخاصية الأصلية. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | رقم صفحة المستند للتوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | الخيارات لتحديد الصفحات التي سيتم توقيعها. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | موضع الشكل يحدد أين يجب عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | نوع الشكل لوضع النص. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | معرف التوقيع الفريد، قابل للاستخدام في خيارات التحقق ومدعوم فقط لمستندات PDF. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | نوع تنفيذ توقيع النص. (موروث من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | نوع التوقيع (`SignatureType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | نص التوقيع. (موروث من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | محاذاة النص أفقياً داخل التوقيع، مدعومة فقط لتطبيقات توقيع الصورة والتعليق التوضيحي (انظر خاصية `TextSignatureImplementation` SignatureImplementation). (موروث من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | محاذاة النص عمودياً داخل التوقيع. (موروث من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | موضع ترتيب Z لتوقيع النص، الذي يحدد ترتيب عرض التوقيعات المتداخلة. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
أدلة المهام التي تستخدم `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
