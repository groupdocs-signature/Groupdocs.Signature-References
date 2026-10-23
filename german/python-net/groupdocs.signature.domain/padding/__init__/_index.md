---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Padding‑Klasse mit Nullwerten."
type: docs
url: /de/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Padding‑Klasse mit Nullwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature.domain import Padding

# Ein Padding‑Objekt mit Standardwerten (Null) erstellen
default_padding = Padding()
```

## __init__ {#all}

Initialisiert eine neue Instanz der Padding‑Klasse unter Verwendung der angegebenen Polstergröße für alle Kanten.

```python
def __init__(self, all):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| all | `int` | Die Anzahl der Maßeinheiten, die für das Padding aller Kanten verwendet werden. |

### Beispiel

```python
# Einheitliche Polsterung von 5 Einheiten auf allen Seiten
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Initialisiert eine neue Instanz der Padding‑Klasse unter Verwendung der angegebenen Polstergrößen.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left | `int` | Die linke Padding-Größe. |
| right | `int` | Die rechte Padding-Größe. |
| top | `int` | Die obere Padding-Größe. |
| bottom | `int` | Die untere Padding-Größe. |

### Beispiel

```python
from groupdocs.signature.domain import Padding

# Ein Padding mit rechten und unteren Versätzen erstellen
margin = Padding(right=40, bottom=60)
```

### Siehe auch
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
