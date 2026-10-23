---
title: "البحث عن التوقيعات الإلكترونية النصية"
linkTitle: "Texts"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يوضح هذا الموضوع كيفية البحث عن توقيعات إلكترونية نصية داخل صفحات المستند باستخدام GroupDocs.Signature للـPython عبر واجهة برمجة تطبيقات .NET."
type: docs
url: /ar/python-net/guides/search-for-text-e-signatures/
is_root: false
weight: 90
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) class to specify different options for searching Text electronic signatures within documents.

فيما يلي الخطوات للبحث عن توقيعات إلكترونية نصية باستخدام واجهة برمجة تطبيقات GroupDocs.Signature:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) object according to your requirements and specify additional search options (if needed).
* Call the [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass a list with the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) to it. The `signatures` property of the returned [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult) holds the found [TextSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignature) objects.

يوضح هذا المثال كيفية البحث عن توقيعات إلكترونية نصية في مستند باستخدام Python. الخاصية `signature_implementation` لكل توقيع توضح كيف تم إضافته إلى المستند: كمحتوى صفحة (`NATIVE`)، أو تعليق، أو حقل نموذج، وما إلى ذلك.

{{< tabs "search_text" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_text():
    with Signature("signed.pdf") as signature:
        result = signature.search([TextSearchOptions()])

        print(f"Found {len(result.signatures)} text signature(s)")
        for text_signature in result.signatures:
            print(f"{text_signature.signature_implementation.name} text signature '{text_signature.text}' "
                  f"on page {text_signature.page_number} at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"search-text.txt\" >}}
```text
Found 3 text signature(s)
ANNOTATION text signature 'Approved' on page 1 at (50, 480), size 90x22
FORM_FIELD text signature 'John Smith' on page 1 at (50, 530), size 190x22
NATIVE text signature 'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text/search-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Advanced Search Options

فيما يلي مثال يوضح كيفية استخدام خيارات البحث المتقدمة: صفحة للبحث، النص للمطابقة مع [TextMatchType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textmatchtype)، و[TextSignatureImplementation](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) للبحث عنه.

{{< tabs \"search_text_with_filters\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

def search_text_with_filters():
    with Signature("signed.pdf") as signature:
        options = TextSearchOptions()
        # ابحث عن الصفحة الأولى فقط (تبدأ أرقام الصفحات من 1)
        options.all_pages = False
        options.page_number = 1
        # إرجاع توقيعات النص فقط التي تحتوي على \"John\"...
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS
        # ...وهي جزء من محتوى الصفحة
        options.signature_implementation = TextSignatureImplementation.NATIVE

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching text signature(s)")
        for text_signature in result.signatures:
            print(f"'{text_signature.text}' on page {text_signature.page_number} "
                  f"at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text_with_filters()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"search-text-with-filters.txt\" >}}
```text
Found 1 matching text signature(s)
'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text_with_filters/search-text-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## More Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لتوقيع ملفات PDF و Word و Excel و PowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
