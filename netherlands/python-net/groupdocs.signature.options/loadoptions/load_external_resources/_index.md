---
title: "load_external_resources‑eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die bepaalt of het document externe bronnen laadt."
type: docs
url: /nl/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

De vlag die bepaalt of het document externe bronnen laadt. Deze eigenschap is verouderd; gebruik in plaats daarvan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), die de tegenovergestelde betekenis heeft.

LoadExternalResources = True is gelijk aan `SkipExternalResources` = False, en LoadExternalResources = False is gelijk aan `SkipExternalResources` = True. De standaardwaarde is False, wat betekent dat externe bronnen niet worden geladen tenzij expliciet toegestaan.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Zie ook
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
