---
title: "مستند eSign مع توقيع صورة"
linkTitle: "Image Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "توضح هذه المقالة كيفية إضافة صورة توقيع على صفحة المستند باستخدام GroupDocs.Signature للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

إن **image** كالتوقيع هو طريقة بديلة لوضع أي بيانات عرضية في شكل بصري. يسمح هذا النوع من التوقيع الإلكتروني بإنشاء صور مخصصة بشعار الشركة، أحرف المرسل، الأسماء وما إلى ذلك.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

فيما يلي الخطوات لإنشاء توقيع صورة على صفحة المستند:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

يوضح هذا المثال كيفية توقيع مستند PDF باستخدام توقيع الصورة عبر بايثون:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
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

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) لتنزيله.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

يمكنك تخصيص توقيع الصورة أكثر باستخدام خيارات إضافية: المحاذاة والهوامش، الدوران، الشفافية وإطار. عندما يتم تعيين محاذاة، فإنها تستبدل إحداثي `left` أو `top`، وتقوم `margin` بإزاحة التوقيع عن حافة الصفحة.

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # ضع التوقيع في الزاوية السفلية اليمنى من الصفحة
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # دوّر الصورة واجعلها شفافة بنسبة 20%
        options.rotation_angle = 10
        options.transparency = 0.2

        # ارسم إطارًا متقطعًا حول الصورة
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) لتنزيله.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

يمكنك أيضًا تحميل صورة التوقيع من تدفق. حافظ على بقاء التدفق مفتوحًا حتى تُعيد الدالة `sign`:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # تحميل صورة التوقيع من تدفق
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) لتنزيله.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
يوضح هذا الدليل كيفية استخدام [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) لإضافة توقيعات قائمة على الصورة إلى المستندات. يغطي تحميل المستند، وتكوين خصائص توقيع الصورة (مثل الحجم، الموضع، والشفافية)، وحفظ المستند الموقّع. كما يتم مناقشة خيارات التخصيص المتقدمة، مثل تعديل مظهر الصورة ومحاذاة التوقيع. للحصول على مزيد من المعلومات، استكشف موارد توقيع المستندات ذات الصلة.

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لإنشاء توقيعات صورة و/أو توقيع ملفاتك بها مجانًا، يمكنك استخدام التطبيق عبر الإنترنت [Generate Image](https://products.groupdocs.app/signature/generate/image).

لتوقيع ملفات PDF وWord وExcel وPowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات الأخرى عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
