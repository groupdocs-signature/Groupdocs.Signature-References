---
title: "Κλάση CertificateVerifyOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Διατηρεί τις επιλογές για επαλήθευση εγγράφων πιστοποιητικού."
type: docs
url: /el/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Διατηρεί τις επιλογές για επαλήθευση εγγράφων πιστοποιητικού.

Μάθετε περισσότερα

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Ο τύπος CertificateVerifyOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Αρχικοποιεί ένα νέο αντικείμενο CertificateVerifyOptions με το subject προς επαλήθευση. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | Η ιδιότητα υποδεικνύει αν το πιστοποιητικό έχει λήξει βάσει του αποτελέσματος επικύρωσης. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | Ο εκδότης του πιστοποιητικού προς επαλήθευση. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Ο τύπος αντιστοίχισης κειμένου που χρησιμοποιείται για την επαλήθευση. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Η διαδικασία επαλήθευσης πρέπει να παρέχει επικύρωση αλυσίδας X.509 χρησιμοποιώντας την βασική πολιτική επικύρωσης. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Ο σειριακός αριθμός του πιστοποιητικού προς επαλήθευση. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Το θέμα του πιστοποιητικού προς επαλήθευση. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | Το αποτύπωμα του πιστοποιητικού προς επαλήθευση. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Η σημαία που υποδεικνύει εάν κάθε σελίδα του εγγράφου πρέπει να επαληθευτεί. Από προεπιλογή η τιμή είναι True. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Οι πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Η έγκυρη σημαία ιδιότητας. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου που θα επαληθευτεί· εάν δεν οριστεί, όλες οι σελίδες του εγγράφου θα επαληθευτούν για την πρώτη εμφάνιση (η ελάχιστη τιμή είναι 1). (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Οι επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Η θέση σχήματος στη διάταξη του εγγράφου που χρησιμοποιείται για την επαλήθευση υπογραφών σε κεφαλίδες/υποσέλιδα. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
