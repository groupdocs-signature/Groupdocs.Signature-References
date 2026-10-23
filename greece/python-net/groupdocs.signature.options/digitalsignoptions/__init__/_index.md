---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με αρχείο πιστοποιητικού.

```python
def __init__(self, certificate_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_file_path | `str` | Διαδρομή αρχείου ψηφιακού πιστοποιητικού. |

### Παράδειγμα

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με ροή πιστοποιητικού.

```python
def __init__(self, certificate_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Ψηφιακό Πιστοποιητικό ροή. |

### Παράδειγμα

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας εμφάνισης.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_file_path | `str` | Διαδρομή αρχείου ψηφιακού πιστοποιητικού. |
| image_file_path | `str` | Διαδρομή αρχείου εικόνας εμφάνισης υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Περάστε το πιστοποιητικό και την εικόνα εμφάνισης στον κατασκευαστή
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο του DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας εμφάνισης.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_file_path | `str` | Διαδρομή αρχείου ψηφιακού πιστοποιητικού. |
| appearence_image_stream | `io.RawIOBase` | Ροή εικόνας εμφάνισης υπογραφής. |

### Παράδειγμα

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

Αρχικοποιεί ένα νέο στιγμιότυπο του DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας εμφάνισης.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Ψηφιακό Πιστοποιητικό ροή. |
| image_file_path | `str` | str. Διαδρομή αρχείου εικόνας εμφάνισης υπογραφής. |

## __init__ {#certificate_stream-appearence_image_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας εμφάνισης.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Ψηφιακό Πιστοποιητικό ροή. |
| appearence_image_stream | `io.RawIOBase` | Ροή εικόνας εμφάνισης υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Φόρτωση πιστοποιητικού και εικόνας εμφάνισης από ροές
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Δείτε επίσης
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
