---
title: "save_document_on_empty_update eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de Update‑methode geen handtekeningen heeft om bij te werken."
type: docs
url: /nl/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de `Update`‑methode geen handtekeningen heeft om bij te werken.

Als ingesteld op `True` (standaard), wordt het document opgeslagen met een bijbehorend historisch proceslog (datum en type bewerking) zelfs wanneer er geen handtekeningen worden bijgewerkt. Wanneer ingesteld op `False`, wordt het brondocument helemaal niet gewijzigd.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Zie ook
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
