---
title: "Κλάση DigitalVerifyOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Διατηρεί τις επιλογές για επαλήθευση της ψηφιακής υπογραφής ενός εγγράφου."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Διατηρεί τις επιλογές για επαλήθευση της ψηφιακής υπογραφής ενός εγγράφου.

Μάθετε περισσότερα

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Ο τύπος DigitalVerifyOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με προεπιλεγμένες τιμές. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με τη δοσμένη διαδρομή αρχείου ψηφιακού πιστοποιητικού. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Αρχικοποιεί ένα αντικείμενο DigitalVerifyOptions με το δοσμένο ρεύμα πιστοποιητικού. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Το πιστοποιητικό X509Certificate2 που λαμβάνεται από τη διαδρομή αρχείου ή το ρεύμα του πιστοποιητικού. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Η διαδρομή αρχείου του ψηφιακού πιστοποιητικού. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Το ρεύμα του ψηφιακού πιστοποιητικού. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Τα σχόλια της ψηφιακής υπογραφής για επαλήθευση. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Η επαφή της υπογραφής για επαλήθευση. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Το όνομα εκδότη του πιστοποιητικού για επαλήθευση. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Η θέση της υπογραφής για επαλήθευση. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Ο κωδικός πρόσβασης του ψηφιακού πιστοποιητικού εάν απαιτείται. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Ο λόγος της ψηφιακής υπογραφής για επαλήθευση. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Η έναρξη του εύρους ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Μια τιμή None θα αγνοηθεί. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Το τέλος του εύρους ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Μια τιμή null θα αγνοηθεί. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Το διακριτικό όνομα του υποκειμένου του πιστοποιητικού για επαλήθευση· η επαλήθευση ελέγχει αν το όνομα υποκειμένου της υπογραφής περιέχει ή ισούται με αυτήν την τιμή με διάκριση πεζών‑κεφαλαίων. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Η σημαία που υποδεικνύει εάν κάθε σελίδα του εγγράφου πρέπει να επαληθευτεί. Από προεπιλογή η τιμή είναι True. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Οι πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Η έγκυρη σημαία ιδιότητας. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Ο αριθμός σελίδας του εγγράφου που θα επαληθευτεί· εάν δεν οριστεί, όλες οι σελίδες του εγγράφου θα επαληθευτούν για την πρώτη εμφάνιση (η ελάχιστη τιμή είναι 1). (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Οι επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Η θέση σχήματος στη διάταξη του εγγράφου που χρησιμοποιείται για την επαλήθευση υπογραφών σε κεφαλίδες/υποσέλιδα. (κληρονομείται από [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
