---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QR-Code 서명을 위한 검증 옵션을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

QR-Code 서명을 위한 검증 옵션을 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

지정된 QR 코드 텍스트를 사용하여 QR-Code 서명을 위한 검증 옵션을 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 검증할 QR 코드 텍스트입니다. |

### 예시

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# 옵션을 생성하고 검증할 QR 코드 텍스트를 설정합니다.
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

텍스트와 검증할 QR-Code 인코드 유형을 사용하여 QR-Code 서명을 위한 검증 옵션을 초기화합니다.

```python
def __init__(self, text, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 검증할 텍스트입니다. |
| encode_type | `QrCodeType` | 인코딩 유형입니다. |

### 예시

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### 또 보기
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
