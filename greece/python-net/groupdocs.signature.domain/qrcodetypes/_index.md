---
title: "Κλάση QrCodeTypes"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Το δοχείο τύπων QR code."
type: docs
url: /el/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Το δοχείο τύπων QR code.

Ο τύπος QrCodeTypes εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Αναλύει ένα όνομα τύπου QR code και επιστρέφει το αντίστοιχο αντικείμενο QRCodeType. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Επιστρέφει τον τύπο QRCode που ταιριάζει με το δοσμένο όνομα τύπου ανάλυσης, ή None εάν το όνομα είναι άγνωστο. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Όλοι οι τύποι QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Αντικείμενο τύπου Aztec QR-Code. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Αντικείμενο τύπου DataMatrix QR-Code. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Αντικείμενο τύπου QR QR-Code. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Αντικείμενο τύπου GS1 DataMatrix QR-Code. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Αντικείμενο τύπου GS1 QR-Code. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Αντικείμενο τύπου HIBC LIC QR-Code. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Αντικείμενο τύπου HIBC LIC Data Matrix QR-Code. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Αντικείμενο τύπου HIBC LIC Aztec QR-Code. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Αντικείμενο τύπου HIBC PAS QR-Code. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Αντικείμενο τύπου HIBC PAS Data Matrix QR-Code. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Αντικείμενο τύπου HIBC PAS Aztec QR-Code. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Αντικείμενο τύπου Han Xin QR-Code. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Αντικείμενο τύπου GS1 Han Xin QR-Code. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Αντικείμενο τύπου RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Αντικείμενο τύπου MicroQR. |

### Παράδειγμα

```python
from groupdocs.signature.domain import QrCodeTypes

# Χρησιμοποιήστε την απαρίθμηση τύπων QR code όταν δημιουργείτε επιλογές υπογραφής
print(QrCodeTypes.QR)
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
