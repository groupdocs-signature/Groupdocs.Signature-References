---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "기본값으로 DigitalVerifyOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

기본값으로 DigitalVerifyOptions 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

지정된 디지털 인증서 파일 경로로 DigitalVerifyOptions 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_file_path | `str` | 디지털 인증서의 파일 경로. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

지정된 인증서 스트림으로 DigitalVerifyOptions 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 인증서 스트림. |

### 또 보기
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
