---
title: "مستند eSign مع توقيع نصي"
linkTitle: "Text Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تشرح هذه المقالة كيفية توقيع مستند باستخدام توقيع نصي عبر واجهة برمجة تطبيقات GroupDocs.Signature for Python via .NET. تعلّم كيفية إضافة توقيع رقمي إلى ملف PDF برمجياً باستخدام بايثون."
type: docs
url: /ar/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

التوقيع الإلكتروني **Text** هو نص عشوائي يُضاف إلى المستند بطريقة أصلية حسب نوع المستند. توفر GroupDocs.Signature ميزة توقيع النص وتسمح بتخصيص مجموعة واسعة من إعدادات النص - من اسم الخط وحجمه ولونه إلى المحاذاة والحدود وتأثيرات الظل وغيرها. هكذا قد يبدو توقيع النص:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

لنحاول إضافة توقيع نصي إلى ملف PDF برمجياً باستخدام بايثون.

للتعامل مع توقيعات النص برمجياً، توفر [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) الفئة [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) وتكون سير العمل بالكامل سهلة كما يلي:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

يوضح هذا المثال كيفية إضافة توقيع نصي إلى مستند باستخدام بايثون:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء خيارات توقيع النص
        options = TextSignOptions("John Smith")

        # تعيين موضع التوقيع والحجم
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # تعيين لون الخط والنص
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

يمكنك تخصيص توقيع النص أكثر باستخدام خيارات إضافية: المحاذاة والهوامش، نمط الخط، الخلفية، الحد، الدوران والشفافية. عند ضبط المحاذاة، يتم استبدال إحداثي `left` أو `top`، وتقوم `margin` بإزاحة التوقيع عن حافة الصفحة.

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # ضع التوقيع في الزاوية السفلية اليمنى من الصفحة
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # نمط الخط ولون النص
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # الخلفية، الحد، الدوران والشفافية
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # عرض النص كصورة، مما يرسم الحد أيضاً على صفحات PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
هذا الدليل يشرح كيفية إضافة توقيعات نصية إلى المستندات باستخدام [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). يغطي تكوين خصائص النص مثل الخط، اللون، الحجم، والموضع، وتطبيق توقيع النص على مستند. ثم يتم حفظ المستند الموقّع مع توقيع النص المضاف.

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لتوقيع ملفات PDF و Word و Excel و PowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
