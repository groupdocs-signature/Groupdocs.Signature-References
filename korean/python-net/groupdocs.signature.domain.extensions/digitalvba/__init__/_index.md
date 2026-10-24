---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "인증서 파일을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

인증서 파일을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_file_path | `str` | 디지털 인증서 파일 경로. |
| password | `str` | 디지털 인증서 비밀번호. |

### 예시

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# 인증서 파일과 비밀번호를 사용하여 DigitalVBA 확장을 생성합니다.
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

인증서 스트림을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_stream, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 디지털 인증서를 포함하는 io.RawIOBase. |
| password | `str` | 디지털 인증서용 문자열 비밀번호. |

### 또 보기
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
