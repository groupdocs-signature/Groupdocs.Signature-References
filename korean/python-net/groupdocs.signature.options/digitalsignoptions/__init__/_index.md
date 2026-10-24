---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "DigitalSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

DigitalSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

인증서 파일을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_file_path | `str` | 디지털 인증서 파일 경로. |

### 예시

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

인증서 스트림을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 디지털 인증서 스트림입니다. |

### 예시

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

인증서 파일과 외관 이미지 파일을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_file_path | `str` | 디지털 인증서 파일 경로. |
| image_file_path | `str` | 서명 외관 이미지 파일 경로입니다. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # 생성자에 인증서와 외관 이미지를 전달합니다.
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

인증서 파일과 외관 이미지 스트림을 사용하여 DigitalSignOptions의 새 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_file_path | `str` | 디지털 인증서 파일 경로. |
| appearence_image_stream | `io.RawIOBase` | 서명 외관 이미지 스트림입니다. |

### 예시

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

인증서 스트림과 외관 이미지 파일을 사용하여 DigitalSignOptions의 새 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. 디지털 인증서 스트림입니다. |
| image_file_path | `str` | str. 서명 외관 이미지 파일 경로입니다. |

## __init__ {#certificate_stream-appearence_image_stream}

인증서 스트림과 외관 이미지 스트림을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 디지털 인증서 스트림입니다. |
| appearence_image_stream | `io.RawIOBase` | 서명 외관 이미지 스트림입니다. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # 스트림에서 인증서와 외관 이미지를 로드합니다.
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### 또 보기
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
