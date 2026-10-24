---
title: "load_external_resources‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som bestämmer om dokumentet laddar externa resurser."
type: docs
url: /sv/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Flaggan som bestämmer om dokumentet laddar externa resurser. Denna egenskap är föråldrad; använd istället [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), som har motsatt betydelse.

LoadExternalResources = True är ekvivalent med `SkipExternalResources` = False, och LoadExternalResources = False är ekvivalent med `SkipExternalResources` = True. Standardvärdet är False, vilket betyder att externa resurser inte laddas om de inte uttryckligen tillåts.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Se även
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
