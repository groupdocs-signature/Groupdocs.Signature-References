---
title: "Κλάση ImageSignOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής εικόνας."
type: docs
url: /el/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής εικόνας.

Μάθετε περισσότερα:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Ο τύπος ImageSignOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Αρχικοποιεί το ImageSignOptions με αρχείο εικόνας. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Αρχικοποιεί ένα νέο αντικείμενο ImageSignOptions με ροή εικόνας. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Καθαρίζει εσωτερικούς πόρους. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Δημιουργεί ένα νέο αντικείμενο ImageSignOptions με προκαθορισμένη εικόνα από μια συμβολοσειρά Base64. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Οι ρυθμίσεις περιγράμματος για την υπογραφή εικόνας. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | Το ύψος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, ποσοστά ή χιλιοστά· δείτε `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | Η οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Η διαδρομή αρχείου της εικόνας υπογραφής, χρησιμοποιείται μόνο εάν δεν έχει οριστεί `image_stream`. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Η ροή εικόνας υπογραφής. Εάν οριστεί, χρησιμοποιείται πάντα αντί για ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | Η αριστερή θέση X της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, ποσοστά ή χιλιοστά). Λειτουργεί εάν δεν έχει οριστεί η οριζόντια στοίχιση. Δείτε `MeasureType` για τον τύπο μέτρησης θέσης. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Ο τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για τις ιδιότητες αριστερά και πάνω. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Ο χώρος μεταξύ της υπογραφής και των άκρων του εγγράφου. Λειτουργεί μόνο εάν έχουν οριστεί η οριζόντια ή η κάθετη στοίχιση. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Ο τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για το περιθώριο. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Το ορθογώνιο της περιοχής για την τοποθέτηση της εικόνας στο έγγραφο. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | Η γωνία περιστροφής της υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Η θέση σχήματος ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διατίθεται μόνο για έγγραφα Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Ο τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Η λειτουργία τέντωσης στη σελίδα του εγγράφου. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | Η άνω θέση Y της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, ποσοστά ή χιλιοστά) όπως ορίζεται από `MeasureType` LocationMeasureType. Λειτουργεί εάν δεν έχει οριστεί η κάθετη στοίχιση. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | Η διαφάνεια της υπογραφής, κυμαίνεται από 0,0 (αδιαφανής) έως 1,0 (διαυγής), η προεπιλογή είναι 0 (αδιαφανής). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | Η κάθετη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | Το πλάτος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, ποσοστά ή χιλιοστά `MeasureType` size measure type). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές υπογραφής εικόνας με το αρχείο εικόνας
        options = ImageSignOptions("signature.jpg")
        # Ορίστε τη θέση και το μέγεθος της υπογραφής
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
