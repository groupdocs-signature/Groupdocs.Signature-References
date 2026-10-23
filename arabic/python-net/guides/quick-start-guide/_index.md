---
title: "دليل البدء السريع"
linkTitle: "Quick Start Guide"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "قم بإعداد بيئة افتراضية، وثبّت groupdocs-signature-net، وشغّل ثلاثة أمثلة بسيطة: توقيع ملف PDF بتوقيع نصي، البحث عنه عن التوقيعات، والتحقق منها."
type: docs
url: /ar/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


يقدم هذا الدليل نظرة سريعة على كيفية إعداد والبدء في استخدام GroupDocs.Signature for Python via .NET. تضيف المكتبة وتبحث وتتحقق وتحدّث وتزيل التوقيعات الإلكترونية في ملفات PDF وWord وExcel وPowerPoint وOpenDocument والملفات الصورة ببضع أسطر من الشيفرة.

## Prerequisites

للمتابعة، تأكد من أن لديك:

1. بيئة مُكوَّنة كما هو موضح في موضوع [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). على نظامي Linux وmacOS يتضمن ذلك بعض حزم النظام.
2. اختياريًا، [Temporary License](https://purchase.groupdocs.com/temporary-license/) لاختبار جميع ميزات المنتج. بدون ترخيص، تعمل المكتبة في وضع التقييم: تعالج المستندات حتى صفحتين وتضيف سطر تقييم إلى كل صفحة تُوقّع. راجع [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

لأفضل الممارسات، استخدم بيئة افتراضية لإدارة التبعيات. تعرف على المزيد في دليل [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

أنشئ بيئة افتراضية:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

فعّلها:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

انظر [Installation](/signature/python-net/guides/installation/) لتحديد نسخة معينة وللتثبيت دون الوصول إلى PyPI.

## Example 1: Sign a PDF with a Text Signature

افتح مستندًا، وصف التوقيع باستخدام [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/)، واحفظ النسخة الموقّعة.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # افتح المستند؛ الـwith‑block يحرر الملف عند انتهائه
    with Signature("sample.pdf") as signature:
        # توقيع نصي على بعد 100 بكسل من الحافة اليسرى والعلوية للصفحة الأولى
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # وقّع واحفظ النتيجة في ملف جديد؛ يبقى المصدر دون تغيير
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

ابحث عن التوقيعات التي يحملها المستند بالفعل. `search` يأخذ قائمة من خيارات البحث، واحدة لكل نوع توقيع للبحث عنه، ويعيدها في `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # ابحث عن توقيعات نصية في كل صفحة
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

تحقق من أن المستند يحمل التوقيع الذي تتوقعه. تنجح عملية التحقق عندما يتم العثور على توقيع نصي يحتوي على هذا النص بالضبط.

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

احفظ كل مثال في ملف `.py` خاص به بجوار ملفات العينة. يجب أن يبدو مجلدك مشابهًا لهذا:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

شغّل مثالًا من ذلك المجلد:

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

عند الانتهاء، قم بإلغاء تنشيط البيئة الافتراضية عن طريق تشغيل `deactivate` أو إغلاق الصدفة الخاصة بك.

## Apply a License

عيّن متغيّر البيئة `GROUPDOCS_LIC_PATH` إلى المسار الكامل لملف الترخيص الخاص بك، وسيتم تطبيق الترخيص تلقائيًا عند استيراد `groupdocs.signature`. لا يلزم أي شفرة. بدلاً من ذلك، طبّق الترخيص في الشفرة مرة واحدة، قبل أي استدعاء آخر:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

الموضوع [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) يغطي الطريقتين والترخيص القائم على القياس.

## Next Steps

بعد إكمال الأساسيات، استكشف الموارد الإضافية:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
