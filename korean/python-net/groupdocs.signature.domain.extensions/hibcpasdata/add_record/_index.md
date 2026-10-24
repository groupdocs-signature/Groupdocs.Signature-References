---
title: "add_record 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 데이터 유형 및 데이터로 새로운 HIBCPASRecord를 추가합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/hibcpasdata/add_record/
is_root: false
weight: 1010
---


## add_record {#data_type-data}

주어진 데이터 유형 및 데이터를 사용하여 새로운 [`HIBCPASRecord`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasrecord/)를 추가합니다.

```python
def add_record(self, data_type, data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| data_type | `HIBCPASDataType` | 레코드 데이터 유형. |
| data | `str` | 레코드 데이터. |

## add_record {#record}

새 레코드를 추가합니다.

```python
def add_record(self, record):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| record | `HIBCPASRecord` | 추가될 레코드. |

**Returns:** Reference to the instance itself.

### 또 보기
* class [`HIBCPASData`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasdata/)
