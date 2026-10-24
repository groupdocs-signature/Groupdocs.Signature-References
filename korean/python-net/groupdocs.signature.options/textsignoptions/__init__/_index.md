---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "기본값으로 TextSignOptions 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

기본값으로 TextSignOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#text}

텍스트와 함께 TextSignOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 서명 텍스트. |

### 예시

```python
from groupdocs.signature.options import TextSignOptions

# 원하는 서명 텍스트로 텍스트 서명 옵션을 생성합니다.
options = TextSignOptions("John Smith")
```

### 또 보기
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
