---
title: "FormFieldSearchOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές αναζήτησης για υπογραφές πεδίων φόρμας."
type: docs
url: /el/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Αναπαριστά τις επιλογές αναζήτησης για υπογραφές πεδίων φόρμας.

Μάθετε περισσότερα:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Ο τύπος FormFieldSearchOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης FormFieldSearchOptions με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Το πρότυπο κανονικής έκφρασης που χρησιμοποιείται για την αντιστοίχιση του ονόματος υπογραφής πεδίου φόρμας κατά την αναζήτηση. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Ο τύπος της υπογραφής πεδίου φόρμας προς αναζήτηση. Η προεπιλεγμένη τιμή είναι None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Η τιμή της υπογραφής πεδίου φόρμας προς αναζήτηση. Η προεπιλεγμένη τιμή είναι None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Η σημαία που υποδεικνύει αν θα γίνει αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή είναι True. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για αναζήτηση (προαιρετικό). (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Οι επιλογές για καθορισμό σελίδων για αναζήτηση υπογραφών. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Η σημαία που υποδεικνύει αν θα επιστραφεί η θέση του σχήματος στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Η σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως `IsSignature`. Από προεπιλογή η τιμή είναι `False`, που υποδεικνύει ότι επιστρέφονται όλες οι υπογραφές που ταιριάζουν στα καθορισμένα κριτήρια. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Επιστρέψτε μόνο τα πεδία κειμένου με όνομα "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
