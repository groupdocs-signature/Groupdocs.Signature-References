---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट पैरामीटरों के साथ एक डिजिटल हस्ताक्षर को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट पैरामीटरों के साथ एक डिजिटल हस्ताक्षर को प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

ज्ञात हस्ताक्षर पहचानकर्ता के साथ एक डिजिटल हस्ताक्षर को प्रारंभ करता है।

```python
def __init__(self, signature_id):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

निर्दिष्ट X509 स्टोर से पहला प्रमाणपत्र उपयोग करके DigitalSignature को प्रारंभ करता है।

```python
def __init__(self, store):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 स्टोर। |

## __init__ {#store-index}

निर्दिष्ट X509 स्टोर और प्रमाणपत्र अनुक्रमांक के आधार पर DigitalSignature को प्रारंभ करता है।

```python
def __init__(self, store, index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 स्टोर। |
| index | `int` | प्रमाणपत्र का इंडेक्स. |

## __init__ {#certificate}

निर्दिष्ट प्रमाणपत्र के साथ एक डिजिटल हस्ताक्षर को प्रारंभ करता है।

```python
def __init__(self, certificate):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 प्रमाणपत्र। |

### संबंधित देखें
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
