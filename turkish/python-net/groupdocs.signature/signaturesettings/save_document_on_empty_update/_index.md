---
title: "save_document_on_empty_update özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Kaynak belgenin, Update yöntemi güncellenecek imza olmadığında yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak."
type: docs
url: /tr/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

`Update` yöntemi güncellenecek imza bulunmadığında kaynak belgenin yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak.

True (varsayılan) olarak ayarlanırsa, belge hiçbir imza güncellenmemiş olsa bile ilgili bir tarih ve işlem türü içeren bir geçmiş işlem kaydıyla kaydedilir. False olarak ayarlandığında, kaynak belge hiç değiştirilemez.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
