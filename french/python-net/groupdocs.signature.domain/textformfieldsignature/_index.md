---
title: "Classe TextFormFieldSignature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les propriétés de signature du champ de formulaire texte pour les documents PDF."
type: docs
url: /fr/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

Représente les propriétés de signature du champ de formulaire texte pour les documents PDF.

Le type TextFormFieldSignature expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Initialise un PdfTextFormFieldSignature avec un nom prédéfini. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Initialise un PdfTextFormFieldSignature avec un nom prédéfini. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | Clone l'instance FormField Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Compare cette signature avec une autre signature pour vérifier l'égalité en fonction du type et des valeurs des propriétés. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | Remplace la méthode GetHashCode. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | Le texte de l'entrée du champ de formulaire. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La date de création de la signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Le drapeau indiquant si cette signature a été supprimée du document. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La hauteur de la signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Le drapeau indiquant si ce composant représente une signature (`True`) ou le contenu du document (`False`). (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La position gauche de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La date de modification de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | Le nom unique du champ de formulaire. (hérité de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Le numéro de page où la signature a été trouvée. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | L'identifiant unique de la signature, utilisé pour modifier la signature dans le document via des opérations de mise à jour ou de suppression. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Le type de signature. (hérité de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La position supérieure de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | Le type du champ de formulaire. (hérité de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | L'objet de données du champ de formulaire. (hérité de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | La largeur de la signature. (héritée de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # Créez un champ de texte nommé "FieldText" avec la valeur "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Créez des options de champ de formulaire pour celui-ci
        options = FormFieldSignOptions(text_field)

        # Définissez la position et la taille du champ de formulaire
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Signez le document et enregistrez le résultat
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
