---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο Signature με ένα έγγραφο που παρέχεται ως ροή."
type: docs
url: /el/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Αρχικοποιεί ένα νέο αντικείμενο Signature με ένα έγγραφο που παρέχεται ως ροή.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή περιεχομένου του εγγράφου. |

## __init__ {#document-load_options}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με ροή εγγράφου και επιλογές φόρτωσης.

Μάθετε περισσότερα

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή περιεχομένου του εγγράφου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης του εγγράφου. |

## __init__ {#document-settings}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με έγγραφο που παρέχεται από ροή και προαιρετικά [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Μάθετε περισσότερα:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή περιεχομένου του εγγράφου. |
| settings | `SignatureSettings` | Οι ρυθμίσεις υπογραφής. |

## __init__ {#document-load_options-settings}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με ροή εγγράφου, επιλογές φόρτωσης και ρυθμίσεις υπογραφής.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή περιεχομένου του εγγράφου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης του εγγράφου. |
| settings | `SignatureSettings` | Οι ρυθμίσεις υπογραφής. |

## __init__ {#file_path}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Απόλυτη ή σχετική διαδρομή αρχείου. |

### Παράδειγμα

```python
from groupdocs.signature import Signature

# Ανοίξτε ένα έγγραφο για υπογραφή, αναζήτηση ή επαλήθευση
with Signature("sample.pdf") as signature:
    # εργαστείτε με το αντικείμενο υπογραφής
    pass
```

## __init__ {#file_path-load_options}

Αρχικοποιεί ένα νέο αντικείμενο Signature με το έγγραφο που παρέχεται μέσω διαδρομής αρχείου και επιλογές φόρτωσης.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Απόλυτη ή σχετική διαδρομή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης του εγγράφου. |

### Παράδειγμα

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Εκτελέστε λειτουργίες υπογραφής, αναζήτησης ή επαλήθευσης
    pass
```

## __init__ {#file_path-settings}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με το έγγραφο που παρέχεται μέσω διαδρομής αρχείου και προαιρετικά [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Απόλυτη ή σχετική διαδρομή αρχείου. |
| settings | `SignatureSettings` | Οι ρυθμίσεις υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature import Signature

# Ανοίξτε ένα PDF έγγραφο για υπογραφή ή επαλήθευση
with Signature("sample.pdf") as signature:
    # Χρησιμοποιήστε το στιγμιότυπο υπογραφής εδώ (π.χ., sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Αρχικοποιεί ένα νέο αντικείμενο [`Signature`](/signature/python-net/groupdocs.signature/signature/) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου, επιλογές φόρτωσης και ρυθμίσεις υπογραφής.

Μάθετε περισσότερα:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Απόλυτη ή σχετική διαδρομή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης του εγγράφου. |
| settings | `SignatureSettings` | Οι ρυθμίσεις υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # εκτελέστε λειτουργίες υπογραφής, επαλήθευσης ή αναζήτησης
    pass
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
