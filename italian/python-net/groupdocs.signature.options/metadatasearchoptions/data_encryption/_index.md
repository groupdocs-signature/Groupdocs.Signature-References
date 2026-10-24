---
title: "proprietà data_encryption"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "L'implementazione di IDataEncryption utilizzata per decrittare tutte le firme dei metadati all'interno di questa raccolta di opzioni."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

L'implementazione di [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizzata per decrittare tutte le firme di metadati all'interno di questa raccolta di opzioni.

Se impostato, tutte le firme trovate utilizzeranno questa crittografia per impostazione predefinita, a meno che non abbiano una propria DataEncryption assegnata.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### Vedi anche
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
