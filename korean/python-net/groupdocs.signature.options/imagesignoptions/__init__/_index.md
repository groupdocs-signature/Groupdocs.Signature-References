---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "ImageSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ImageSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature.options import ImageSignOptions

# 이미지 파일 경로를 사용하여 이미지 서명 옵션을 생성합니다
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

이미지 파일로 ImageSignOptions를 초기화합니다.

```python
def __init__(self, image_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_file_path | `str` | 이미지 파일 경로. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # 여기에서 추가 옵션을 구성하세요, 예: 위치, 크기 등.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

이미지 스트림으로 새 ImageSignOptions 인스턴스를 초기화합니다.

```python
def __init__(self, image_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | 이미지 스트림. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### 또 보기
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
