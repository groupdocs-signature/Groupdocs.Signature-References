---
title: "delete μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Διαγράφει το καθορισμένο BaseSignature από το έγγραφο."
type: docs
url: /el/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Διαγράφει το καθορισμένο [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) από το έγγραφο.

Μάθετε περισσότερα:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature | `BaseSignature` | Αντικείμενο BaseSignature που θα αφαιρεθεί από το έγγραφο. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Παράδειγμα

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # Η delete() αποθηκεύει τις αλλαγές στο ανοιχτό έγγραφο, γι' αυτό δουλέψτε σε αντίγραφο
    shutil.copy("signed.docx", "text_signature_deleted.docx")
    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        if signature.delete(signatures[0]):
            print("Signature deleted")
```

## delete {#signatures}

Διαγράφει τη λίστα υπογραφών που παρέχεται από το έγγραφο.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Λίστα υπογραφών προς αφαίρεση από το έγγραφο. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Παράδειγμα

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Δουλέψτε σε αντίγραφο επειδή η delete() αποθηκεύει τις αλλαγές στο ανοιχτό έγγραφο
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Διαγράψτε την πρώτη βρεθείσα υπογραφή
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Διαγράφει τις υπογραφές του καθορισμένου τύπου από το έγγραφο.

Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο `Sign` και σημειώθηκαν ως υπογραφές ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) θα αφαιρεθούν. Οι υποστηριζόμενοι τύποι υπογραφών είναι Κείμενο, Εικόνα, Ψηφιακή, Barcode και QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_type | `SignatureType` | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Εγείρει | Περιγραφή |
| :- | :- |
| `Remarks` | - Μάθετε περισσότερα: - Περισσότερα για το πώς να διαγράψετε ηλεκτρονική υπογραφή από έγγραφο σε C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Προχωρημένες περιπτώσεις χρήσης για τη διαγραφή eSignature εγγράφων: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Διαγράφει τις υπογραφές της καθορισμένης λίστας `SignatureType` από το έγγραφο.

Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο `Sign` και σημειώθηκαν ως υπογραφές ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) θα αφαιρεθούν. Οι υποστηριζόμενοι τύποι υπογραφών είναι Κείμενο, Εικόνα, Ψηφιακή, Barcode και QR‑Code.

Μάθετε περισσότερα
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Διαγράφει μια υπογραφή με το συγκεκριμένο Id της υπογραφής από το έγγραφο.

Μάθετε περισσότερα:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_id | `str` | Το Id της υπογραφής που θα αφαιρεθεί από το έγγραφο. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Διαγράφει τις καθορισμένες υπογραφές από το έγγραφο.

Μάθετε περισσότερα:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_ids | `List[str]` | Λίστα των αναγνωριστικών των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Παράδειγμα

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Δουλέψτε σε αντίγραφο επειδή η delete() αποθηκεύει τις αλλαγές στο ανοιχτό έγγραφο
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return

        text_signature = signatures[0]
        result = signature.delete([text_signature.id])
        if result.successful:
            print(f"Deleted text signature '{text_signature.text}'")
        else:
            print(f"Failed to delete text signature '{text_signature.text}'")
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
