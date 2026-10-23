---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ توقيعًا رقميًا بالمعلمات الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ توقيعًا رقميًا بالمعلمات الافتراضية.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

يُهيئ توقيعًا رقميًا بمعرف توقيع معروف.

```python
def __init__(self, signature_id):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

يُهيئ DigitalSignature باستخدام الشهادة الأولى من مخزن X509 المحدد.

```python
def __init__(self, store):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | مخزن X509. |

## __init__ {#store-index}

يُهيئ DigitalSignature بناءً على مخزن X509 المحدد وفهرس الشهادة.

```python
def __init__(self, store, index):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | مخزن X509. |
| index | `int` | فهرس الشهادة. |

## __init__ {#certificate}

يُهيئ توقيعًا رقميًا بالشهادة المحددة.

```python
def __init__(self, certificate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | شهادة X509. |

### انظر أيضًا
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
