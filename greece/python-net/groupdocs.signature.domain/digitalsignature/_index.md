---
title: "Κλάση DigitalSignature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η κλάση περιέχει ιδιότητες ψηφιακής υπογραφής."
type: docs
url: /el/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

Η κλάση περιέχει ιδιότητες ψηφιακής υπογραφής.

Ο τύπος DigitalSignature εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Αρχικοποιεί μια ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Αρχικοποιεί μια ψηφιακή υπογραφή με γνωστό αναγνωριστικό υπογραφής. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Αρχικοποιεί ένα DigitalSignature χρησιμοποιώντας το πρώτο πιστοποιητικό από το καθορισμένο κατάστημα X509. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Αρχικοποιεί ένα DigitalSignature βάσει του καθορισμένου καταστήματος X509 και του δείκτη πιστοποιητικού. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Αρχικοποιεί μια ψηφιακή υπογραφή με το καθορισμένο πιστοποιητικό. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Κλωνοποιεί το στιγμιότυπο της υπογραφής barcode. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Συγκρίνει αυτήν την υπογραφή με άλλη υπογραφή για ισότητα. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για την ψηφιακή υπογραφή. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Φορτώνει ψηφιακές υπογραφές από όλα τα συστημικά καταστήματα πιστοποιητικών X509. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Φορτώνει ψηφιακές υπογραφές από μια αποθήκη πιστοποιητικών. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Φορτώνει ψηφιακές υπογραφές από μια αποθήκη πιστοποιητικών. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Φορτώνει ψηφιακές υπογραφές από μια αποθήκη ψηφιακών πιστοποιητικών τοποθετημένη σε συγκεκριμένη θέση. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Φορτώνει ψηφιακές υπογραφές από μια αποθήκη ψηφιακών πιστοποιητικών τοποθετημένη σε συγκεκριμένη θέση. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Το πιστοποιητικό X509 που σχετίζεται με την ψηφιακή υπογραφή. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Το προσαρμοσμένο όνομα αποθήκης του πιστοποιητικού. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Η θέση αποθήκευσης του πιστοποιητικού. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Το όνομα αποθήκευσης του πιστοποιητικού. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Το σχόλιο σκοπού υπογραφής. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Η ώρα που υπογράφηκε το έγγραφο. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Το αποτύπωμα ενός πιστοποιητικού. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Ο τύπος XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Η ημερομηνία δημιουργίας της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Η σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Το ύψος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Η σημαία που υποδεικνύει εάν αυτό το στοιχείο αντιπροσωπεύει υπογραφή (`True`) ή περιεχόμενο εγγράφου (`False`). (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Η αριστερή θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Η ημερομηνία τροποποίησης της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Ο αριθμός σελίδας όπου βρέθηκε η υπογραφή. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Το μοναδικό αναγνωριστικό της υπογραφής, που χρησιμοποιείται για την τροποποίηση της υπογραφής στο έγγραφο μέσω λειτουργιών ενημέρωσης ή διαγραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Ο τύπος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Η άνω θέση της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Το πλάτος της υπογραφής. (κληρονομείται από [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
