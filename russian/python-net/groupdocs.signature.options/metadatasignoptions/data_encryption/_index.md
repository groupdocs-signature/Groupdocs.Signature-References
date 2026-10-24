---
title: "свойство data_encryption"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Реализация IDataEncryption, используемая для шифрования всех метаданных подписей в этой коллекции параметров."
type: docs
url: /ru/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

Реализация [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) используется для шифрования всех подписей метаданных в этой коллекции параметров.

Если установлено, все добавленные подписи будут использовать это шифрование по умолчанию, если у них не назначено собственное DataEncryption.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### См. также
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
