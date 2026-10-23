---
title: "طريقة load_digital_signatures"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "حمّل التواقيع الرقمية من جميع مخازن شهادات X509 النظامية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

حمّل التواقيع الرقمية من جميع مخازن شهادات X509 النظامية.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

حمّل التواقيع الرقمية من تخزين شهادة.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | اسم مساحة تخزين رقمية تحتوي على الشهادات. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

حمّل التواقيع الرقمية من تخزين شهادة.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store_name | `str` | اسم مخصص لمساحة تخزين رقمية تحتوي على الشهادات. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

حمّل التواقيع الرقمية من تخزين شهادة رقمية موجود في موقع محدد.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | اسم مساحة تخزين رقمية تحتوي على الشهادات. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | موقع مساحة تخزين شهادة رقمية. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

يحمّل التواقيع الرقمية من تخزين شهادة رقمية موجود في موقع محدد.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| store_name | `str` | اسم مخصص لمساحة تخزين رقمية تحتوي على الشهادات. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | موقع مساحة تخزين شهادة رقمية. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### انظر أيضًا
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
