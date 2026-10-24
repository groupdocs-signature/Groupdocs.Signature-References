---
title: "propiedad include_standard_metadata_signatures"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que indica si las firmas de metadatos de documento estándar, como Autor, Propietario, fecha de creación y fecha de modificación, están incluidas en la lista de metadatos."
type: docs
url: /es/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

La bandera que indica si las firmas de metadatos de documento estándar, como Autor, Propietario, fecha de creación y fecha de modificación, están incluidas en la lista de metadatos.

Si se establece en False (valor predeterminado), GetDocumentInfo no incluirá estas firmas de metadatos. Cuando se establece en True, la información del documento incluirá las firmas de metadatos estándar.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### Ver también
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
