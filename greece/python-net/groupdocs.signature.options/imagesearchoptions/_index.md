---
title: "Κλάση ImageSearchOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές εικόνας."
type: docs
url: /el/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Αντιπροσωπεύει τις επιλογές αναζήτησης για υπογραφές εικόνας.

Μάθετε περισσότερα:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

Ο τύπος ImageSearchOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSearchOptions με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | Το μέγιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης, σε bytes. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | Το ελάχιστο μέγεθος των δεδομένων εικόνας, σε bytes, που θα ληφθεί υπόψη κατά τη διάρκεια μιας αναζήτησης. Μια μη μηδενική τιμή καθορίζει το ελάχιστο μέγεθος· η προεπιλογή είναι μηδέν, που δεν επηρεάζει το αποτέλεσμα της αναζήτησης. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | Η σημαία που καθορίζει αν επιστρέφεται το περιεχόμενο εικόνας μιας υπογραφής. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας όταν η ιδιότητα `return_content` είναι ενεργοποιημένη. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Η σημαία που υποδεικνύει αν θα γίνει αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή είναι True. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για αναζήτηση (προαιρετικό). (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Οι επιλογές για καθορισμό σελίδων για αναζήτηση υπογραφών. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Η σημαία που υποδεικνύει αν θα επιστραφεί η θέση του σχήματος στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Η σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως `IsSignature`. Από προεπιλογή η τιμή είναι `False`, που υποδεικνύει ότι επιστρέφονται όλες οι υπογραφές που ταιριάζουν στα καθορισμένα κριτήρια. (κληρονομείται από [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
