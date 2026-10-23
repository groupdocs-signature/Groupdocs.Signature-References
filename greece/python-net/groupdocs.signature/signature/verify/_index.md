---
title: "μέθοδος verify"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions."
type: docs
url: /el/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions.

Περισσότερα για την επαλήθευση ηλεκτρονικά υπογεγραμμένων εγγράφων χρησιμοποιώντας το GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Οι επιλογές επαλήθευσης υπογραφής. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα βάσει του καθορισμένου predicate.

Μάθετε περισσότερα

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Οι επιλογές επαλήθευσης υπογραφής. |
| predicate | `Func[BaseSignature, bool]` | Η συνθήκη φίλτρου για τον καθορισμό ποιες υπογραφές πρέπει να επαληθευτούν. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

Επαληθεύει τις υπογραφές του εγγράφου με μια λίστα από δεδομένα VerifyOptions.

Περισσότερα για την επαλήθευση ηλεκτρονικά υπογεγραμμένων εγγράφων χρησιμοποιώντας το GroupDocs.Signature: [Πώς να επαληθεύσετε ότι ένα έγγραφο είναι ηλεκτρονικά υπογεγραμμένο σε C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Η συλλογή επιλογών επαλήθευσης υπογραφής. Παράδειγμα του `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

Επαληθεύει τις υπογραφές εγγράφων χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα με το δεδομένο κατηγόρημα.

Η μέθοδος πρώτα αναζητά υπογραφές που ταιριάζουν με τις επιλογές επαλήθευσης, τις φιλτράρει χρησιμοποιώντας τη συνθήκη, και στη συνέχεια επαληθεύει μόνο τις φιλτραρισμένες υπογραφές.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Η συλλογή επιλογών επαλήθευσης υπογραφής. |
| predicate | `Func[BaseSignature, bool]` | Η συνθήκη φίλτρου για τον καθορισμό ποιες υπογραφές πρέπει να επαληθευτούν. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
