---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με το καθορισμένο μορφότυπο εξόδου αρχείου.

```python
def __init__(self, file_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Τύπος αρχείου εξόδου `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με σημαία αντικατάστασης.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

## __init__ {#file_format-overwrite_existing_file}

Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με το καθορισμένο μορφότυπο εξόδου αρχείου και σημαία αντικατάστασης.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Τύπος αρχείου εξόδου. |
| overwrite_existing_file | `bool` | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

### Παράδειγμα

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Δημιουργήστε επιλογές αποθήκευσης με μορφή PDF και επιτρέψτε την αντικατάσταση υπαρχόντων αρχείων
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Δείτε επίσης
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
