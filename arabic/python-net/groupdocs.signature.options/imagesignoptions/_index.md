---
title: "فئة ImageSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات توقيع الصورة."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

يمثل خيارات توقيع الصورة.

تعرف على المزيد:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

نوع ImageSignOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | ينشئ مثيلاً جديدًا من فئة ImageSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | ينشئ ImageSignOptions بملف صورة. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | ينشئ مثيلاً جديدًا من ImageSignOptions باستخدام تدفق صورة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | يمسح الموارد الداخلية. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | ينشئ مثيلاً جديدًا من ImageSignOptions بصورة معرفة مسبقًا من سلسلة Base64. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | إعدادات الحدود لتوقيع الصورة. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | ارتفاع التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات؛ راجع `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | محاذاة التوقيع الأفقية على صفحة المستند. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | مسار ملف صورة التوقيع، يُستخدم فقط إذا لم يتم تحديد `image_stream`. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | دفق صورة التوقيع. إذا تم تحديده، يُستخدم دائمًا بدلاً من ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | الموضع X الأيسر للتوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات). يعمل إذا لم يتم تحديد المحاذاة الأفقية. راجع `MeasureType` لنوع قياس الموقع. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص اليسرى والعليا. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | المسافة بين التوقيع وحواف المستند. يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) للهامش. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | المستطيل الذي يحدد المنطقة لوضع الصورة على المستند. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | موقع الشكل يحدد أين يجب عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | الموضع Y العلوي للتوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات) كما هو معرف بواسطة `MeasureType` LocationMeasureType. يعمل إذا لم يتم تحديد المحاذاة العمودية. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | شفافية التوقيع، تتراوح من 0.0 (معتم) إلى 1.0 (شفاف)، القيمة الافتراضية هي 0 (معتم). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | المحاذاة العمودية للتوقيع على صفحة المستند. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | عرض التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية، أو مليمترات `MeasureType` نوع قياس الحجم). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء خيارات توقيع الصورة باستخدام ملف الصورة
        options = ImageSignOptions("signature.jpg")
        # تعيين موضع التوقيع والحجم
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
أدلة المهام التي تستخدم `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
