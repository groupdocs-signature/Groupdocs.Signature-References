---
title: "Κλάση DigitalSignOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές ψηφιακής υπογραφής."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Αναπαριστά τις επιλογές ψηφιακής υπογραφής.

Μάθετε περισσότερα

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Ο τύπος DigitalSignOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με αρχείο πιστοποιητικού. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με ροή πιστοποιητικού. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας εμφάνισης. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Αρχικοποιεί ένα νέο στιγμιότυπο του DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας εμφάνισης. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Αρχικοποιεί ένα νέο στιγμιότυπο του DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας εμφάνισης. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Αρχικοποιεί ένα νέο στιγμιότυπο DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας εμφάνισης. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Καθαρίζει εσωτερικούς πόρους. (κληρονομείται από [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Δημιουργεί ένα νέο στιγμιότυπο ImageSignOptions με προεπιλεγμένη εικόνα από συμβολοσειρά Base64. (κληρονομείται από [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Η σημαία που επιτρέπει την υπογραφή με ένα πιστοποιητικό του οποίου η περίοδος ισχύος έχει λήξει. Η προεπιλεγμένη τιμή είναι False· η υπογραφή με ληγμένο πιστοποιητικό προκαλεί την εξαίρεση `GroupDocsSignatureException` και το έγγραφο δεν υπογράφεται. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Η σημαία που επιτρέπει την υπογραφή με ένα πιστοποιητικό του οποίου η περίοδος ισχύος δεν έχει ξεκινήσει ακόμη. Η προεπιλεγμένη τιμή είναι False· η υπογραφή με τέτοιο πιστοποιητικό προκαλεί την εξαίρεση `GroupDocsSignatureException` και το έγγραφο δεν υπογράφεται. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Η διαδρομή αρχείου του ψηφιακού πιστοποιητικού. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Η ροή του ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί για CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Η επαφή της υπογραφής. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Η προσαρμοσμένη συνάρτηση κατακερματισμού για υπογραφή που χρησιμοποιείται για την υπογραφή του εγγράφου, επιτρέποντας στους χρήστες να υλοποιήσουν τη δική τους λογική ψηφιακής υπογραφής. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Το ύψος της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixels, percents, or millimeters; see `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Η οριζόντια στοίχιση της εικόνας σε μια σελίδα εγγράφου. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Η αριστερή θέση X της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixels, percents, or millimeters as defined by `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | Η θέση της υπογραφής. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Ο τύπος μέτρησης (pixels, percents or millimeters) για τις ιδιότητες αριστερά και πάνω. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Ο χώρος που καθορίζεται εξ ορισμού μεταξύ της εικόνας και των άκρων του εγγράφου (ισχύει όταν έχει καθοριστεί οριζόντια ή κάθετη στοίχιση). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Ο τύπος μέτρησης περιθωρίου (pixel, ποσοστά ή χιλιοστά). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Ο κωδικός πρόσβασης του ψηφιακού πιστοποιητικού. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Ο λόγος της υπογραφής. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Η γωνία περιστροφής δεξιόστροφα. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Οι ιδιότητες ψηφιακής υπογραφής για το έγγραφο. Για υπογραφή PDF, μπορούν να οριστούν προχωρημένες ιδιότητες χρησιμοποιώντας ένα στιγμιότυπο του [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Η λειτουργία τέντωσης στη σελίδα του εγγράφου. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Η πάνω θέση Y της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixels, percents, or millimeters; see `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Η διαφάνεια της ψηφιακής υπογραφής, κυμαινόμενη από 0.0 έως 1.0. Η προεπιλογή είναι 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Η σημαία επαλήθευσης LTV (Long Term Validation). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Η κάθετη στοίχιση της εικόνας σε μια σελίδα εγγράφου. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | Η ορατότητα της υπογραφής. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Το πλάτος της περιοχής υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, percents, or millimeters). Η μονάδα μέτρησης ορίζεται από το `MeasureType` μέσω της ιδιότητας SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Ο τύπος XAdES. Η προεπιλεγμένη τιμή είναι None (XAdES is off). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Η υπογραφή θα τοποθετηθεί σε όλες τις σελίδες του εγγράφου. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Η πρόσθετη εμφάνιση της υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Οι ρυθμίσεις περιγράμματος για την υπογραφή εικόνας. (κληρονομείται από το [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Ο τύπος εγγράφου των επιλογών υπογραφής (`DocumentType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Οι επεκτάσεις υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Ο αλγόριθμος κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Η διαδρομή αρχείου της εικόνας υπογραφής, χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί `image_stream`. (κληρονομείται από το [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Η ροή εικόνας υπογραφής. Εάν καθοριστεί, χρησιμοποιείται πάντα αντί για ImageFilePath. (κληρονομείται από το [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για υπογραφή. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Οι επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Το ορθογώνιο της περιοχής για την τοποθέτηση της εικόνας στο έγγραφο. (κληρονομείται από το [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Η θέση σχήματος καθορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διατίθεται μόνο για έγγραφα Word. (κληρονομείται από το [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Ο τύπος υπογραφής (`SignatureType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Η θέση Z-order της κειμενικής υπογραφής, η οποία καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Περάστε το πιστοποιητικό και την εικόνα εμφάνισης στον κατασκευαστή
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Εμφανίστε την υπογραφή στη σελίδα, σε αυτή τη θέση και μέγεθος
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Πληροφορίες αποθηκευμένες στην υπογραφή
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
