---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QRCodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

QRCodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다.

```python
def __init__(self, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code 인코드 유형을 지정합니다. |

## __init__ {#encode_type-text}

QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다.

```python
def __init__(self, encode_type, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code 인코드 유형을 지정합니다. |
| text | `str` | QR-Code 서명의 텍스트를 설정합니다. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### 또 보기
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
