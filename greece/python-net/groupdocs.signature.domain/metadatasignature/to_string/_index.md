---
title: "μέθοδος to_string"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά."
type: docs
url: /el/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Για άλλους τύπους δεδομένων θα χρησιμοποιηθεί ο προεπιλεγμένος πάροχος μορφοποίησης δεδομένων.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Μετατρέπει τη μεταδεδομένη υπογραφή σε συμβολοσειρά χρησιμοποιώντας την καθορισμένη μορφή.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Πληροφορίες προεπιλεγμένης πολιτισμικής ρύθμισης θα χρησιμοποιηθούν από τις ιδιότητες SignatureSettings [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Μετατρέπει σε συμβολοσειρά με καθορισμένη μορφή.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

```python
def to_string(self, format, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** The metadata signature value as a string.

### Δείτε επίσης
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
