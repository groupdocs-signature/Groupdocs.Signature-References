---
title: "to_double 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명 값을 float으로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

메타데이터 서명 값을 float으로 변환합니다.

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원래 값이 문자열 기반인 경우, [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 에서 기본 문화가 사용됩니다.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Double로 변환합니다.

```python
def to_double(self, provider):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 데이터 변환 작업에 사용할 데이터 제공자를 포맷합니다. |

**Returns:** float: The metadata signature value as a float.

### 또 보기
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
