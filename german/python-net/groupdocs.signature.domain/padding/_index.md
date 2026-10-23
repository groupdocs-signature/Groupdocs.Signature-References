---
title: "Padding‑Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Padding- oder Randinformationen dar, die mit dem Element verbunden sind."
type: docs
url: /de/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Stellt Padding- oder Randinformationen dar, die mit dem Element verbunden sind.

Der Padding‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Initialisiert eine neue Instanz der Padding‑Klasse mit Nullwerten. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Initialisiert eine neue Instanz der Padding‑Klasse unter Verwendung der angegebenen Polstergröße für alle Kanten. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Initialisiert eine neue Instanz der Padding‑Klasse unter Verwendung der angegebenen Polstergrößen. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Gibt eine Kopie dieses Objekts zurück. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Der Polsterwert für alle Kanten. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Der Polsterwert für die untere Kante. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Der kombinierte Polsterwert für die rechte und linke Kante. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Der Polsterwert für die linke Kante. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Der Polsterwert für die rechte Kante. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Der Polsterwert für die obere Kante. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Der kombinierte Polsterwert für die obere und untere Kante. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Stellt ein Padding‑Objekt ohne Polsterung bereit. |

### Beispiel

```python
from groupdocs.signature.domain import Padding

# Einheitliche Polsterung von 5 Einheiten auf allen Seiten
uniform = Padding(5)

# Spezifisches Padding rechts und unten
custom = Padding(right=40, bottom=60)
```

### Guides
Aufgabenleitfäden, die `Padding` verwenden:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
