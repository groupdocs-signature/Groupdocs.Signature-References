---
title: "load_external_resources-Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das bestimmt, ob das Dokument externe Ressourcen lädt."
type: docs
url: /de/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Das Flag, das bestimmt, ob das Dokument externe Ressourcen lädt. Diese Eigenschaft ist veraltet; verwenden Sie stattdessen [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), das die gegenteilige Bedeutung hat.

LoadExternalResources = True ist gleichbedeutend mit `SkipExternalResources` = False, und LoadExternalResources = False ist gleichbedeutend mit `SkipExternalResources` = True. Der Standardwert ist False, was bedeutet, dass externe Ressourcen nicht geladen werden, es sei denn, sie werden ausdrücklich erlaubt.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Siehe auch
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
