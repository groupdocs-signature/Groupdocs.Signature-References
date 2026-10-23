---
title: "ιδιότητα return_content_type"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας όταν η ιδιότητα returncontent είναι ενεργοποιημένη."
type: docs
url: /el/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Ο τύπος αρχείου του επιστρεφόμενου περιεχομένου εικόνας όταν η ιδιότητα `return_content` είναι ενεργοποιημένη.

Εάν δεν οριστεί (προεπιλογή `None`), το περιεχόμενο της εικόνας επιστρέφεται στην αρχική του μορφή όπως ορίζεται από [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Οι υποστηριζόμενες τιμές είναι [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), και [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Εάν δοθεί μη υποστηριζόμενη μορφή, επιστρέφεται η αρχική μορφή.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
