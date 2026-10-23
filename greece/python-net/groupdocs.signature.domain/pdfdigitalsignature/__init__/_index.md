---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια ψηφιακή υπογραφή PDF χωρίς πιστοποιητικό."
type: docs
url: /el/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια ψηφιακή υπογραφή PDF χωρίς πιστοποιητικό.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Αρχικοποιεί μια ψηφιακή υπογραφή PDF χρησιμοποιώντας το καθορισμένο αποθηκευτικό χώρο X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το αποθηκευτικό χώρο.

```python
def __init__(self, store):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | αποθήκευση X509. |

## __init__ {#store-index}

Αρχικοποιεί μια ψηφιακή υπογραφή PDF χρησιμοποιώντας το καθορισμένο αποθηκευτικό χώρο X509 και το δείκτη πιστοποιίου.

```python
def __init__(self, store, index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | αποθήκευση X509. |
| index | `int` | Δείκτης του πιστοποιητικού. |

## __init__ {#certificate}

Αρχικοποιεί μια ψηφιακή υπογραφή PDF με το καθορισμένο πιστοποιητικό X509.

```python
def __init__(self, certificate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | Πιστοποιητικό X509. |

### Δείτε επίσης
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
