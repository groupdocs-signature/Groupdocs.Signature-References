---
title: "JpegSaveOptions κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές αποθήκευσης JPEG για έγγραφα εικόνας."
type: docs
url: /el/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Αντιπροσωπεύει τις επιλογές αποθήκευσης JPEG για έγγραφα εικόνας.

Ο τύπος JpegSaveOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Αρχικοποιεί το JpegSaveOptions με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Ο αριθμός των bit ανά κανάλι για μια μη-συμπιεσμένη JPEG εικόνα. Οι υποστηριζόμενες τιμές είναι από 2 έως 8 bit ανά κανάλι. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Ο τύπος χρώματος για την εικόνα JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Το σχόλιο αρχείου JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Ο τύπος συμπίεσης. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | Η ποιότητα εικόνας. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Η λειτουργία στρογγυλοποίησης δείγματος που χρησιμοποιείται για να προσαρμόσει μια τιμή 8-bit σε μια τιμή n-bit του `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Η σημαία που καθορίζει εάν θα προστεθεί αυτόματα μια επέκταση όταν λείπει στη διαδρομή του αρχείου εξόδου. Η προεπιλεγμένη τιμή είναι False. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Η μορφή αρχείου του υπογεγραμμένου εγγράφου. (κληρονομείται από [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Η σημαία που υποδεικνύει εάν θα αντικατασταθεί ένα υπάρχον αρχείο με το νέο αρχείο εξόδου. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για την προστασία του αποθηκευμένου υπογεγραμμένου εγγράφου. Δεν υποστηρίζεται για έγγραφα εικόνας. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Η σημαία που υποδεικνύει εάν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) κατά την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο. Η προεπιλεγμένη τιμή είναι True. Δεν υποστηρίζεται για έγγραφα εικόνας. (κληρονομείται από [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
