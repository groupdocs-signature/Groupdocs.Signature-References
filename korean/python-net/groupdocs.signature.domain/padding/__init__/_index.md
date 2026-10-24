---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Padding 클래스의 새 인스턴스를 0값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Padding 클래스의 새 인스턴스를 0값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature.domain import Padding

# 기본(0) 값으로 패딩 객체를 생성합니다
default_padding = Padding()
```

## __init__ {#all}

Padding 클래스의 새 인스턴스를 제공된 패딩 크기를 모든 가장자리에 적용하여 초기화합니다.

```python
def __init__(self, all):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| all | `int` | 모든 가장자리에 사용할 패딩 측정 단위 수. |

### 예시

```python
# 모든 면에 5 단위의 균일한 패딩
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Padding 클래스의 새 인스턴스를 제공된 패딩 크기를 사용하여 초기화합니다.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| left | `int` | 왼쪽 패딩 크기. |
| right | `int` | 오른쪽 패딩 크기. |
| top | `int` | 위쪽 패딩 크기. |
| bottom | `int` | 아래쪽 패딩 크기입니다. |

### 예시

```python
from groupdocs.signature.domain import Padding

# 오른쪽 및 아래쪽 오프셋으로 패딩을 생성합니다
margin = Padding(right=40, bottom=60)
```

### 또 보기
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
