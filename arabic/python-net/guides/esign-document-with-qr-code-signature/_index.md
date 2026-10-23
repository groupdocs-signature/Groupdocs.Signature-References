---
title: "توقيع إلكتروني للمستند باستخدام توقيع رمز QR"
linkTitle: "QR Code Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تشرح هذه المقالة كيفية توقيع المستندات بتوقيع إلكتروني على شكل رمز QR في صفحة المستند باستخدام GroupDocs.Signature للبايثون عبر واجهة .NET API."
type: docs
url: /ar/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

رمز QR (أو Quick Response code) هو نوع من [الباركود](/signature/python-net/guides/esign-document-with-barcode-signature/) ثنائي الأبعاد الذي يتكون من مربعات سوداء مرتبة في شبكة مربعة على خلفية بيضاء. يمكن قراءة رموز QR بواسطة كاميرات الهواتف الذكية أو الأجهزة المتخصصة المخصصة لقراءة QR - الماسحات اليدوية، الأجهزة الطرفية المحمولة، الماسحات المكتبية، الماسحات المدمجة، وما إلى ذلك. عادةً ما تحتوي رموز QR على بيانات تشير إلى موقع ويب أو تطبيق، رسائل بريد إلكتروني، أو أرقام هواتف، معرفات منتجات، أو متعقّبات. لذلك، يمتد نطاق تطبيقات رمز QR من التسويق العام وتحديد العناصر إلى إدارة المستندات.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | رمز أزتيك | رمز DataMatrix | GS1 DataMatrix | رمز GS1 QR | QR |
| --- | --- | --- | --- | --- | --- |
| **التطبيق** | * النقل وتذاكر;<br> * في صناعة الطيران لتذاكر الصعود الإلكترونية;<br> * في السكك الحديدية للتذاكر المباعة عبر الإنترنت والمطبوعة من قبل العملاء أو المعروضة على شاشات الهواتف المحمولة. يتم مسح الرمز ضوئيًا بواسطة ماسح يدوي من قبل موظفي القطار أو عند البوابة للتحقق من صحة التذكرة.<br> * الطب - أساور تعريف المرضى والملصقات للأدوية ذات الاستخدام الواحد وغيرها. | * الوسائط المطبوعة مثل الملصقات والرسائل;<br> * أغراض الهندسة الصناعية - وضع علامات على المكونات وغيرها;<br>  * صناعة الأغذية - لمنع تغليف المنتجات الغذائية وتاريخها بشكل غير صحيح; | مستخدم في<br> * الرعاية الصحية;<br> * الحكومة;<br> * الصناعة.<br> يشفر معلومات إضافية عن العنصر، مثل:<br> * الوزن;<br> * تاريخ الانتهاء;<br> * رقم الدفعة;<br> * تاريخ الصنع;<br> * إلخ. | يُستخدم في التسويق لتشفير معلومات إضافية عن العنصر على العبوة | يُستخدم على نطاق واسع في صناعة السيارات وتطبيقات الهواتف المحمولة. مفيد لتشفير كمية كبيرة من أحرف البيانات وعناوين URL المحددة. |
| **الطول** | 3067 حروف وأرقام,<br> 3832 رقمي,<br> 1914 بايت | 2335 حروف وأرقام,<br> 3116 رقمي | 2335 حروف وأرقام,<br> 3116 رقمي,<br> 1556 بايت | 7089 حروف وأرقام,<br> 4296 رقمي,<br> 2953 بايت | 4296 حروف وأرقام,<br> 7089 رقمي,<br> 2953 بايت |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

عند إضافة توقيع إلكتروني برمز QR إلى مستند، تكون الإعدادات الرئيسية هي النص المراد تشفيره و[نوع رمز QR](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) الذي يجب تحديده عبر فئة [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

فيما يلي الخطوات لتوقيع مستند إلكترونيًا باستخدام توقيع رمز QR:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

المقتطف البرمجي أدناه يوضح كيفية توقيع مستند PDF باستخدام توقيع رمز QR باستخدام بايثون:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء خيارات توقيع رمز QR مع النص المراد تشفيره
        options = QrCodeSignOptions("John Smith")

        # تحديد نوع رمز QR
        options.encode_type = QrCodeTypes.QR

        # تحديد موضع وحجم رمز QR
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو الملف النموذجي المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

أنواع رموز QR الأخرى من الجدول أعلاه يتم ضبطها بنفس الطريقة، على سبيل المثال `QrCodeTypes.AZTEC` أو `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

فيما يلي مثال يوضح كيفية إنشاء توقيع رمز QR أكثر تعقيدًا مع تخصيص إضافي: المحاذاة والهوامش، لون الوحدة، الخلفية والحدود:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
{{< tab "Python" >}}
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
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو الملف النموذجي المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
يوضح هذا الدليل كيفية إضافة توقيعات رموز QR إلى المستندات باستخدام [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). يتضمن خطوات لإنشاء توقيع رمز QR، وتكوين خصائصه مثل الحجم والترميز، وتطبيقه على مستند. يمكن استخدام توقيعات رموز QR للتحقق السريع من المستند الموقّع.

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لإنشاء رموز QR و/أو توقيع ملفاتك باستخدام رموز QR مجانًا، يمكنك استخدام تطبيق الويب [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

لتوقيع ملفات PDF وWord وExcel وPowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات الأخرى عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
