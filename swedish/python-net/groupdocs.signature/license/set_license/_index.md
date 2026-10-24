---
title: "metoden set_license"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Applicera en licens på den aktuella processen."
type: docs
url: /sv/python-net/groupdocs.signature/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Applicera en licens på den aktuella processen.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| license_source |  | Antingen en sökväg som en sträng till en ``.lic``‑fil eller ett läsbart fil‑liknande objekt som returnerar licens‑bytarna. Fil‑liknande indata skrivs till en temporär fil innan de skickas till bryggan. |

| Utlöser | Beskrivning |
| :- | :- |
| `TypeError` | Om ``license_source`` varken är en strängsökväg eller ett läsbart fil‑liknande objekt. |

### Se även
* class [`License`](/signature/python-net/groupdocs.signature/license/)
