---
title: "referans özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Alacaklı ödeme referansı."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Alacaklı ödeme referansı.

SwissQR IBAN'ları için (CHxx30000xxxxxx ile CHxx31999xxxxx aralığındaki IBAN'lar) zorunludur. Belirtilirse, referans ya geçerli bir SwissQR referansı (ISR referans formuna karşılık gelen) ya da ISO 11649'a göre geçerli bir alacaklı referansı (\"RFxxxx\") olmalıdır. Her ikisi de biçimlendirme için boşluk içerebilir.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
