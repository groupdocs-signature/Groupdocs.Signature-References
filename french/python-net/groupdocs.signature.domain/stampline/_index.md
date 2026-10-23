---
title: "Classe StampLine"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Spécifiez les propriétés de ligne du tampon."
type: docs
url: /fr/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Spécifiez les propriétés de ligne du tampon.

Le type StampLine expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Initialise un StampLine avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | La couleur d'arrière-plan de la signature. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | La police du texte de la ligne de tampon. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | La hauteur de ligne sur le tampon. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | La bordure interne de la ligne de tampon. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | La bordure extérieure de la ligne de tampon. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Le texte de la ligne de tampon. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | L'intention inférieure du texte. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | La couleur du texte de la signature. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Le type de répétition du texte. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | La visibilité de la ligne de tampon. |

### Exemple

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Créer une ligne de tampon
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
