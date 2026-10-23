---
title: "فئة DigitalSignOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات التوقيع الرقمي."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

يمثل خيارات التوقيع الرقمي.

اعرف المزيد

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

نوع DigitalSignOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | ينشئ مثيلاً جديداً من فئة DigitalSignOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | ينشئ مثيلاً جديداً من DigitalSignOptions بملف شهادة. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | ينشئ مثيلاً جديداً من فئة DigitalSignOptions بملف شهادة وملف صورة مظهر. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | ينشئ مثيلاً جديداً من DigitalSignOptions بملف شهادة وتدفق صورة مظهر. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة وملف صورة مظهر. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة وتدفق صورة مظهر. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | يمسح الموارد الداخلية. (موروث من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | ينشئ مثيلاً جديداً من ImageSignOptions بصورة معرفة مسبقاً من سلسلة Base64. (موروث من [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | العلم الذي يسمح بالتوقيع باستخدام شهادة انتهت فترة صلاحيتها. القيمة الافتراضية هي False؛ التوقيع بشهادة منتهية الصلاحية يثير `GroupDocsSignatureException` ولا يتم توقيع المستند. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | العلم الذي يسمح بالتوقيع باستخدام شهادة لم يبدأ بعد فترة صلاحيتها. القيمة الافتراضية هي False؛ التوقيع بهذه الشهادة يثير `GroupDocsSignatureException` ولا يتم توقيع المستند. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | مسار ملف الشهادة الرقمية. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | تدفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية فسيتم دائمًا استخدامها بدلاً من CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | جهة الاتصال الخاصة بالتوقيع. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | دالة تجزئة التوقيع المخصصة المستخدمة لتوقيع المستند، مما يتيح للمستخدمين تنفيذ منطق التوقيع الرقمي الخاص بهم. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | ارتفاع منطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسبة مئوية، أو مليمتر؛ انظر `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | محاذاة الصورة أفقياً على صفحة المستند. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | الموضع X الأيسر لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسبة مئوية، أو مليمتر كما هو معرف في `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | موقع التوقيع. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | نوع القياس (بكسل، نسبة مئوية أو مليمتر) للخصائص اليسرى والعليا. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | المسافة التي يتم تحديدها افتراضيًا بين الصورة وحواف المستند (تنطبق عندما يتم تحديد المحاذاة الأفقية أو العمودية). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | نوع قياس الهامش (بكسل، نسب مئوية أو مليمترات). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | كلمة مرور الشهادة الرقمية. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | سبب التوقيع. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | زاوية الدوران باتجاه عقارب الساعة. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | خصائص التوقيع الرقمي للمستند. لتوقيع PDF، يمكن تعيين الخصائص المتقدمة باستخدام كائن [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | نوع القياس (بكسل، نسب مئوية أو مليمترات) لخصائص Width و Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | وضع التمدد على صفحة المستند. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | الموضع Y العلوي لمنطقة التوقيع على صفحة المستند بوحدات القياس (بكسل، نسبة مئوية، أو مليمتر؛ انظر `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | شفافية التوقيع الرقمي، تتراوح بين 0.0 إلى 1.0. القيمة الافتراضية هي 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | علامة التحقق LTV (التحقق طويل الأمد). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | محاذاة الصورة عمودياً على صفحة المستند. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | رؤية التوقيع. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | عرض منطقة التوقيع على صفحة المستند بقيم القياس (بكسل، نسبة مئوية، أو مليمتر). وحدة القياس معرفة بواسطة `MeasureType` عبر خاصية SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | نوع XAdES. القيمة الافتراضية هي None (XAdES غير مفعل). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # مرّر الشهادة وصورة المظهر إلى المُنشئ
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # اعرض التوقيع على الصفحة، في هذا الموضع والحجم
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # المعلومات المخزنة في التوقيع
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
أدلة المهام التي تستخدم `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
