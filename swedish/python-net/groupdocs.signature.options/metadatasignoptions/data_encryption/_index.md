---
title: "data_encryption-egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Implementeringen av IDataEncryption används för att kryptera alla metadata‑signaturer i den här alternativsamlingen."
type: docs
url: /sv/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

Implementeringen av [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) som används för att kryptera alla metadata‑signaturer i denna alternativsamling.

Om den är inställd, kommer alla tillagda signaturer att använda denna kryptering som standard om de inte har sin egen DataEncryption tilldelad.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### Se även
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
