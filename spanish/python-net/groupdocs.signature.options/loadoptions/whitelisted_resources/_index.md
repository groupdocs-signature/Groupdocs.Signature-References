---
title: "propiedad whitelisted_resources"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La lista de fragmentos de direcciones de recursos externos que se cargan incluso cuando LoadOptions.SkipExternalResources es true."
type: docs
url: /es/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

La lista de fragmentos de direcciones de recursos externos que se cargan incluso cuando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) es true. El valor predeterminado es una lista vacía.

Prefiera fragmentos largos como `\"https://cdn.example.com/images/\"`: un fragmento corto también coincide con otras direcciones que lo contengan.

Establecer esta propiedad en `None` borra la lista. La lista no tiene efecto cuando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) es false, porque entonces se cargan todos los recursos externos.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Ver también
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
