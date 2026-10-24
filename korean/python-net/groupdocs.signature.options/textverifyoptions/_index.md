---
title: "TextVerifyOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 텍스트 서명을 검증하기 위한 옵션을 보관합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

문서 텍스트 서명을 검증하기 위한 옵션을 보관합니다.

자세히 보기:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

TextVerifyOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | TextVerifyOptions의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | TextVerifyOptions의 새 인스턴스를 검증 텍스트와 함께 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | 검증할 텍스트와 서명 구현 유형을 사용하여 새 TextVerifyOptions 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 검증할 폼 필드의 제목. 설정하면 텍스트가 텍스트 폼 필드에서만 검색됩니다. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 검증할 폼 필드 유형; 설정하면 텍스트가 텍스트 폼 필드에서만 검색됩니다. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | 텍스트 매치 유형 검증. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 검증할 텍스트 서명 ID. 0보다 커야 하며 PDF 문서에서만 지원됩니다. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 검증할 서명 유형. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 검증할 서명 텍스트. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 각 문서 페이지를 검증할지 여부를 나타내는 플래그. 기본값은 True입니다. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 대체 서명 옵션 검증을 위한 추가 확장자. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 유효한 속성 플래그. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 검증할 문서 페이지 번호; 설정되지 않으면 문서의 모든 페이지가 첫 번째 발생에 대해 검증됩니다(최소값은 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 검증할 페이지를 지정하기 위한 페이지 옵션입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 머리글/바닥글에 서명을 검증하는 데 사용되는 문서 레이아웃의 도형 위치입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 예시

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

### Guides
`TextVerifyOptions`를 사용하는 작업 가이드:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
