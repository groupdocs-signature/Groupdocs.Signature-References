---
title: "Classe TextSignature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La classe TextSignature contient les propriétés de signature texte."
type: docs
url: /fr/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

La classe TextSignature contient les propriétés de signature texte.

Le type TextSignature expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Initialise un objet TextSignature avec l'identifiant de signature unique obtenu lors d'une opération de signature ou de recherche. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Clone l'instance Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Compare la signature spécifiée avec cette instance pour l'égalité. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Renvoie le code de hachage pour la signature. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | L'attribut natif indiquant si la signature est spécifique au document. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | L'implémentation de la signature texte. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | Le texte de la signature. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La date de création de la signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Le drapeau indiquant si cette signature a été supprimée du document. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La hauteur de la signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Le drapeau indiquant si ce composant représente une signature (`True`) ou le contenu du document (`False`). (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La position gauche de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La date de modification de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Le numéro de page où la signature a été trouvée. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | L'identifiant unique de la signature, utilisé pour modifier la signature dans le document via des opérations de mise à jour ou de suppression. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Le type de signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La position supérieure de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | La largeur de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
