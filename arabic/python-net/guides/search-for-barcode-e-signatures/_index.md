---
title: "ابحث عن توقيعات إلكترونية للباركود"
linkTitle: "Barcodes"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تشرح هذه المقالة كيفية البحث عن التواقيع الإلكترونية للباركود داخل صفحات المستند باستخدام GroupDocs.Signature للبايثون عبر واجهة .NET API"
type: docs
url: /ar/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

توقيع الباركود هو تمثيل بصري للبيانات يمكن مسحه ضوئياً وقراءته بواسطة الآلات. عادةً ما يتكون من خطوط سوداء متوازية ومسافات بيضاء بعروض مختلفة. تُستخدم الباركودات عادةً لـ:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

توفر الفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) الطريقة [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) التي تتيح لك البحث عن توقيعات الباركود في المستندات. إليك كيفية استخدامها:

1. أنشئ مثيلاً جديداً للفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) ومرّر مسار المستند المصدر كمعامل.
2. أنشئ كائن [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) مع الخيارات المطلوبة.
3. استدعِ الطريقة [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) لكائن الفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) ومرّر إليه قائمة تحتوي على [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/).
4. عالج نتائج البحث: خاصية `signatures` في الكائن [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) المعاد تحتوي على كائنات [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) التي تم العثور عليها.

إليك مثال على كيفية البحث عن توقيعات الباركود في مستند:

{{< tabs \"search_barcodes\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # ابحث في جميع صفحات المستند عن توقيعات الباركود
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"search-barcodes.txt\" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

توفر الفئة [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) خصائص لتضييق نطاق البحث:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs \"search_barcodes_with_filters\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # ابحث في الصفحة الأولى فقط
        options.all_pages = False
        options.page_number = 1
        # أرجع فقط باركودات Code 128 التي يبدأ نصها بـ "1234"
        options.encode_type = BarcodeTypes.CODE128
        options.text = "1234"
        options.match_type = TextMatchType.STARTS_WITH

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}'")

if __name__ == "__main__":
    search_barcodes_with_filters()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` هو ملف العينة المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"search-barcodes-with-filters.txt\" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلتنا:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

إلى جانب مكتبة بايثون الكاملة، نوفر تطبيقات مجانية بسيطة ولكن قوية.

نرحب بك للبحث عن توقيعات الباركود في المستندات باستخدام تطبيقاتنا المجانية على الإنترنت:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
