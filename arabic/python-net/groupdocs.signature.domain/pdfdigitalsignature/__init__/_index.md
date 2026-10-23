---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ توقيعًا رقميًا PDF دون شهادة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ توقيعًا رقميًا PDF دون شهادة.

```python
def __init__(self):
    ...
```

## __init__ {#store}

يُهيئ توقيعًا رقميًا PDF باستخدام مخزن X509 المحدد. سيتم استخدام الشهادة الأولى من المخزن.

```python
def __init__(self, store):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | مخزن X509. |

## __init__ {#store-index}

يُهيئ توقيعًا رقميًا PDF باستخدام مخزن X509 المحدد وفهرس الشهادة.

```python
def __init__(self, store, index):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | مخزن X509. |
| index | `int` | فهرس الشهادة. |

## __init__ {#certificate}

يُهيئ توقيعًا رقميًا PDF باستخدام شهادة X509 المحددة.

```python
def __init__(self, certificate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | شهادة X509. |

### انظر أيضًا
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
