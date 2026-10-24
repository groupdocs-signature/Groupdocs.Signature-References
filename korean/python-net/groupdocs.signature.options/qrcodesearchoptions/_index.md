---
title: "QrCodeSearchOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QR-Code 서명에 대한 검색 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

QR-Code 서명에 대한 검색 옵션을 나타냅니다.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

이 QrCodeSearchOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | QRCodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | 이 구현은 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/)을 사용하여 QR-Code 서명 텍스트 또는 데이터 속성을 인코딩 및 디코딩합니다. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | QR 코드를 검색하기 위한 인코드 유형. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | 검색 중에 사용되는 QR-Code 텍스트 매치 유형. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | 문서 페이지의 각 서명에 대해 QR‑Code 이미지 콘텐츠가 반환되는지 여부를 결정하는 플래그입니다. True로 설정하면 원시 이미지 데이터가 `return_content_type`으로 지정된 형식을 사용하여 서명의 `content` 속성에 보관됩니다. 기본적으로 비활성화됩니다. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | `return_content` 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠의 파일 형식입니다. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | 검색 및 매치를 위한 QR-Code 서명 텍스트입니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 각 문서 페이지에서 검색할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 검색을 위한 문서 페이지 번호(옵션). ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 문서 레이아웃에서 도형 위치를 반환할지 여부를 나타내는 플래그입니다. Word 문서에서만 사용할 수 있습니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` 로 표시된 서명만 반환하는 플래그입니다. 기본값은 `False`이며, 이는 지정된 기준에 맞는 모든 서명이 반환됨을 의미합니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
