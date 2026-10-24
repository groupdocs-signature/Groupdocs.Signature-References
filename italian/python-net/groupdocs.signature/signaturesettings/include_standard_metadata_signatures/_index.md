---
title: "proprietà include_standard_metadata_signatures"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che indica se le firme di metadati del documento standard, come Autore, Proprietario, data di creazione e data di modifica, sono incluse nell'elenco dei metadati."
type: docs
url: /it/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

Il flag che indica se le firme di metadati del documento standard, come Autore, Proprietario, data di creazione e data di modifica, sono incluse nell'elenco dei metadati.

Se impostato su False (predefinito), GetDocumentInfo non includerà queste firme di metadati. Quando impostato su True, le informazioni del documento includeranno le firme di metadati standard.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### Vedi anche
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
