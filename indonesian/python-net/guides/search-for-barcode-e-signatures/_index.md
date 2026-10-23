---
title: "Cari e-Tanda Tangan Barcode"
linkTitle: "Barcodes"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara mencari tanda tangan elektronik barcode dalam halaman dokumen menggunakan GroupDocs.Signature untuk Python melalui .NET API"
type: docs
url: /id/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Tanda tangan barcode adalah representasi visual data yang dapat dipindai dan dibaca oleh mesin. Biasanya terdiri dari garis hitam paralel dan ruang putih dengan lebar yang bervariasi. Barcode biasanya digunakan untuk:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

Kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) menyediakan metode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) yang memungkinkan Anda mencari tanda tangan barcode dalam dokumen. Berikut cara menggunakannya:

1. Buat instance baru dari kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) dan berikan jalur dokumen sumber sebagai parameter.
2. Instansiasi objek [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) dengan opsi yang diperlukan.
3. Panggil metode [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) dari instance kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) dan berikan daftar dengan [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) kepadanya.
4. Proses hasil pencarian: properti `signatures` dari [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) yang dikembalikan berisi objek [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) yang ditemukan.

Berikut contoh cara mencari tanda tangan barcode dalam sebuah dokumen:

{{< tabs \"search_barcodes\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Cari tanda tangan barcode di semua halaman dokumen
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

`signed.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) untuk mengunduhnya.

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

Kelas [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) menyediakan properti untuk mempersempit pencarian:

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
        # Cari hanya halaman pertama
        options.all_pages = False
        options.page_number = 1
        # Kembalikan hanya barcode Code 128 yang teksnya dimulai dengan \"1234\"
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

`signed.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) untuk mengunduhnya.

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

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur tersebut beraksi dalam contoh kami:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Bersama dengan pustaka Python lengkap, kami menyediakan Aplikasi gratis yang sederhana namun kuat.

Anda dipersilakan mencari tanda tangan barcode dalam dokumen dengan aplikasi online gratis kami:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
