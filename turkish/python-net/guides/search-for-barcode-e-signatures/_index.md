---
title: "Barcode e-İmzaları için ara"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, GroupDocs.Signature for Python aracılığıyla .NET API kullanarak belge sayfalarında barkod elektronik imzalarını nasıl arayacağınızı açıklar."
type: docs
url: /tr/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Barkod imzası, makineler tarafından taranıp okunabilen verinin görsel bir temsilidir. Genellikle farklı genişliklerde paralel siyah çizgiler ve beyaz boşluklardan oluşur. Barkodlar genellikle şunlar için kullanılır:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

[Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) sınıfı, belgelerde barkod imzalarını aramanızı sağlayan [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) metodunu sağlar. İşte nasıl kullanılacağı:

1. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) sınıfının yeni bir örneğini oluşturun ve kaynak belge yolunu parametre olarak geçin.
2. Gerekli seçeneklerle [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) nesnesini örnekleyin.
3. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) sınıfı örneğinin [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) metodunu çağırın ve ona [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) içeren bir liste geçirin.
4. Arama sonuçlarını işleyin: döndürülen [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) nesnesinin `signatures` özelliği bulunan [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) nesnelerini tutar.

Bir belgede barkod imzalarını nasıl arayacağınıza dair bir örnek:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Belgenin tüm sayfalarında barkod imzalarını ara
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-barcodes.txt" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

[BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) sınıfı, aramayı daraltmak için özellikler sunar:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs "search_barcodes_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # Yalnızca ilk sayfayı ara
        options.all_pages = False
        options.page_number = 1
        # Metni "1234" ile başlayan yalnızca Code 128 barkodlarını döndür
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
{{< tab "signed.pdf" >}}

`signed.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-barcodes-with-filters.txt" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Tam Python kütüphanesiyle birlikte basit ama güçlü ücretsiz Uygulamalar da sunuyoruz.

Ücretsiz çevrimiçi uygulamalarımızla belgelerde barkod imzalarını aramaya davetlisiniz:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
