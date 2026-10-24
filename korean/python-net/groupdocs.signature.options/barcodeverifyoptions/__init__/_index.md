---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "바코드 서명을 위한 기본 검증 옵션을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

바코드 서명을 위한 기본 검증 옵션을 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

검증 텍스트가 포함된 기본 검증 옵션을 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 검증할 바코드 텍스트입니다. |

## __init__ {#encode_type}

바코드 유형 검증이 포함된 기본 검증 옵션을 초기화합니다.

```python
def __init__(self, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 바코드 유형 검증입니다. |

## __init__ {#text-encode_type}

바코드 유형 검증 및 텍스트가 포함된 기본 검증 옵션을 초기화합니다.

```python
def __init__(self, text, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 검증할 바코드 텍스트입니다. |
| encode_type | `BarcodeType` | 바코드 유형 검증입니다. |

### 또 보기
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
