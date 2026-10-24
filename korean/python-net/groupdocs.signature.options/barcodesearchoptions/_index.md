---
title: "BarcodeSearchOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "바코드 서명에 대한 검색 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

바코드 서명에 대한 검색 옵션을 나타냅니다.

자세히 보기:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

BarcodeSearchOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | BarcodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | BarcodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | BarcodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | 바코드 검색을 필터링하는 데 사용되는 인코드 유형입니다; 설정되지 않으면 검색에 모든 지원되는 바코드 유형이 포함됩니다. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | 검색에 사용되는 바코드 텍스트 매치 유형입니다. `text` 속성이 설정된 경우에만 사용됩니다. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | 문서 페이지에서 서명의 바코드 이미지 콘텐츠를 가져올지 여부를 나타내는 플래그입니다. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | `return_content` 속성이 활성화된 경우 바코드 서명의 반환된 이미지 콘텐츠 파일 유형입니다. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | 검색 및 매치를 위한 바코드 서명의 텍스트입니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 각 문서 페이지에서 검색할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 검색을 위한 문서 페이지 번호(옵션). ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 문서 레이아웃에서 도형 위치를 반환할지 여부를 나타내는 플래그입니다. Word 문서에서만 사용할 수 있습니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` 로 표시된 서명만 반환하는 플래그입니다. 기본값은 `False`이며, 이는 지정된 기준에 맞는 모든 서명이 반환됨을 의미합니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
`BarcodeSearchOptions`를 사용하는 작업 가이드:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
