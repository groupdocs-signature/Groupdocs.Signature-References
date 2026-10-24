---
title: "바코드 전자 서명 검색"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서는 .NET API를 통해 Python용 GroupDocs.Signature를 사용하여 문서 페이지 내에서 바코드 전자 서명을 검색하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

바코드 서명은 기계가 스캔하고 읽을 수 있는 데이터의 시각적 표현입니다. 일반적으로 다양한 두께의 평행한 검은 선과 흰 공간으로 구성됩니다. 바코드는 일반적으로 다음 용도로 사용됩니다:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

The [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) 클래스는 문서에서 바코드 서명을 검색할 수 있는 [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) 메서드를 제공합니다. 사용 방법은 다음과 같습니다:

1. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) 클래스의 새 인스턴스를 생성하고 소스 문서 경로를 매개변수로 전달합니다.
2. 필요한 옵션을 사용하여 [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) 객체를 인스턴스화합니다.
3. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) 클래스 인스턴스의 [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) 메서드를 호출하고, [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) 목록을 전달합니다.
4. 검색 결과를 처리합니다: 반환된 [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/)의 `signatures` 속성에 찾은 [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) 객체가 포함됩니다.

문서에서 바코드 서명을 검색하는 예시는 다음과 같습니다:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # 문서의 모든 페이지에서 바코드 서명을 검색합니다
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

`signed.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf)를 클릭하십시오.

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

[BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) 클래스는 검색 범위를 좁히는 속성을 제공합니다:

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
        # 첫 페이지만 검색합니다
        options.all_pages = False
        options.page_number = 1
        # 텍스트가 "1234"로 시작하는 Code 128 바코드만 반환합니다
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

`signed.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf)를 클릭하십시오.

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

위 코드를 쉽게 실행하여 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

전체 Python 라이브러리와 함께 간단하지만 강력한 무료 앱을 제공합니다.

무료 온라인 앱을 사용하여 문서에서 바코드 서명을 검색해 보세요:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
