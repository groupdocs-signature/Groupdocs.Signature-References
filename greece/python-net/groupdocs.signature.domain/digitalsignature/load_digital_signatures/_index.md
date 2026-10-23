---
title: "load_digital_signatures μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Φορτώνει ψηφιακές υπογραφές από όλα τα συστημικά καταστήματα πιστοποιητικών X509."
type: docs
url: /el/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Φορτώνει ψηφιακές υπογραφές από όλα τα συστημικά καταστήματα πιστοποιητικών X509.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Φορτώνει ψηφιακές υπογραφές από μια αποθήκη πιστοποιητικών.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Όνομα ψηφιακής αποθήκευσης που περιέχει πιστοποιητικά. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Φορτώνει ψηφιακές υπογραφές από μια αποθήκη πιστοποιητικών.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store_name | `str` | Προσαρμοσμένο όνομα ψηφιακής αποθήκευσης που περιέχει πιστοποιητικά. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Φορτώνει ψηφιακές υπογραφές από μια αποθήκη ψηφιακών πιστοποιητικών τοποθετημένη σε συγκεκριμένη θέση.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Όνομα ψηφιακής αποθήκευσης που περιέχει πιστοποιητικά. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Τοποθεσία ψηφιακής αποθήκευσης πιστοποιητικών. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Φορτώνει ψηφιακές υπογραφές από μια αποθήκη ψηφιακών πιστοποιητικών τοποθετημένη σε συγκεκριμένη θέση.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store_name | `str` | Προσαρμοσμένο όνομα ψηφιακής αποθήκευσης που περιέχει πιστοποιητικά. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Τοποθεσία ψηφιακής αποθήκευσης πιστοποιητικών. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Δείτε επίσης
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
