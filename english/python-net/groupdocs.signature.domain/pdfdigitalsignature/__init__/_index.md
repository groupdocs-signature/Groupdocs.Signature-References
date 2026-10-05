---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a PDF digital signature without a certificate."
type: docs
url: /python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a PDF digital signature without a certificate.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Initializes a PDF digital signature using the specified X509 store. The first certificate from the store will be used.

```python
def __init__(self, store):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 store. |

## __init__ {#store-index}

Initializes a PDF digital signature using the specified X509 store and certificate index.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 store. |
| index | `int` | Index of certificate. |

## __init__ {#certificate}

Initializes a PDF digital signature with the specified X509 certificate.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 certificate. |

### See Also
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
