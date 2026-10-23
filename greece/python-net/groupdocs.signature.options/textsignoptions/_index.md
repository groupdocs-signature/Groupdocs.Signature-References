---
title: "TextSignOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής Κειμένου."
type: docs
url: /el/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής Κειμένου.

Μάθετε περισσότερα

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Ο τύπος TextSignOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSignOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSignOptions με κείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Οι ρυθμίσεις φόντου της υπογραφής. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Οι ρυθμίσεις περιγράμματος. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Η γραμματοσειρά της υπογραφής. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Το χρώμα προσκηνίου της υπογραφής. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Ο τίτλος του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου. Μπορεί να χρησιμοποιηθεί μόνο όταν η `signature_implementation` ορίζεται σε `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Ο τύπος του πεδίου φόρμας όπου θα τοποθετηθεί η υπογραφή κειμένου. Αυτή η ιδιότητα ισχύει μόνο όταν το `signature_implementation` είναι ορισμένο σε `TextSignatureImplementation.FORM_FIELD` (δηλαδή, TextToFormField). Η προεπιλεγμένη τιμή είναι `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | Το ύψος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά). Η μονάδα καθορίζεται από την ιδιότητα `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | Η οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | Η αριστερή θέση X της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά όπως ορίζεται από την ιδιότητα `MeasureType` LocationMeasureType). Λειτουργεί εάν δεν έχει καθοριστεί οριζόντια στοίχιση. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες `left` και `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Ο χώρος μεταξύ της υπογραφής και των άκρων του εγγράφου. Ισχύει μόνο όταν έχει καθοριστεί οριζόντια ή κάθετη στοίχιση. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Ο τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για το περιθώριο. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Το εγγενές χαρακτηριστικό. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | Η γωνία περιστροφής της υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Η θέση σχήματος ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διατίθεται μόνο για έγγραφα Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Ο τύπος σχήματος για την τοποθέτηση κειμένου. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Το μοναδικό ID της υπογραφής, χρησιμοποιήσιμο στις επιλογές επαλήθευσης και υποστηρίζεται μόνο για έγγραφα PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Ο τύπος υλοποίησης υπογραφής κειμένου. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Η λειτουργία τέντωσης στη σελίδα του εγγράφου. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Το κείμενο της υπογραφής. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Η οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή, υποστηρίζεται μόνο για υλοποιήσεις υπογραφής Image και Annotation (δείτε την ιδιότητα `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Η κάθετη στοίχιση του κειμένου μέσα σε μια υπογραφή. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | Η άνω θέση Y της υπογραφής στη σελίδα του εγγράφου, εκφρασμένη σε μονάδες μέτρησης (pixel, ποσοστό ή χιλιοστά). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | Η διαφάνεια της υπογραφής, ένας δεκαδικός αριθμός μεταξύ 0.0 (αδιαφανής) και 1.0 (διαυγής). Η προεπιλογή είναι 0.0 (αδιαφανής). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | Η κάθετη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | Το πλάτος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά· δείτε τις ιδιότητες `MeasureType` `SizeMeasureType`). |
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
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν το `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
