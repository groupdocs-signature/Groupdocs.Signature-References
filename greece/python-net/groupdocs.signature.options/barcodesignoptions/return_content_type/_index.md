---
title: "ιδιότητα return_content_type"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής Barcode όταν η ιδιότητα returncontent είναι ενεργοποιημένη."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής Barcode όταν η ιδιότητα `return_content` είναι ενεργοποιημένη.

Από προεπιλογή ορίζεται σε `None`, που σημαίνει ότι το περιεχόμενο της εικόνας Barcode επιστρέφεται στην αρχική του μορφή. Η μορφή εικόνας καθορίζεται από [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Οι υποστηριζόμενες τιμές είναι [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), και [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Εάν δοθεί μορφή που δεν υποστηρίζεται, το περιεχόμενο της εικόνας Barcode θα επιστραφεί σε μορφή PNG.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
