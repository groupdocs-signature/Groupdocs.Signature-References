---
title: "Κλάση BarcodeSearchOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές αναζήτησης για υπογραφές Barcode."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Αναπαριστά τις επιλογές αναζήτησης για υπογραφές Barcode.

Μάθετε περισσότερα:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

Ο τύπος BarcodeSearchOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με τιμή τύπου κωδικοποίησης. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSearchOptions με τιμές τύπου κωδικοποίησης και κειμένου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | Ο τύπος κωδικοποίησης που χρησιμοποιείται για το φιλτράρισμα της αναζήτησης barcode· εάν δεν οριστεί, η αναζήτηση περιλαμβάνει όλους τους υποστηριζόμενους τύπους barcode. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | Ο τύπος αντιστοίχισης κειμένου barcode που χρησιμοποιείται για την αναζήτηση. Χρησιμοποιείται μόνο όταν έχει οριστεί η ιδιότητα `text`. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | Η σημαία που υποδεικνύει αν θα ανακτηθεί το περιεχόμενο εικόνας barcode μιας υπογραφής σε σελίδα εγγράφου. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας για μια υπογραφή Barcode όταν η ιδιότητα `return_content` είναι ενεργοποιημένη. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | Το κείμενο της υπογραφής barcode για αναζήτηση και αντιστοίχιση. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Η σημαία που υποδεικνύει αν θα γίνει αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή είναι True. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για αναζήτηση (προαιρετικό). (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Οι επιλογές για καθορισμό σελίδων για αναζήτηση υπογραφών. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Η σημαία που υποδεικνύει αν θα επιστραφεί η θέση του σχήματος στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Η σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως `IsSignature`. Από προεπιλογή η τιμή είναι `False`, που υποδεικνύει ότι επιστρέφονται όλες οι υπογραφές που ταιριάζουν στα καθορισμένα κριτήρια. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν το `BarcodeSearchOptions`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
