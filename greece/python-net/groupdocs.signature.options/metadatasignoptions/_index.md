---
title: "Κλάση MetadataSignOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής μεταδεδομένων."
type: docs
url: /el/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής μεταδεδομένων.

Μάθετε περισσότερα

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

Ο τύπος MetadataSignOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MetadataSignOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | Αρχικοποιεί ένα νέο αντικείμενο του [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) με μεταδεδομένα. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Προσθέτει υπάρχον αντικείμενο MetadataSignature στη συλλογή. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Δημιουργεί ένα νέο ImageMetadataSignature με τα δοσμένα επιχειρήματα και το προσθέτει στη συλλογή. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Δημιουργεί ένα νέο PdfMetadataSignature με τα δοσμένα επιχειρήματα και το προσθέτει στη συλλογή. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | Η υλοποίηση του [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) χρησιμοποιείται για την κρυπτογράφηση όλων των υπογραφών μεταδεδομένων σε αυτή τη συλλογή επιλογών. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | Οι υπογραφές μεταδεδομένων που σχετίζονται με την υπογραφή. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Η υπογραφή θα τοποθετηθεί σε όλες τις σελίδες του εγγράφου. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Η πρόσθετη εμφάνιση της υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Ο τύπος εγγράφου των επιλογών υπογραφής (`DocumentType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Οι επεκτάσεις υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Ο αλγόριθμος κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για υπογραφή. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Οι επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Ο τύπος υπογραφής (`SignatureType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Η θέση Z-order της κειμενικής υπογραφής, η οποία καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
