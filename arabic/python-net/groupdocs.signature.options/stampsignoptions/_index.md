---
title: "فئة StampSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع الختم."
type: docs
url: /ar/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

يمثل خيارات توقيع الختم.

تعرف على المزيد:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

نوع StampSignOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | يُهيئ نسخة جديدة من فئة StampSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | يُهيئ نسخة جديدة من فئة StampSignOptions بخيارات المحاذاة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | يمسح الموارد الداخلية. (موروث من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | ينشئ مثيلاً جديداً من ImageSignOptions بصورة معرفة مسبقاً من سلسلة Base64. (موروث من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | خلفية الختم. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | نوع قص لون الخلفية للتوقيع. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | نوع قص صورة الخلفية للتوقيع. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | ارتفاع منطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | محاذاة الصورة أفقياً على صفحة المستند. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | قائمة الخطوط الداخلية المعروضة كمجموعة من المستطيلات. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | الموضع الأيسر X لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | نوع القياس (بكسل، نسبة مئوية أو مليمتر) للخصائص اليسرى والعليا. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | المسافة المحددة افتراضيًا بين الصورة وحواف المستند (تعمل إذا تم تحديد محاذاة أفقية أو عمودية). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | نوع قياس الهامش (بكسل، نسب مئوية أو مليمترات). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | قائمة الخطوط الخارجية المعروضة كدوائر متحدة المركز. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | زاوية الدوران باتجاه عقارب الساعة. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | نوع الختم. القيمة الافتراضية هي `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | الموضع العلوي Y لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). راجع `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | شفافية توقيع الختم. تتراوح القيمة من 0.0 إلى 1.0، مع القيمة الافتراضية 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | محاذاة الختم العمودية على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | عرض منطقة التوقيع على صفحة المستند بقيم القياس (بكسل، نسب مئوية أو مليمترات). وحدة القياس معرفة بواسطة `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | سيتم وضع التوقيع على جميع صفحات المستند. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | مظهر التوقيع الإضافي. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | إعدادات الحدود لتوقيع الصورة. (موروثة من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | نوع المستند لخيارات التوقيع (`DocumentType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | امتدادات التوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | خوارزمية التجزئة المستخدمة للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | مسار ملف صورة التوقيع، يُستخدم فقط إذا لم يتم تحديد `image_stream`. (موروثة من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | تدفق صورة التوقيع. إذا تم تحديده، يُستخدم دائمًا بدلاً من ImageFilePath. (موروثة من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | رقم صفحة المستند للتوقيع. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | الخيارات لتحديد الصفحات التي سيتم توقيعها. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | المستطيل الذي يحدد المنطقة لوضع الصورة على المستند. (موروثة من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | موضع الشكل يحدد أين يجب عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروثة من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | نوع التوقيع (`SignatureType`). (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | موضع ترتيب Z لتوقيع النص، الذي يحدد ترتيب عرض التوقيعات المتداخلة. (موروث من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # قم بتكوين خيارات الختم الإضافية حسب الحاجة
    signature.sign(options)
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
