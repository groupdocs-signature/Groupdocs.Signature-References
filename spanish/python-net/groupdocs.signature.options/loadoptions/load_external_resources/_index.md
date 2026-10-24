---
title: "propiedad load_external_resources"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El indicador que determina si el documento carga recursos externos."
type: docs
url: /es/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

La bandera que determina si el documento carga recursos externos. Esta propiedad está obsoleta; use [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) en su lugar, que tiene el significado opuesto.

LoadExternalResources = True es equivalente a `SkipExternalResources` = False, y LoadExternalResources = False es equivalente a `SkipExternalResources` = True. El valor predeterminado es False, lo que significa que los recursos externos no se cargan a menos que se permitan explícitamente.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Ver también
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
