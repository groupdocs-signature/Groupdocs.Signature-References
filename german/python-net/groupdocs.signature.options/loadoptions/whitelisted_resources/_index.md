---
title: "whitelisted_resources Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Liste der Adressfragmente externer Ressourcen, die geladen werden, selbst wenn LoadOptions.SkipExternalResources true ist."
type: docs
url: /de/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Die Liste von Adressfragmenten externer Ressourcen, die geladen werden, selbst wenn [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true ist. Der Standardwert ist eine leere Liste.

Eine Ressource wird geladen, wenn ihre vollständige Adresse eines der Fragmente enthält. Der Vergleich ignoriert Groß‑ und Kleinschreibung, und leere Fragmente werden ignoriert. Bevorzugen Sie lange Fragmente wie `\"https://cdn.example.com/images/\"`: ein kurzes Fragment passt ebenfalls zu anderen Adressen, die es zufällig enthalten.

Das Setzen dieser Eigenschaft auf `None` leert die Liste. Die Liste hat keine Wirkung, wenn [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) false ist, weil dann jede externe Ressource geladen wird.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Siehe auch
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
