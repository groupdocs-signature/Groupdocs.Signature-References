---
title: "to_string 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "재정의된 ToString 메서드를 사용하여 메타데이터 서명 값을 문자열로 변환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

재정의된 `ToString` 메서드를 사용하여 메타데이터 서명 값을 문자열로 변환합니다.

불리언 속성을 `True` 또는 `False` 로 변환합니다. 다른 데이터 유형의 경우 기본 데이터 형식 제공자가 사용됩니다.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

지정된 형식을 사용하여 메타데이터 서명을 문자열로 변환합니다.

부울 속성을 "True" 또는 "False" 로 변환합니다.

```python
def to_string(self, format, provider):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| format | `str` | 데이터 형식 문자열. |
| provider | `System.IFormatProvider` | 데이터 변환 작업에 사용할 데이터 제공자를 포맷합니다. |

**Returns:** str: The metadata signature value as a string.

### 또 보기
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
