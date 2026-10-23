---
title: "Κλάση PdfSaveOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές αποθήκευσης για έγγραφα PDF."
type: docs
url: /el/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

Αντιπροσωπεύει τις επιλογές αποθήκευσης για έγγραφα PDF.

Ο τύπος PdfSaveOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με το καθορισμένο μορφότυπο εξόδου αρχείου. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με σημαία αντικατάστασης. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | Αρχικοποιεί ένα νέο αντικείμενο του PdfSaveOptions με το καθορισμένο μορφότυπο εξόδου αρχείου και σημαία αντικατάστασης. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | Η μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | Τα δικαιώματα του εγγράφου PDF, όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | Ο κωδικός πρόσβασης δικαιωμάτων (ο κύριος κωδικός) που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Η σημαία που καθορίζει εάν θα προστεθεί αυτόματα μια επέκταση όταν λείπει στη διαδρομή του αρχείου εξόδου. Η προεπιλεγμένη τιμή είναι False. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Η σημαία που υποδεικνύει εάν θα αντικατασταθεί ένα υπάρχον αρχείο με το νέο αρχείο εξόδου. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για την προστασία του αποθηκευμένου υπογεγραμμένου εγγράφου. Δεν υποστηρίζεται για έγγραφα εικόνας. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Η σημαία που υποδεικνύει εάν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) κατά την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο. Η προεπιλεγμένη τιμή είναι True. Δεν υποστηρίζεται για έγγραφα εικόνας. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
