---
title: "load_digital_signatures 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "시스템의 모든 X509 인증서 저장소에서 디지털 서명을 로드합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

시스템의 모든 X509 인증서 저장소에서 디지털 서명을 로드합니다.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

인증서 저장소에서 디지털 서명을 로드합니다.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 인증서를 포함하는 디지털 저장소의 이름. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

인증서 저장소에서 디지털 서명을 로드합니다.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store_name | `str` | 인증서를 포함하는 디지털 저장소의 사용자 지정 이름. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

특정 위치에 배치된 디지털 인증서 저장소에서 디지털 서명을 로드합니다.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 인증서를 포함하는 디지털 저장소의 이름. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | 디지털 인증서 저장소의 위치. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

특정 위치에 배치된 디지털 인증서 저장소에서 디지털 서명을 로드합니다.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| store_name | `str` | 인증서를 포함하는 디지털 저장소의 사용자 지정 이름. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | 디지털 인증서 저장소의 위치. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### 또 보기
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
