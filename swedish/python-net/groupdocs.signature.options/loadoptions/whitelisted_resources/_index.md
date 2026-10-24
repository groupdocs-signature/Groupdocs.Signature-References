---
title: "whitelisted_resources egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Listan med adressfragment för externa resurser som laddas även när LoadOptions.SkipExternalResources är true."
type: docs
url: /sv/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Listan med adressfragment för externa resurser som laddas även när [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) är true. Standardvärdet är en tom lista.

En resurs laddas när dess fullständiga adress innehåller ett av fragmenten. Jämförelsen ignorerar skiftläge, och tomma fragment ignoreras. Föredra långa fragment såsom `\"https://cdn.example.com/images/\"`: ett kort fragment matchar också andra adresser som råkar innehålla det.

Att sätta denna egenskap till `None` rensar listan. Listan har ingen effekt när [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) är false, eftersom då varje extern resurs laddas.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Se även
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
