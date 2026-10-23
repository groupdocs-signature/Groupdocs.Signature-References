---
title: "Κλάση PdfDigitalSignature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις ιδιότητες ψηφιακής υπογραφής PDF."
type: docs
url: /el/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

Αντιπροσωπεύει τις ιδιότητες ψηφιακής υπογραφής PDF.

Ο τύπος PdfDigitalSignature εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Αρχικοποιεί μια ψηφιακή υπογραφή PDF χωρίς πιστοποιητικό. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Αρχικοποιεί μια ψηφιακή υπογραφή PDF χρησιμοποιώντας το καθορισμένο αποθηκευτικό χώρο X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το αποθηκευτικό χώρο. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Αρχικοποιεί μια ψηφιακή υπογραφή PDF χρησιμοποιώντας το καθορισμένο αποθηκευτικό χώρο X509 και το δείκτη πιστοποιίου. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Αρχικοποιεί μια ψηφιακή υπογραφή PDF με το καθορισμένο πιστοποιητικό X509. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | Κλωνοποιεί το στιγμιότυπο της ψηφιακής υπογραφής PDF. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | Συγκρίνει τις ιδιότητες της υπογραφής για να καθορίσει την ισότητα. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | Αντικαθιστά τη μέθοδο GetHashCode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Φορτώνει ψηφιακές υπογραφές από όλα τα αποθηκευτικά χώροι πιστοποιητικών X509 του συστήματος. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | Οι πληροφορίες επικοινωνίας που παρέχονται από τον υπογράφοντα για να επιτρέπουν στον παραλήπτη να επαληθεύσει την υπογραφή, π.χ., έναν αριθμό τηλεφώνου. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | Ο λόγος για την υπογραφή, όπως (συμφωνώ). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | Η σημαία που αναγκάζει τις ιδιότητες της υπογραφής να εμφανίζονται ή να κρύβονται· όταν είναι true, το πεδίο υπογραφής χρησιμοποιεί προκαθορισμένη μορφή εμφάνισης (π.χ., `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) και έχει προεπιλογή True. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | Η χρονική σήμανση για μια ψηφιακή υπογραφή PDF. Η προεπιλεγμένη τιμή είναι None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | Ο τύπος της ψηφιακής υπογραφής PDF. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Το πιστοποιητικό X509 που σχετίζεται με την ψηφιακή υπογραφή. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Το προσαρμοσμένο όνομα αποθήκης του πιστοποιητικού. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Η θέση αποθήκης του πιστοποιητικού. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Το όνομα αποθήκης του πιστοποιητικού. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Το σχόλιο σκοπού υπογραφής. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Η ημερομηνία δημιουργίας της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Η σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Το ύψος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Η σημαία που υποδεικνύει εάν αυτό το στοιχείο αντιπροσωπεύει υπογραφή (`True`) ή περιεχόμενο εγγράφου (`False`). (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Η αριστερή θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Η ημερομηνία τροποποίησης της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Ο αριθμός σελίδας όπου βρέθηκε η υπογραφή. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Η ώρα που υπογράφηκε το έγγραφο. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Το μοναδικό αναγνωριστικό της υπογραφής, που χρησιμοποιείται για την τροποποίηση της υπογραφής στο έγγραφο μέσω λειτουργιών ενημέρωσης ή διαγραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Ο τύπος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Το αποτύπωμα ενός πιστοποιητικού. (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Η άνω θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Το πλάτος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Ο τύπος XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (κληρονομείται από [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
