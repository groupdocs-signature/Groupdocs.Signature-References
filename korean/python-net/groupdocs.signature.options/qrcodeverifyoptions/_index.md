---
title: "QrCodeVerifyOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 QR-code 서명을 검증하기 위한 옵션을 보관합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

문서 QR-code 서명을 검증하기 위한 옵션을 보관합니다.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

QrCodeVerifyOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | QR-Code 서명을 위한 검증 옵션을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | 지정된 QR 코드 텍스트를 사용하여 QR-Code 서명을 위한 검증 옵션을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | 텍스트와 검증할 QR-Code 인코드 유형을 사용하여 QR-Code 서명을 위한 검증 옵션을 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | QR-Code 서명 텍스트 속성을 인코딩 및 디코딩하는 데 사용되는 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 구현입니다. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | QR-code 유형 검증입니다. 이 속성은 선택 사항입니다. |
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
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
