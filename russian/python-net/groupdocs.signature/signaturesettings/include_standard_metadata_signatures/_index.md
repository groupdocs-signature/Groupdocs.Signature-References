---
title: "include_standard_metadata_signatures свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, указывающий, включены ли стандартные подписи метаданных документа, такие как Автор, Владелец, дата создания и дата изменения, в список метаданных."
type: docs
url: /ru/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

Флаг, указывающий, включены ли стандартные подписи метаданных документа, такие как Автор, Владелец, дата создания и дата изменения, в список метаданных.

Если установить значение False (по умолчанию), GetDocumentInfo не будет включать эти подписи метаданных. При установке True информация о документе будет включать стандартные подписи метаданных.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### См. также
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
