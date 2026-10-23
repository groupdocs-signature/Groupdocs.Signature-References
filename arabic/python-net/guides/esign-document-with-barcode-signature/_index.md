---
title: "التوقيع الإلكتروني للمستند باستخدام توقيع الباركود"
linkTitle: "Barcode Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تشرح هذه المقالة كيفية إضافة توقيع الباركود إلى صفحة المستند مع خيارات متعددة مثل نوع الباركود، نص الباركود، التحديد، المحاذاة وإعدادات بصرية أخرى باستخدام GroupDocs.Signature للبايثون عبر .NET"
type: docs
url: /ar/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

إن **barcode** أو **bar code** هو طريقة لعرض البيانات بصيغة بصرية قابلة للقراءة آليًا. بشكل عام، الباركود هو صورة ذات شكل مستطيل يتكون من خطوط سوداء متوازية ومسافات بيضاء بعروض مختلفة.
تُستخدم الباركودات في مجالات مختلفة حيث تكون التعرف السريع ضروريًا - كجزء من عملية الشراء في المتاجر، وفي المستودعات لتتبع المخزون، وعلى الفواتير للمساعدة في المحاسبة، وغيرها من الاستخدامات المتعددة.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

تسمح الباركودات بتخزين بيانات متعلقة بالمنتج مثل تواريخ التصنيع والانتهاء، اسم الشركة المصنعة، بلد المنشأ، وسعر المنتج. هناك العديد من أنواع الباركود اليوم لأن الشركات المختلفة تستخدم تركيبات مختلفة من الأرقام والشرطيات في باركوداتها وفقًا لاحتياجاتها. من منظور توقيع المستند، قد يحتوي الباركود على أحرف مختلفة (حروف، أرقام، أو رموز) وقد يكون له أطوال وأحجام متنوعة حسب النوع والإعدادات للحفاظ على معلومات التوقيع، العنوان، الموضوع، أو بيانات مشفرة قصيرة.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
لتحديد خيارات مختلفة لتوقيع الباركود، يوفر GroupDocs.Signature للبايثون عبر .NET الفئة [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). الحقول الرئيسية هي:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

فيما يلي خطوات التوقيع الإلكتروني للمستند باستخدام توقيع الباركود عبر GroupDocs.Signature للبايثون عبر .NET API:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

يوضح هذا المثال كيفية توقيع مستند PDF باستخدام توقيع الباركود عبر بايثون:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء خيارات توقيع الباركود مع النص المراد ترميزه
        options = BarcodeSignOptions("John Smith")

        # تحديد نوع الباركود
        options.encode_type = BarcodeTypes.CODE128

        # تحديد موضع الباركود وحجمه
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

يمكنك تخصيص توقيع الباركود أكثر باستخدام خيارات إضافية: المحاذاة والهوامش، لون الخط، موضع النص المشفر، الهوامش الداخلية، الخلفية، الحدود والشفافية:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # مرّر النص ونوع الباركود إلى المُنشئ
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # ضع الباركود في الزاوية السفلية اليمنى للصفحة
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # لون الخط، النص المشفر أسفل الخطوط، المسافة داخل الحدود
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # الخلفية، الحدود والشفافية
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

يدعم GroupDocs.Signature أنواعًا متعددة من الباركود. كل نوع يقبل مجموعة خاصة من الأحرف والأطوال، لذا اختر النص المناسب للنوع. يوقع هذا المثال مستندًا بأربعة باركودات من أنواع مختلفة في استدعاء واحد:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # كائن خيار توقيع واحد لكل باركود، يُوضع أحدًا تحت الآخر
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
هذا الدليل يوضح كيفية استخدام [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) لإضافة توقيعات تعتمد على الباركود إلى المستندات. يغطي إنشاء وتكوين وتطبيق توقيعات الباركود مع دعم لأنواع مختلفة من الباركود وخيارات التخصيص. للمزيد من الاستكشاف، راجع الأدلة ذات الصلة بمعلومات المستند وتقنيات التوقيع المتقدمة.

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لإنشاء باركودات و/أو توقيع ملفاتك بالباركود مجانًا، يمكنك استخدام التطبيق عبر الإنترنت [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

لتوقيع ملفات PDF وWord وExcel وPowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات الأخرى عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
