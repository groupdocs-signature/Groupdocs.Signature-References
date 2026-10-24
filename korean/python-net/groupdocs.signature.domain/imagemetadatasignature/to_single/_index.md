---
title: "to_single 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "float으로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

float으로 변환합니다.

Metadata 값을 변환할 수 없는 경우 예외를 발생시킵니다. 원래 값이 문자열 기반인 경우, 기본 문화 속성 정보는 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/)에서 사용됩니다.

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

메타데이터 서명 값을 float으로 변환합니다.

메타데이터 값을 변환할 수 없는 경우 예외를 발생시킵니다.

```python
def to_single(self, provider):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 데이터 변환 작업에 사용할 데이터 제공자를 포맷합니다. |

**Returns:** float: The metadata signature value as a float.

### 또 보기
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
