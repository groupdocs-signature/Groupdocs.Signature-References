---
title: "Classe ImageSignature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La classe contient les propriétés de la signature d'image."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

La classe contient les propriétés de la signature d'image.

Le type ImageSignature expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Initialise un objet ImageSignature avec un identifiant de signature unique obtenu à partir de la méthode Sign ou Search de la classe [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Cloner l'instance ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Détermine si la signature spécifiée est égale à cette instance. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Renvoie le code de hachage pour la signature. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Les données d'image binaires de la signature, au format spécifié par [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Le format de l'image de la signature. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | La taille en octets de l'image de la signature. |
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
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
