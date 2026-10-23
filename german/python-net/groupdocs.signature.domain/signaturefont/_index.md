---
title: "SignatureFont Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Klasse SignatureFont gibt Schriftart-Eigenschaften für eine Textunterschrift an."
type: docs
url: /de/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

Die Klasse SignatureFont gibt Schriftart-Eigenschaften für eine Textunterschrift an.

Der Typ SignatureFont stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Initialisiert ein SignatureFont mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Der fette Schriftsstil. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Der Name der Schriftfamilie. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Der kursive Schriftsstil. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | Die Schriftgröße. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Der Durchstreichstil der Schrift. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Der Unterstreichungsstil der Schrift. |

### Beispiel

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Aufgabenleitfäden, die `SignatureFont` verwenden:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
