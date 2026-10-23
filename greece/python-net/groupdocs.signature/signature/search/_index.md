---
title: "search μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναζητά υπογραφές σε ένα έγγραφο χρησιμοποιώντας μια λίστα από SearchOptions."
type: docs
url: /el/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Αναζητά υπογραφές σε ένα έγγραφο χρησιμοποιώντας μια λίστα από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Μάθετε περισσότερα

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Η συλλογή επιλογών αναζήτησης. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας τις παρεχόμενες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει του καθορισμένου predicate.

Μάθετε περισσότερα:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Μια λίστα από στιγμιότυπα `SearchOptions` που ορίζουν τα κριτήρια για την αναζήτηση υπογραφών. |
| predicate | `Func[BaseSignature, bool]` | Η συνθήκη φίλτρου που θα εφαρμοστεί στη λίστα των ευρεθέντων υπογραφών. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Αναζητήστε υπογραφές κειμένου σε κάθε σελίδα
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#search_options}

```python
def search(self, search_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Αναζητά τους καθορισμένους τύπους υπογραφών στο έγγραφο με την τιμή `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Ένας ή πολλοί τύποι υπογραφών προς εύρεση. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Αναζητήστε υπογραφές κειμένου σε κάθε σελίδα
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας όλες τις διαθέσιμες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει του καθορισμένου predicate.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – μια συνάρτηση που λαμβάνει ένα `BaseSignature` και επιστρέφει `True` για να διατηρήσει την υπογραφή ή `False` για να την απορρίψει. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Αναζήτηση κειμενικών υπογραφών και φιλτράρισμά τους με μια προσαρμοσμένη συνθήκη.
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
