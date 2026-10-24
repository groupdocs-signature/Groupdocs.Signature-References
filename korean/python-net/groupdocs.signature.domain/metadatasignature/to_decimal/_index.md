---
title: "to_decimal 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명 값을 Decimal로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

메타데이터 서명 값을 Decimal로 변환합니다.

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원본 값이 문자열 기반인 경우, 기본 문화 속성 정보가 [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/)에서 사용됩니다.

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

메타데이터 서명 값을 Decimal로 변환합니다.

```python
def to_decimal(self, provider):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 데이터 변환 작업에 사용할 데이터 제공자를 포맷합니다. |

**Returns:** The metadata signature value as Decimal.

### 또 보기
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
