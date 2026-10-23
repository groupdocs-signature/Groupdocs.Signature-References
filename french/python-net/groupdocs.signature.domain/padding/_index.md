---
title: "Classe Padding"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les informations de remplissage ou de marge associées à l'élément."
type: docs
url: /fr/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Représente les informations de remplissage ou de marge associées à l'élément.

Le type Padding expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Initialise une nouvelle instance de la classe Padding avec des valeurs zéro. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Initialise une nouvelle instance de la classe Padding en utilisant la taille de remplissage fournie pour tous les bords. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Initialise une nouvelle instance de la classe Padding en utilisant les tailles de remplissage fournies. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Obtient une copie de cet objet. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | La valeur de remplissage pour tous les bords. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | La valeur de remplissage pour le bord inférieur. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Le remplissage combiné pour les bords droit et gauche. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | La valeur de remplissage pour le bord gauche. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | La valeur de remplissage pour le bord droit. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | La valeur de remplissage pour le bord supérieur. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Le remplissage combiné pour les bords supérieur et inférieur. |

### Champs
| Champ | Description |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Fournit un objet Padding sans remplissage. |

### Exemple

```python
from groupdocs.signature.domain import Padding

# Remplissage uniforme de 5 unités sur tous les côtés
uniform = Padding(5)

# Remplissage spécifique à droite et en bas
custom = Padding(right=40, bottom=60)
```

### Guides
Guides de tâche qui utilisent `Padding` :

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
