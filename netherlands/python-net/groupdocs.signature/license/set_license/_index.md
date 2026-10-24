---
title: "set_license methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Pas een licentie toe op het huidige proces."
type: docs
url: /nl/python-net/groupdocs.signature/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Pas een licentie toe op het huidige proces.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| license_source |  | Een stringpad naar een ``.lic``-bestand of een leesbaar bestand-achtig object dat de licentiebits oplevert. Bestand-achtige invoer wordt naar een tijdelijk bestand geschreven voordat deze aan de brug wordt doorgegeven. |

| Verhoogt | Beschrijving |
| :- | :- |
| `TypeError` | Als ``license_source`` noch een stringpad noch een leesbaar bestand-achtig object is. |

### Zie ook
* class [`License`](/signature/python-net/groupdocs.signature/license/)
