---
title: "فئة FormFieldSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع FormField لمستندات PDF."
type: docs
url: /ar/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

يمثل خيارات توقيع FormField لمستندات PDF.

يوفر خيارات لإنشاء أو تحديث توقيعات حقول النماذج في ملفات PDF.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

نوع FormFieldSignOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | ينشئ مثيلاً جديداً من فئة PdfFormFieldSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | ينشئ مثيلاً جديداً من فئة PdfFormFieldSignOptions بتوقيع FormField. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | ارتفاع منطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات؛ راجع `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | محاذاة الصورة أفقياً على صفحة المستند. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | الموضع X الأيسر لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Left و Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | المسافة الافتراضية بين الصورة وحواف المستند (تطبق عندما يتم تعيين المحاذاة الأفقية أو العمودية). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | نوع قياس الهوامش (بكسل، نسب مئوية، أو مليمترات). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | زاوية الدوران، مقاسة باتجاه عقارب الساعة. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | حقل FormField للتوقيع. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | الموضع العلوي Y لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType` لنوع قياس الموقع. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | شفافية توقيع حقل النموذج. تتراوح القيمة من 0.0 إلى 1.0، مع القيمة الافتراضية 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | محاذاة الصورة عمودياً على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | عرض منطقة التوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية، أو مليمترات؛ راجع `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | سيتم وضع التوقيع على جميع صفحات المستند. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | مظهر التوقيع الإضافي. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | إعدادات خلفية التوقيع. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | إعدادات الحدود. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | نوع المستند لخيارات التوقيع (`DocumentType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | امتدادات التوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | خط التوقيع. (موروثة من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | لون المقدمة للتوقيع. (موروث من [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
