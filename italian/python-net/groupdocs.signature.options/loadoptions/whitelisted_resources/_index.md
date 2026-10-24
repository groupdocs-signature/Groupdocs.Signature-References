---
title: "proprietà whitelisted_resources"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "L'elenco dei frammenti di indirizzo delle risorse esterne che vengono caricate anche quando LoadOptions.SkipExternalResources è true."
type: docs
url: /it/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

L'elenco dei frammenti di indirizzo delle risorse esterne che vengono caricati anche quando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) è true. Il valore predefinito è una lista vuota.

Una risorsa viene caricata quando il suo indirizzo completo contiene uno dei frammenti. Il confronto ignora maiuscole/minuscole e i frammenti vuoti vengono ignorati. Preferisci frammenti lunghi come `\"https://cdn.example.com/images/\"`: un frammento corto corrisponde anche ad altri indirizzi che lo contengono incidentalmente.

Impostare questa proprietà su `None` svuota l'elenco. L'elenco non ha effetto quando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) è false, perché in tal caso ogni risorsa esterna viene caricata.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Vedi anche
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
