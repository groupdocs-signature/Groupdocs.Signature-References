---
title: "طريقة add_record"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يضيف سجل HIBCPASRecord جديد بنوع البيانات والبيانات المعطاة."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/hibcpasdata/add_record/
is_root: false
weight: 1010
---


## add_record {#data_type-data}

يضيف سجلًا جديدًا [`HIBCPASRecord`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasrecord/) بنوع البيانات والبيانات المعطاة.

```python
def add_record(self, data_type, data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| data_type | `HIBCPASDataType` | نوع بيانات السجل. |
| data | `str` | بيانات السجل. |

## add_record {#record}

يضيف سجلًا جديدًا.

```python
def add_record(self, record):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | `HIBCPASRecord` | السجل الذي سيُضاف. |

**Returns:** Reference to the instance itself.

### انظر أيضًا
* class [`HIBCPASData`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasdata/)
