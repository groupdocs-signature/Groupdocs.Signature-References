---
title: "propriété load_external_resources"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau qui détermine si le document charge des ressources externes."
type: docs
url: /fr/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Le drapeau qui détermine si le document charge des ressources externes. Cette propriété est obsolète ; utilisez [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) à la place, qui a le sens opposé.

LoadExternalResources = True est équivalent à `SkipExternalResources` = False, et LoadExternalResources = False est équivalent à `SkipExternalResources` = True. La valeur par défaut est False, ce qui signifie que les ressources externes ne sont pas chargées sauf autorisation explicite.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Voir aussi
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
