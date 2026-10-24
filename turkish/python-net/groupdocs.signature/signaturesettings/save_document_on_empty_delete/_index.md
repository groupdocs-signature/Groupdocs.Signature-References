---
title: "save_document_on_empty_delete özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Delete yöntemi kaldırılacak etkilenmiş imza bulunmadığında kaynak belgenin yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak."
type: docs
url: /tr/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Delete yöntemi kaldırılacak etkilenmiş imza bulunmadığında kaynak belgenin yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak.

True (varsayılan) olduğunda, belge hiçbir imza kaldırılmamış olsa bile tarih ve işlem türü içeren bir geçmiş kaydıyla kaydedilir; False olduğunda, kaynak belge değişmeden kalır.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
