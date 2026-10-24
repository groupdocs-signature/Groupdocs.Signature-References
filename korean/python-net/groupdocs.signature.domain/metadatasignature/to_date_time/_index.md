---
title: "to_date_time 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명 값을 날짜/시간으로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

메타데이터 서명 값을 날짜/시간으로 변환합니다.

메타데이터 값을 변환할 수 없으면 예외가 발생합니다. 원래 값이 문자열 기반인 경우, 변환을 위해 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 에서 기본 문화가 사용됩니다.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

메타데이터 서명 값을 날짜/시간으로 변환합니다.

```python
def to_date_time(self, provider):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 데이터 변환 작업에 사용할 데이터 제공자를 포맷합니다. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

### 또 보기
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
