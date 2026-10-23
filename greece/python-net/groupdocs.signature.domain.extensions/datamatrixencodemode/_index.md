---
title: "Κλάση DataMatrixEncodeMode"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Enum DataMatrixEncodeMode — GroupDocs.Signature for Python μέσω .NET API αναφορά."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Ο τύπος DataMatrixEncodeMode εκθέτει τα ακόλουθα μέλη:

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Αυτόματη επιλογή της βέλτιστης λειτουργίας κωδικοποίησης για κωδικοποίηση DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Κωδικοποίηση τιμών 8 bit |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Κωδικοποίηση με την κωδικοποίηση που καθορίζεται στο BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Χρησιμοποιεί κωδικοποίηση C40. Κωδικοποιεί αλφαριθμητικά κεφαλαία, πεζά και ειδικούς χαρακτήρες |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Χρησιμοποιεί κωδικοποίηση κειμένου. Κωδικοποιεί αλφαριθμητικά πεζά, κεφαλαία και ειδικούς χαρακτήρες. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία, κεφαλαία γράμματα και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζά γράμματα. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή σχήματος κωδικοποίησης στο code-text. Μορφή : \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Τα επιτρεπόμενα σχήματα κωδικοποίησης είναι: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Παράδειγμα εκτεταμένου code-text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" Όλες οι ανάποδες κάθετες (\\) πρέπει να διπλασιαστούν στο κείμενο. |

### Δείτε επίσης
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
