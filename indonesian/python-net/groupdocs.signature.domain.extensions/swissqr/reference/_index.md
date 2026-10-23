---
title: "Properti reference"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Referensi pembayaran kreditor."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Referensi pembayaran kreditor.

Wajib untuk IBAN SwissQR (IBAN dalam rentang CHxx30000xxxxxx hingga CHxx31999xxxxx). Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai format referensi ISR) atau referensi kreditor yang valid menurut ISO 11649 (\"RFxxxx\"). Kedua-duanya dapat berisi spasi untuk format.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Lihat Juga
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
