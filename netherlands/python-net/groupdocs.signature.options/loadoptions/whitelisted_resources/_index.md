---
title: "whitelisted_resources‑eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De lijst met adresfragmenten van externe bronnen die worden geladen, zelfs wanneer LoadOptions.SkipExternalResources true is."
type: docs
url: /nl/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

De lijst met adresfragmenten van externe bronnen die worden geladen, zelfs wanneer [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true is. De standaardwaarde is een lege lijst.

Een bron wordt geladen wanneer het volledige adres een van de fragmenten bevat. De vergelijking negeert hoofdlettergebruik en lege fragmenten worden genegeerd. Geef de voorkeur aan lange fragmenten zoals `\"https://cdn.example.com/images/\"`; een kort fragment komt ook overeen met andere adressen die het toevallig bevatten.

Het instellen van deze eigenschap op `None` wist de lijst. De lijst heeft geen effect wanneer [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) false is, omdat dan elke externe bron wordt geladen.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Zie ook
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
