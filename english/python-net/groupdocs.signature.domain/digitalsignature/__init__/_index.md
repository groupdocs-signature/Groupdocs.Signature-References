---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a digital signature with default parameters."
type: docs
url: /python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a digital signature with default parameters.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Initializes a digital signature with a known signature identifier.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Initializes a DigitalSignature using the first certificate from the specified X509 store.

```python
def __init__(self, store):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 store. |

## __init__ {#store-index}

Initializes a DigitalSignature based on the specified X509 store and certificate index.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 store. |
| index | `int` | Index of the certificate. |

## __init__ {#certificate}

Initializes a digital signature with the specified certificate.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 certificate. |

### See Also
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
