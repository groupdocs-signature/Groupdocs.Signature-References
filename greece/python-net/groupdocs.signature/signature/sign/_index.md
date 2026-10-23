---
title: "sign μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Υπογράφει το έγγραφο με SignOptions και αποθηκεύει το αποτέλεσμα σε ροή."
type: docs
url: /el/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Υπογράφει το έγγραφο με [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα σε ροή.

```python
def sign(self, document, sign_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή εξόδου εγγράφου. |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Σχόλια:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

Υπογράφει ένα έγγραφο με [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα σε ροή χρησιμοποιώντας προορισμένες [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Μάθετε περισσότερα
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή εξόδου εγγράφου. |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής. |
| save_options | `SaveOptions` | Οι επιλογές αποθήκευσης. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα σε ροή.

Μάθετε περισσότερα

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή εξόδου εγγράφου. |
| sign_options_list | `List[SignOptions]` | Η λίστα των επιλογών υπογραφής. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα σε ροή χρησιμοποιώντας προορισμένες [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή εξόδου εγγράφου. |
| sign_options_list | `List[SignOptions]` | Η λίστα των επιλογών υπογραφής. |
| save_options | `SaveOptions` | Οι επιλογές αποθήκευσης. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Σχόλια:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Υπογράψτε και αποθηκεύστε το αποτέλεσμα σε νέο αρχείο· η πηγή παραμένει αμετάβλητη
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Υπογράφει το έγγραφο με SignOptions και αποθηκεύει το αποτέλεσμα στη καθορισμένη διαδρομή αρχείου.

Μάθετε περισσότερα

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή εξόδου αρχείου. |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

Υπογράφει το έγγραφο με [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα στη καθορισμένη διαδρομή αρχείου χρησιμοποιώντας προορισμένες [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή εξόδου αρχείου. |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής. |
| save_options | `SaveOptions` | Οι επιλογές αποθήκευσης. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Ανοίξτε το έγγραφο· το μπλοκ with απελευθερώνει το αρχείο όταν ολοκληρωθεί
    with Signature("sample.pdf") as signature:
        # Μια υπογραφή κειμένου 100 εικονοστοιχεία από τις αριστερές και άνω άκρες της πρώτης σελίδας
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Υπογράψτε και αποθηκεύστε το αποτέλεσμα σε νέο αρχείο· η πηγή παραμένει αμετάβλητη
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα στη καθορισμένη διαδρομή αρχείου.

Μάθετε περισσότερα:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή εξόδου αρχείου. |
| sign_options_list | `List[SignOptions]` | Η λίστα των επιλογών υπογραφής. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) και αποθηκεύει το αποτέλεσμα στη καθορισμένη διαδρομή αρχείου χρησιμοποιώντας προορισμένες [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Μάθετε περισσότερα:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή εξόδου αρχείου. |
| sign_options_list | `List[SignOptions]` | Η λίστα των επιλογών υπογραφής. |
| save_options | `SaveOptions` | Οι επιλογές αποθήκευσης. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
