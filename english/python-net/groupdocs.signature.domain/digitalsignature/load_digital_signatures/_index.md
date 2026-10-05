---
title: load_digital_signatures method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Load digital signatures from all system X509 certificate stores."
type: docs
url: /python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Load digital signatures from all system X509 certificate stores.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Load digital signatures from a certificate storage.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Name of a digital storage containing certificates. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Load digital signatures from a certificate storage.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store_name | `str` | Custom name of a digital storage containing certificates. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Load digital signatures from a digital certificate storage placed in a specific location.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Name of a digital storage containing certificates. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Location of a digital certificate storage. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Loads digital signatures from a digital certificate storage placed at a specific location.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| store_name | `str` | Custom name of a digital storage containing certificates. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Location of a digital certificate storage. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### See Also
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
