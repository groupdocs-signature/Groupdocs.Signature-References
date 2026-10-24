---
title: "try_parse 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 파싱 유형 이름에 일치하는 Barcode 유형을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

주어진 파싱 유형 이름에 일치하는 Barcode 유형을 반환합니다.

이름이 알려지지 않은 경우, 메서드는 예외를 발생시키는 대신 None을 반환합니다.

```python
def try_parse(cls, parsing_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parsing_type | `str` | 바코드 유형 이름의 원본 문자열. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### 또 보기
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
