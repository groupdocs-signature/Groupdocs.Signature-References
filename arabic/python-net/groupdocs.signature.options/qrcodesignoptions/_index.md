---
title: "فئة QrCodeSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع QR-Code."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

يمثل خيارات توقيع QR-Code.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

يعرض نوع QrCodeSignOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | ينشئ كائنًا جديدًا من فئة QRCodeSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | ينشئ كائنًا من خيارات توقيع رمز الاستجابة السريعة بالنص المحدد. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | ينشئ كائنًا جديدًا من فئة QrCodeSignOptions بالنص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | محاذاة النص في صورة QR-code الناتجة، القيمة الافتراضية هي None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | الكائن المخصص لتسلسله إلى محتوى QR-Code. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | تنفيذ تشفير البيانات المستخدم لتشفير وفك تشفير نص أو بيانات توقيع رمز الاستجابة السريعة. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | نوع QR-Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | لون المقدمة لأشرطة QR code؛ قد يسبب استخدام هذه الخاصية مشاكل في التحقق، لذا استخدمها بحذر. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | ارتفاع منطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات؛ راجع `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | محاذاة QR code الأفقية على صفحة المستند. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | المسافة بين عناصر QR code وحدود الصورة الناتجة. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | الموضع X الأيسر لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص اليسرى والعليا. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | اسم ملف صورة شعار QR-code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | دفق صورة شعار QR-code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | المسافة المحددة افتراضيًا بين حواف الصورة والمستند (تعمل إذا تم تحديد المحاذاة الأفقية أو العمودية). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | نوع قياس الهامش (بكسل، نسب مئوية أو مليمترات). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | العلم لاسترجاع محتوى صورة QR-Code لتوقيع موضع على صفحة المستند. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | نوع الملف لمحتوى الصورة المعاد لتوقيع QR‑Code عندما تكون الخاصية `return_content` مفعلة. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | زاوية الدوران بالدرجات، باتجاه عقارب الساعة. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | الموضع Y العلوي لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). الوحدة معرفة بواسطة الخاصية `LocationMeasureType` من النوع `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | شفافية توقيع QR code. تتراوح القيمة من 0.0 إلى 1.0، مع قيمة افتراضية 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | محاذاة الصورة عمودياً على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | عرض منطقة التوقيع على صفحة المستند بقيم القياس (بكسل، نسبة مئوية، أو مليمترات كما هو معرف في `MeasureType`). |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # مرّر النص ونوع QR code إلى المُنشئ
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # ضع QR code في الزاوية السفلية اليمنى من الصفحة
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # لون الوحدة، الخلفية، وإطار منقط مع بعض المسافة داخله
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
دليل المهام الذي يستخدم `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
