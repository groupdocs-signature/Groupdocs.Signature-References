---
title: "log_level özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "SignatureSettings.Logger'a iletilen mesaj türlerini belirleyen log seviyesi bayrakları."
type: docs
url: /tr/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Hangi tür mesajların [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) adresine iletileceğini belirleyen günlük seviyesi bayrakları.

Değer, birleştirilebilen `LogLevel` bayraklarından oluşan bir kümedir, örneğin `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` hiçbir şey kaydetmez. Varsayılan `LogLevel.All`'dır: hatalar, uyarılar ve izlemeler.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
