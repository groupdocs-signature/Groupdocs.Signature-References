---
title: "Κλάση SignatureSettings"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Signature."
type: docs
url: /el/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Αντιπροσωπεύει τις ρυθμίσεις για την προσαρμογή της συμπεριφοράς του [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Ο τύπος SignatureSettings εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Αρχικοποιεί ένα προεπιλεγμένο αντικείμενο SignatureSettings με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Αρχικοποιεί ένα προεπιλεγμένο αντικείμενο SignatureSettings με την υλοποίηση του Logger. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Η προεπιλεγμένη πολιτισμική ρύθμιση που χρησιμοποιείται κατά την επεξεργασία εγγράφων. Η προεπιλεγμένη τιμή είναι "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Η σημαία που υποδεικνύει εάν οι τυπικές υπογραφές μεταδεδομένων εγγράφου όπως Συγγραφέας, Ιδιοκτήτης, ημερομηνία δημιουργίας και ημερομηνία τροποποίησης περιλαμβάνονται στη λίστα μεταδεδομένων. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Οι σημαίες επιπέδου καταγραφής που καθορίζουν ποιοι τύποι μηνυμάτων περνούν στο [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Σφάλματα, Προειδοποιήσεις, Ιχνηλάσεις). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Η σημαία που καθορίζει εάν το αρχικό έγγραφο αποθηκεύεται ξανά όταν η μέθοδος Delete δεν έχει υπογραφές που επηρεάζονται για αφαίρεση. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Η σημαία που καθορίζει εάν το αρχικό έγγραφο αποθηκεύεται ξανά όταν η μέθοδος `Update` δεν έχει υπογραφές για ενημέρωση. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Η σημαία που καθορίζει εάν οι διαγραμμένες υπογραφές περιλαμβάνονται στο αποτέλεσμα πληροφοριών εγγράφου. Κάθε [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) έχει μια σημαία `Deleted` για να υποδεικνύει αν έχει διαγραφεί. |

### Δείτε επίσης
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
