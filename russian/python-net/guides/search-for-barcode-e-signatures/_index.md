---
title: "Поиск электронных подписей на основе штрихкодов"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье объясняется, как искать электронные подписи штрихкода на страницах документов с помощью GroupDocs.Signature для Python через .NET API"
type: docs
url: /ru/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Подпись штрихкода — это визуальное представление данных, которое может быть сканировано и прочитано машинами. Обычно она состоит из параллельных черных линий и белых промежутков различной ширины. Штрихкоды обычно используются для:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

Класс [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) предоставляет метод [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/), который позволяет искать подписи штрихкода в документах. Вот как его использовать:

1. Создайте новый экземпляр класса [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) и передайте путь к исходному документу в качестве параметра.
2. Создайте объект [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) с необходимыми параметрами.
3. Вызовите метод [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) у экземпляра класса [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) и передайте ему список с объектом [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/).
4. Обработайте результаты поиска: свойство `signatures` возвращённого объекта [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) содержит найденные объекты [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/).

Ниже приведён пример того, как искать подписи штрихкода в документе:

{{< tabs \"search_barcodes\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Поиск подписи штрихкода на всех страницах документа
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

`signed.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf), чтобы скачать его.

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

Класс [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) предоставляет свойства для уточнения поиска:

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
        # Искать только первую страницу
        options.all_pages = False
        options.page_number = 1
        # Возвращать только штрихкоды Code 128, текст которых начинается с \"1234\"
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

`signed.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf), чтобы скачать его.

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

Вы можете легко выполнить приведённый выше код и увидеть работу функции в наших примерах:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Вместе с полной библиотекой Python мы предоставляем простые, но мощные бесплатные приложения.

Вы можете искать подписи штрихкода в документах с помощью наших бесплатных онлайн‑приложений:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
