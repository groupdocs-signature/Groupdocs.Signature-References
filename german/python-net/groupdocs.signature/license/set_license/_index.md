---
title: "Methode set_license"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Wenden Sie eine Lizenz auf den aktuellen Prozess an."
type: docs
url: /de/python-net/groupdocs.signature/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Wenden Sie eine Lizenz auf den aktuellen Prozess an.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| license_source |  | Entweder ein Zeichenkettenpfad zu einer ``.lic``-Datei oder ein lesbares dateiähnliches Objekt, das die Lizenzbytes liefert. Dateiähnliche Eingaben werden in eine temporäre Datei geschrieben, bevor sie an die Brücke übergeben werden. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `TypeError` | Wenn ``license_source`` weder ein Zeichenkettenpfad noch ein lesbares dateiähnliches Objekt ist. |

### Siehe auch
* class [`License`](/signature/python-net/groupdocs.signature/license/)
