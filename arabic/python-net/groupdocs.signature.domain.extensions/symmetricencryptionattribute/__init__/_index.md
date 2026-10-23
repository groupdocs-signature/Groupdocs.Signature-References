---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ خوارزمية متماثلة باستخدام المعلمات المحددة."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

يُهيئ خوارزمية متماثلة باستخدام المعلمات المحددة.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | حدد نوع خوارزمية التشفير المتماثل |
| key | `str` | مفتاح التشفير |
| salt | `str` | عبارة مرور للتشفير |

## __init__ {#algorithm_type-key}

يُهيئ خوارزمية متماثلة باستخدام المعلمات وعبارة مرور افتراضية.

```python
def __init__(self, algorithm_type, key):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | نوع خوارزمية التشفير |
| key | `str` | مفتاح التشفير |

### انظر أيضًا
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
