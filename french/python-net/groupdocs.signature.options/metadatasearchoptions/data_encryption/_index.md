---
title: "propriété data_encryption"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "L'implémentation de IDataEncryption utilisée pour déchiffrer toutes les signatures de métadonnées au sein de cette collection d'options."
type: docs
url: /fr/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

L'implémentation de [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilisée pour déchiffrer toutes les signatures de métadonnées au sein de cette collection d'options.

Si définie, toutes les signatures trouvées utiliseront ce chiffrement par défaut, sauf si elles ont leur propre DataEncryption assigné.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### Voir aussi
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
