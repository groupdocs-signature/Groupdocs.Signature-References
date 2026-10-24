---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "인증서 없이 PDF 디지털 서명을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

인증서 없이 PDF 디지털 서명을 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#store}

지정된 X509 저장소를 사용하여 PDF 디지털 서명을 초기화합니다. 저장소의 첫 번째 인증서가 사용됩니다.

```python
def __init__(self, store):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 저장소. |

## __init__ {#store-index}

지정된 X509 저장소와 인증서 인덱스를 사용하여 PDF 디지털 서명을 초기화합니다.

```python
def __init__(self, store, index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 저장소. |
| index | `int` | 인증서 인덱스. |

## __init__ {#certificate}

지정된 X509 인증서를 사용하여 PDF 디지털 서명을 초기화합니다.

```python
def __init__(self, certificate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 인증서. |

### 또 보기
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
