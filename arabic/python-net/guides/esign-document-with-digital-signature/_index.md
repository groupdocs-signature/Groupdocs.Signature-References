---
title: "توقيع المستند باستخدام التوقيع الرقمي"
linkTitle: "Digital Signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تعرف على فوائد استخدام التوقيعات الرقمية لتوقيع المستندات بأمان. اكتشف كيفية إضافة توقيعات رقمية برمجيًا في بايثون مع تعليمات خطوة بخطوة."
type: docs
url: /ar/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

في عصرنا الرقمي اليوم، ضمان أصالة وسلامة المستندات الإلكترونية أمر حيوي. إحدى الطرق الفعّالة لتحقيق ذلك هي استخدام التوقيعات الرقمية. في هذا الدليل، سنستكشف عالم التوقيعات الرقمية، موضحين ما هي، ولماذا هي ضرورية، وكيف يمكنك الاستفادة من GroupDocs.Signature for Python via .NET لتوقيع مستنداتك إلكترونيًا بسلاسة.

## What is a Digital Signature?

التوقيع الرقمي هو آلية تشفيرية للتحقق من أصالة وسلامة المستندات الإلكترونية. يوفر ضمانًا قويًا بأن المستند نشأ من مرسل معروف ولم يتم العبث به من قبل مصادر غير مصرح لها. عادةً ما يتم تمثيل التوقيعات الرقمية بشهادات تحتوي على مفاتيح خاصة (للتوقيع) وعامة (للتحقق). تُستخدم معايير مختلفة للتشفير بالمفتاح العام، مثل تنسيق PFX، لهذا الغرض.
تظهر الصورة أدناه كيف يبدو التوقيع الرقمي على صفحة مستند PDF بشكل افتراضي.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

يتم رفض الشهادات المنتهية الصلاحية أو غير الصالحة بعد: `sign` يثير [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) برسالة مثل "انتهت صلاحية شهادة التوقيع في ...". لتوقيع باستخدام مثل هذه الشهادة على أي حال، اضبط `allow_expired` أو `allow_not_yet_valid` إلى `True`.

### Follow these steps to sign your documents with a digital signature

1. قم بتثبيت حزمة GroupDocs.Signature باستخدام pip:
```bash
pip install groupdocs-signature-net
```

2. أنشئ نسخة جديدة من الفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) ومرّر مسار المستند المصدر كمعامل للمنشئ.
3. أنشئ كائن [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) باستخدام الشهادة المطلوبة وكلمة مرورها.
4. استدعِ طريقة [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) من نسخة الفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) ومرّر لها كائن [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/).

يوضح المثال أدناه كيفية توقيع مستند PDF باستخدام توقيع إلكتروني رقمي عبر بايثون. يمكننا توقيع أي تنسيق مستند مدعوم آخر بنفس الطريقة.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء خيارات التوقيع الرقمي باستخدام ملف الشهادة
        options = DigitalSignOptions("certificate.pfx")

        # تعيين كلمة مرور الشهادة
        options.password = "1234567890"

        # اختياري: صورة تُظهر التوقيع على الصفحة
        options.image_file_path = "signature.jpg"

        # تعيين موضع التوقيع
        options.left = 100
        options.top = 400

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` هو شهادة العينة المستخدمة في هذا المثال (كلمة المرور `1234567890`). انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) لتنزيلها.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) لتنزيله.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

يمكنك تخصيص التوقيع الرقمي أكثر باستخدام خيارات إضافية: حجم التوقيع على الصفحة، وكذلك معلومات الاتصال والسبب والموقع المخزنة فيه:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
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
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` هو شهادة العينة المستخدمة في هذا المثال (كلمة المرور `1234567890`). انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) لتنزيلها.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) لتنزيله.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

يمكنك أيضًا تحميل الشهادة من تدفق. احتفظ بالتدفق مفتوحًا حتى تُعيد الدالة `sign`.

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # تحميل الشهادة من تدفق
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # تعيين موضع التوقيع والحجم
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` هو شهادة العينة المستخدمة في هذا المثال (كلمة المرور `1234567890`). انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) لتنزيلها.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
يوضح هذا الدليل كيفية استخدام [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) لتوقيع المستندات باستخدام التوقيعات الرقمية. يشرح كيفية تحميل المستندات، وتكوين التوقيعات القائمة على الشهادات، وحفظ الملفات الموقعة بأمان. كما يتم تغطية الميزات المتقدمة، مثل مظهر التوقيع والمعلومات المخزنة في التوقيع. راجع الموارد ذات الصلة للحصول على تفاصيل إضافية حول سير عمل التوقيع الرقمي.

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لتوقيع ملفات PDF و Word و Excel و PowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
