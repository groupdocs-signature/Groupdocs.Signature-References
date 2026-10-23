---
title: "μέθοδος to_string"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε string."
type: docs
url: /el/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε string.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Μετατρέπει την τιμή της υπογραφής μεταδεδομένων σε string χρησιμοποιώντας τη καθορισμένη μορφή.

Μετατρέπει μια λογική ιδιότητα σε "True" ή "False". Χρησιμοποιείται η προεπιλεγμένη πληροφορία πολιτισμού από [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Μετατρέπει σε συμβολοσειρά με το καθορισμένο μορφότυπο.

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

```python
def to_string(self, format, provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | `str` | Συμβολοσειρά μορφοποίησης δεδομένων. |
| provider | `System.IFormatProvider` | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

**Returns:** str: The metadata signature value as a string.

### Δείτε επίσης
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
