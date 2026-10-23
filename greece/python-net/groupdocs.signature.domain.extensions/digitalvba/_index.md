---
title: "κλάση DigitalVBA"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει την ψηφιακή υπογραφή για έργα VBA σε λογιστικά φύλλα."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Αντιπροσωπεύει την ψηφιακή υπογραφή για έργα VBA σε λογιστικά φύλλα.

Παρέχει τη δυνατότητα υπογραφής ενός έργου VBA σε μορφές εγγράφων λογιστικού φύλλου όπως `Xlsm` ή `Xltm`. Εάν προστεθούν πολλές επεκτάσεις [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) στο [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), μόνο η πρώτη χρησιμοποιείται κατά την υπογραφή.

Ο τύπος DigitalVBA εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalVBA με αρχείο πιστοποιητικού. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalVBA με ροή πιστοποιητικού. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. (κληρονομείται από [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Η διαδρομή του αρχείου ψηφιακού πιστοποιητικού, χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το `CertificateStream`. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Η ροή του ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί για CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Τα σχόλια της υπογραφής. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Ο κωδικός πρόσβασης του ψηφιακού πιστοποιητικού. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Η ρύθμιση που καθορίζει εάν θα υπογραφεί μόνο το έργο VBA. Όταν True, το ίδιο το έγγραφο λογιστικού φύλλου δεν υπογράφεται· μόνο το έργο VBA υπογράφεται. |

### Παράδειγμα

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Υπογραφή μακροεντολών εντός του λογιστικού φύλλου
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Προσθήκη επέκτασης για ψηφιακή υπογραφή του έργου VBA
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Επαλήθευση ότι προστέθηκε το τμήμα υπογραφής του έργου VBA
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Δείτε επίσης
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
