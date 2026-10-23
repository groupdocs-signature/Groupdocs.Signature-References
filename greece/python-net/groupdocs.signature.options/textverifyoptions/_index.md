---
title: "TextVerifyOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Διατηρεί επιλογές για επαλήθευση υπογραφής Κειμένου εγγράφου."
type: docs
url: /el/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Διατηρεί επιλογές για επαλήθευση υπογραφής Κειμένου εγγράφου.

Μάθετε περισσότερα:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

Ο τύπος TextVerifyOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με κείμενο επαλήθευσης. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Αρχικοποιεί ένα νέο αντικείμενο TextVerifyOptions με το κείμενο προς επαλήθευση και τον τύπο υλοποίησης της υπογραφής. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Ο τίτλος του πεδίου φόρμας προς επαλήθευση. Εάν οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Ο τύπος του πεδίου φόρμας προς επαλήθευση· εάν οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία κειμένου φόρμας. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Η επαλήθευση του τύπου αντιστοίχισης κειμένου. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Το ID της Υπογραφής Κειμένου προς επαλήθευση. Πρέπει να είναι μεγαλύτερο του μηδενός· υποστηρίζεται μόνο για έγγραφα PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Ο τύπος της υπογραφής που θα επαληθευθεί. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Το κείμενο της υπογραφής προς επαλήθευση. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Η σημαία που υποδεικνύει εάν κάθε σελίδα του εγγράφου πρέπει να επαληθευτεί. Από προεπιλογή η τιμή είναι True. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Οι πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Η έγκυρη σημαία ιδιότητας. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου που θα επαληθευτεί· εάν δεν οριστεί, όλες οι σελίδες του εγγράφου θα επαληθευτούν για την πρώτη εμφάνιση (η ελάχιστη τιμή είναι 1). (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Οι επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Η θέση σχήματος στη διάταξη του εγγράφου που χρησιμοποιείται για την επαλήθευση υπογραφών σε κεφαλίδες/υποσέλιδα. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

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

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `TextVerifyOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
