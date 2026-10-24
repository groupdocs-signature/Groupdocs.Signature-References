---
title: "PreviewSignatureOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "서명 미리보기 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

서명 미리보기 옵션을 나타냅니다.

PreviewSignatureOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | PreviewSignatureOptions 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | PreviewSignatureOptions 객체를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | 미리보기 이미지 형식. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | 미리보기를 생성하기 위한 서명 옵션입니다. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | 서명을 구분하는 고유 값입니다. |

### 예시

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # 파일 대신 버퍼에 이미지를 씁니다
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
`PreviewSignatureOptions`를 사용하는 작업 가이드:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
