---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "기본 매개변수로 디지털 서명을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

기본 매개변수로 디지털 서명을 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

알려진 서명 식별자를 사용하여 디지털 서명을 초기화합니다.

```python
def __init__(self, signature_id):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

지정된 X509 저장소의 첫 번째 인증서를 사용하여 DigitalSignature를 초기화합니다.

```python
def __init__(self, store):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 저장소. |

## __init__ {#store-index}

지정된 X509 저장소와 인증서 인덱스를 기반으로 DigitalSignature를 초기화합니다.

```python
def __init__(self, store, index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 저장소. |
| index | `int` | 인증서의 인덱스. |

## __init__ {#certificate}

지정된 인증서를 사용하여 디지털 서명을 초기화합니다.

```python
def __init__(self, certificate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 인증서. |

### 또 보기
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
