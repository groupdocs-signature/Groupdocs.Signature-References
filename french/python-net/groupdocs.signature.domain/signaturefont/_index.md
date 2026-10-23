---
title: "SignatureFont classe"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La classe SignatureFont spécifie les propriétés de police pour une signature texte."
type: docs
url: /fr/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

La classe SignatureFont spécifie les propriétés de police pour une signature texte.

Le type SignatureFont expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Initialise un SignatureFont avec des valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Le style gras de la police. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Le nom de la famille de police. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Le style italique de la police. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | La taille de la police. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Le style barré de la police. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Le style souligné de la police. |

### Exemple

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Guides de tâches qui utilisent `SignatureFont` :

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
