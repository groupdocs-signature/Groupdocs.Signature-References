---
title: "propriété include_standard_metadata_signatures"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "L'indicateur indiquant si les signatures de métadonnées de document standard telles que Auteur, Propriétaire, date de création et date de modification sont incluses dans la liste des métadonnées."
type: docs
url: /fr/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

L'indicateur indiquant si les signatures de métadonnées de document standard telles que Auteur, Propriétaire, date de création et date de modification sont incluses dans la liste des métadonnées.

Si elle est définie sur False (par défaut), GetDocumentInfo n’inclura pas ces signatures de métadonnées. Lorsqu’elle est définie sur True, les informations du document incluront les signatures de métadonnées standard.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### Voir aussi
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
