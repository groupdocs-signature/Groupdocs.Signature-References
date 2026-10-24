---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "BarcodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature.options import BarcodeSearchOptions

# 기본 설정으로 검색 옵션 객체를 생성합니다
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

BarcodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다.

```python
def __init__(self, encode_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 바코드 인코드 유형을 지정합니다. |

## __init__ {#encode_type-text}

BarcodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다.

```python
def __init__(self, encode_type, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 바코드 인코드 유형을 지정합니다. |
| text | `str` | 바코드 서명의 텍스트를 설정합니다. |

### 또 보기
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
