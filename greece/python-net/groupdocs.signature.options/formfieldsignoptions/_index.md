---
title: "FormFieldSignOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές υπογραφής FormField για έγγραφα PDF."
type: docs
url: /el/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Αναπαριστά τις επιλογές υπογραφής FormField για έγγραφα PDF.

Παρέχει επιλογές για τη δημιουργία ή ενημέρωση υπογραφών πεδίων φόρμας σε αρχεία PDF.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

Ο τύπος FormFieldSignOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfFormFieldSignOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfFormFieldSignOptions με υπογραφή FormField. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Το ύψος της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixel, ποσοστά ή χιλιοστά· δείτε `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Η οριζόντια στοίχιση της εικόνας σε μια σελίδα εγγράφου. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Η αριστερή θέση X της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixel, ποσοστά ή χιλιοστά). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Το προεπιλεγμένο κενό μεταξύ της εικόνας και των άκρων του εγγράφου (εφαρμόζεται όταν έχει οριστεί οριζόντια ή κάθετη στοίχιση). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Ο τύπος μέτρησης περιθωρίου (pixel, ποσοστά ή χιλιοστά). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Η γωνία περιστροφής, μετρική δεξιόστροφα. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | Το FormField της υπογραφής. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Η λειτουργία τέντωσης στη σελίδα του εγγράφου. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Η κορυφαία θέση Y της περιοχής υπογραφής στη σελίδα του εγγράφου σε μονάδες μέτρησης (pixel, ποσοστά ή χιλιοστά). Δείτε το `MeasureType` για τον τύπο μέτρησης θέσης. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Η διαφάνεια της υπογραφής πεδίου φόρμας. Η τιμή κυμαίνεται από 0.0 έως 1.0, με προεπιλογή το 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Η κάθετη στοίχιση της εικόνας σε μια σελίδα εγγράφου. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Το πλάτος της περιοχής υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά· δείτε `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Η υπογραφή θα τοποθετηθεί σε όλες τις σελίδες του εγγράφου. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Η πρόσθετη εμφάνιση της υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Οι ρυθμίσεις φόντου της υπογραφής. (κληρονομούνται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Οι ρυθμίσεις περιγράμματος. (κληρονομούνται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Ο τύπος εγγράφου των επιλογών υπογραφής (`DocumentType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Οι επεκτάσεις υπογραφής. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Η γραμματοσειρά της υπογραφής. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Το χρώμα προσκηνίου της υπογραφής. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Ο τίτλος του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου. Μπορεί να χρησιμοποιηθεί μόνο όταν η `signature_implementation` είναι ορισμένη σε `TextSignatureImplementation.FORM_FIELD`. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Ο τύπος του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου. Αυτή η ιδιότητα εφαρμόζεται μόνο όταν η `signature_implementation` είναι ορισμένη σε `TextSignatureImplementation.FORM_FIELD` (π.χ., TextToFormField). Η προεπιλεγμένη τιμή είναι `FormTextFieldType.ALL_TEXT_TYPES`. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Ο αλγόριθμος κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Το εγγενές χαρακτηριστικό. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου για υπογραφή. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Οι επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Η θέση του σχήματος ορίζει πού θα εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Ο τύπος σχήματος για την τοποθέτηση κειμένου. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Το μοναδικό ID της υπογραφής, χρήσιμο στις επιλογές επαλήθευσης και υποστηρίζεται μόνο για έγγραφα PDF. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Ο τύπος υλοποίησης υπογραφής κειμένου. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Ο τύπος υπογραφής (`SignatureType`). (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Το κείμενο της υπογραφής. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Η οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή, υποστηρίζεται μόνο για υλοποιήσεις υπογραφών εικόνας και σχολιασμού (δείτε την ιδιότητα `TextSignatureImplementation` SignatureImplementation). (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Η κάθετη στοίχιση του κειμένου μέσα σε μια υπογραφή. (κληρονομείται από [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Η θέση Z-order της κειμενικής υπογραφής, η οποία καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. (κληρονομείται από [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
