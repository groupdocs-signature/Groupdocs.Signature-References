---
title: "QrCodeVerifyOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Διατηρεί τις επιλογές για επαλήθευση υπογραφής QR-code εγγράφου."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Διατηρεί τις επιλογές για επαλήθευση υπογραφής QR-code εγγράφου.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

Ο τύπος QrCodeVerifyOptions εμφανίζει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code με το καθορισμένο κείμενο QR-code. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Αρχικοποιεί τις επιλογές επαλήθευσης για υπογραφές QR-Code με κείμενο και τύπο κωδικοποίησης QR-Code για επαλήθευση. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | Η υλοποίηση του [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) χρησιμοποιείται για την κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων κειμένου υπογραφής QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | Η επαλήθευση τύπου QR-code. Αυτή η ιδιότητα είναι προαιρετική. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Η σημαία που υποδεικνύει εάν κάθε σελίδα του εγγράφου πρέπει να επαληθευτεί. Από προεπιλογή η τιμή είναι True. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Οι πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Ο τίτλος του πεδίου φόρμας προς επαλήθευση. Εάν οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Ο τύπος του πεδίου φόρμας προς επαλήθευση· εάν οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Η έγκυρη σημαία ιδιότητας. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Η επαλήθευση τύπου αντιστοίχισης κειμένου. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου που θα επαληθευτεί· εάν δεν οριστεί, όλες οι σελίδες του εγγράφου θα επαληθευτούν για την πρώτη εμφάνιση (η ελάχιστη τιμή είναι 1). (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Οι επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Η θέση σχήματος στη διάταξη του εγγράφου που χρησιμοποιείται για την επαλήθευση υπογραφών σε κεφαλίδες/υποσέλιδα. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Το αναγνωριστικό Text Signature για επαλήθευση. Πρέπει να είναι μεγαλύτερο του μηδενός· υποστηρίζεται μόνο για έγγραφα PDF. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Ο τύπος της υπογραφής που θα επαληθευτεί. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Το κείμενο υπογραφής για επαλήθευση. (κληρονομείται από [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
