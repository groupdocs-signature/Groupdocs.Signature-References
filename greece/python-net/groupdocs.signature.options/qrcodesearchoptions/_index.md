---
title: "κλάση QrCodeSearchOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές QR-Code."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές QR-Code.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Ο τύπος QrCodeSearchOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με τιμή τύπου κωδικοποίησης. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSearchOptions με τύπο κωδικοποίησης και τιμές κειμένου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | Η υλοποίηση του [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) που χρησιμοποιείται για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Ο τύπος κωδικοποίησης για την αναζήτηση κωδικών QR. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Ο τύπος αντιστοίχισης κειμένου QR-Code που χρησιμοποιείται κατά την αναζήτηση. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Η σημαία που καθορίζει εάν το περιεχόμενο εικόνας QR‑Code επιστρέφεται για κάθε υπογραφή σε μια σελίδα εγγράφου. Όταν ορίζεται σε True, τα ακατέργαστα δεδομένα εικόνας διατηρούνται στην ιδιότητα `content` της υπογραφής χρησιμοποιώντας τη μορφή που καθορίζεται από το `return_content_type`. Απενεργοποιημένο από προεπιλογή. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα `return_content` είναι ενεργοποιημένη. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | Το κείμενο υπογραφής QR-Code για αναζήτηση και αντιστοίχιση. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Η σημαία που υποδεικνύει αν θα γίνει αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή είναι True. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για αναζήτηση (προαιρετικό). (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Οι επιλογές για καθορισμό σελίδων για αναζήτηση υπογραφών. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Η σημαία που υποδεικνύει αν θα επιστραφεί η θέση του σχήματος στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Η σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως `IsSignature`. Από προεπιλογή η τιμή είναι `False`, που υποδεικνύει ότι επιστρέφονται όλες οι υπογραφές που ταιριάζουν στα καθορισμένα κριτήρια. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
