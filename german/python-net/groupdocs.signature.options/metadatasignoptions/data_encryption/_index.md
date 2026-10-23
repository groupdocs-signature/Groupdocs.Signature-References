---
title: "data_encryption Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Implementierung von IDataEncryption wird verwendet, um alle Metadaten‑Signaturen in dieser Optionssammlung zu verschlüsseln."
type: docs
url: /de/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

Die Implementierung von [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) wird verwendet, um alle Metadaten‑Signaturen in dieser Optionssammlung zu verschlüsseln.

Wenn gesetzt, verwenden alle hinzugefügten Signaturen standardmäßig diese Verschlüsselung, es sei denn, sie haben eine eigene DataEncryption zugewiesen.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### Siehe auch
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
