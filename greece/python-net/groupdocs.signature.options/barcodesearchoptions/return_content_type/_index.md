---
title: "ιδιότητα return_content_type"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας για μια υπογραφή Barcode όταν η ιδιότητα returncontent είναι ενεργοποιημένη."
type: docs
url: /el/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας για μια υπογραφή Barcode όταν η ιδιότητα `return_content` είναι ενεργοποιημένη.

Από προεπιλογή είναι None, το οποίο επιστρέφει την εικόνα barcode στη αρχική της μορφή όπως ορίζεται από [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Οι υποστηριζόμενες τιμές είναι [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), και [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Εάν δοθεί τιμή διαφορετική από αυτές, η εικόνα θα επιστραφεί σε μορφή PNG.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
