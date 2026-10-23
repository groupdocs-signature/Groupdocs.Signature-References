---
title: "Κλάση TextSearchOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές Κειμένου."
type: docs
url: /el/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές Κειμένου.

Μάθετε περισσότερα:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

Ο τύπος TextSearchOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με μια τιμή κειμένου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Ο τύπος αντιστοίχισης κειμένου που χρησιμοποιείται για αναζήτηση. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | Η υλοποίηση της υπογραφής κειμένου για αναζήτηση. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | Το κείμενο της υπογραφής που πρέπει να ταιριάζει κατά την αναζήτηση. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Η σημαία που υποδεικνύει αν θα γίνει αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή είναι True. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για αναζήτηση (προαιρετικό). (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Οι επιλογές για καθορισμό σελίδων για αναζήτηση υπογραφών. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Η σημαία που υποδεικνύει αν θα επιστραφεί η θέση του σχήματος στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Η σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως `IsSignature`. Από προεπιλογή η τιμή είναι `False`, που υποδεικνύει ότι επιστρέφονται όλες οι υπογραφές που ταιριάζουν στα καθορισμένα κριτήρια. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `TextSearchOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
