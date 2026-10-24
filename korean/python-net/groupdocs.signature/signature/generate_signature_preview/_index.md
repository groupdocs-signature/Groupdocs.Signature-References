---
title: "generate_signature_preview 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다.

서명의 미리보기를 생성하는 방법에 대해 자세히 알아보세요:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | 주어진 SignOptions를 사용한 미리보기 서명. |

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
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
