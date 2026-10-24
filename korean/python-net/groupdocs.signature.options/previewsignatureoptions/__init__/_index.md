---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PreviewSignatureOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

PreviewSignatureOptions 인스턴스를 초기화합니다.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| sign_options | `SignOptions` | 미리보기를 생성할 서명 옵션입니다. |
| create_signature_stream | `CreateSignatureStream` | 출력 서명 미리보기 스트림을 생성하는 대리자. |

### 예시

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# 미리보기 이미지를 받기 위한 메모리 버퍼
preview_buffer = io.BytesIO()

def create_stream(options):
    # 모든 미리보기 생성에 대해 동일한 버퍼를 반환합니다
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# 버퍼에 미리보기 이미지를 생성합니다
Signature.generate_signature_preview(preview_opts)

# 생성된 PNG 바이트에 접근합니다
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

PreviewSignatureOptions 객체를 초기화합니다.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| sign_options | `SignOptions` | 미리보기를 생성할 서명 옵션입니다. |
| create_signature_stream | `CreateSignatureStream` | 출력 서명 미리보기 스트림을 생성하는 호출 가능 객체입니다. 서명 옵션을 받아 `io.RawIOBase`(예: `io.BytesIO`)를 반환해야 합니다. |
| release_signature_stream | `ReleaseSignatureStream` | 출력 서명 미리보기 스트림을 해제하는 호출 가능 객체입니다. 서명 옵션과 스트림을 받아 필요에 따라 정리 작업을 수행합니다. |

### 예시

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_qr_code_image():
    result = io.BytesIO()
    qr_options = QrCodeSignOptions()
    qr_options.encode_type = QrCodeTypes.QR
    qr_options.text = "Case 148-01"

    preview_options = PreviewSignatureOptions(
        qr_options,
        lambda options: result,
        lambda options, stream: None,
    )
    Signature.generate_signature_preview(preview_options)

    with open("qr_code_result.png", "wb") as f:
        f.write(result.getvalue())
```

### 또 보기
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
