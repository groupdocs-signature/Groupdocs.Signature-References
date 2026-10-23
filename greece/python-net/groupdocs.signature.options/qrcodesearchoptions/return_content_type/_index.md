---
title: "ιδιότητα return_content_type"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα returncontent είναι ενεργοποιημένη."
type: docs
url: /el/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα `return_content` είναι ενεργοποιημένη.

Από προεπιλογή είναι ορισμένο σε `None`, το οποίο επιστρέφει το περιεχόμενο εικόνας QR-Code στην αρχική του μορφή. Η μορφή εικόνας καθορίζεται στο [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). Οι υποστηριζόμενες τιμές είναι [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), και [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Εάν δοθεί μη υποστηριζόμενη μορφή, το περιεχόμενο εικόνας QR-Code επιστρέφεται ως PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Δείτε επίσης
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
