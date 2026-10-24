---
title: "try_parse 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 구문 분석 유형 이름과 일치하는 QRCode 유형을 반환하며, 이름을 알 수 없을 경우 None을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

주어진 구문 분석 유형 이름과 일치하는 QRCode 유형을 반환하며, 이름을 알 수 없을 경우 None을 반환합니다.

```python
def try_parse(cls, parsing_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parsing_type | `str` | QRCode 유형 이름의 원본 문자열입니다. |

**Returns:** QrCodeTypes or None: QRCode type instance, or None when the name is not recognized.

### 또 보기
* class [`QrCodeTypes`](/signature/python-net/groupdocs.signature.domain/qrcodetypes/)
