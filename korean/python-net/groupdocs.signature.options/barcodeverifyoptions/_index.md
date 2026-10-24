---
title: "BarcodeVerifyOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "바코드 검증 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

바코드 검증 옵션을 나타냅니다.

자세히 알아보기
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

BarcodeVerifyOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | 바코드 서명을 위한 기본 검증 옵션을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | 검증 텍스트가 포함된 기본 검증 옵션을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | 바코드 유형 검증이 포함된 기본 검증 옵션을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | 바코드 유형 검증 및 텍스트가 포함된 기본 검증 옵션을 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | 검증에 사용되는 바코드 유형입니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 각 문서 페이지를 검증할지 여부를 나타내는 플래그. 기본값은 True입니다. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 대체 서명 옵션 검증을 위한 추가 확장자. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 검증할 폼 필드의 제목입니다. 설정하면 텍스트는 텍스트 폼 필드에서만 찾습니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 검증할 폼 필드의 유형; 설정하면 텍스트는 텍스트 폼 필드에서만 찾습니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 유효한 속성 플래그. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | 텍스트 일치 유형 검증입니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 검증할 문서 페이지 번호; 설정되지 않으면 문서의 모든 페이지가 첫 번째 발생에 대해 검증됩니다(최소값은 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 검증할 페이지를 지정하기 위한 페이지 옵션입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 머리글/바닥글에 서명을 검증하는 데 사용되는 문서 레이아웃의 도형 위치입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 검증할 텍스트 서명 ID입니다. 0보다 커야 하며; PDF 문서에서만 지원됩니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 검증될 서명의 유형입니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 검증할 서명 텍스트입니다. (상속됨: [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
