---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "BarcodeSignOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSignOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#text}

텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 바코드 텍스트. |

### 예시

```python
from groupdocs.signature.options import BarcodeSignOptions

# 원하는 텍스트로 바코드 서명 옵션을 생성합니다
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, text, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 바코드 텍스트. |
| encode_type | `BarcodeType` | 바코드 인코드 유형. |

### 예시

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# 텍스트와 유형을 사용하여 바코드 서명 옵션을 생성합니다
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### 또 보기
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
