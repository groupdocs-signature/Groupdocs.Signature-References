---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους."
type: docs
url: /el/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Αρχικοποιεί μια ψηφιακή υπογραφή με γνωστό αναγνωριστικό υπογραφής.

```python
def __init__(self, signature_id):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Αρχικοποιεί ένα DigitalSignature χρησιμοποιώντας το πρώτο πιστοποιητικό από το καθορισμένο κατάστημα X509.

```python
def __init__(self, store):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | αποθήκευση X509. |

## __init__ {#store-index}

Αρχικοποιεί ένα DigitalSignature βάσει του καθορισμένου καταστήματος X509 και του δείκτη πιστοποιητικού.

```python
def __init__(self, store, index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | αποθήκευση X509. |
| index | `int` | Δείκτης του πιστοποιητικού. |

## __init__ {#certificate}

Αρχικοποιεί μια ψηφιακή υπογραφή με το καθορισμένο πιστοποιητικό.

```python
def __init__(self, certificate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | Πιστοποιητικό X509. |

### Δείτε επίσης
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
