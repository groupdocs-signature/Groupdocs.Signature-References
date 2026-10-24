---
title: "proprietà load_external_resources"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che determina se il documento carica risorse esterne."
type: docs
url: /it/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Il flag che determina se il documento carica risorse esterne. Questa proprietà è obsoleta; usa invece [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), che ha il significato opposto.

LoadExternalResources = True è equivalente a `SkipExternalResources` = False, e LoadExternalResources = False è equivalente a `SkipExternalResources` = True. Il valore predefinito è False, il che significa che le risorse esterne non vengono caricate a meno che non siano esplicitamente consentite.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Vedi anche
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
