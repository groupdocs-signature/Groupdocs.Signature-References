---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ خوارزمية تشفير متماثلة بالمعلمات المحددة."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

يُهيئ خوارزمية تشفير متماثلة بالمعلمات المحددة.

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

يُهيئ خوارزمية تشفير متماثلة بعبارة مرور افتراضية.

```python
def __init__(self, algorithm_type, key):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | حدد نوع الخوارزمية المتماثلة. |
| key | `str` | مفتاح التشفير. |

### انظر أيضًا
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
