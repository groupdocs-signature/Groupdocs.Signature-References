---
title: "Classe FormFieldSearchOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de recherche pour les signatures de champs de formulaire."
type: docs
url: /fr/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Représente les options de recherche pour les signatures de champs de formulaire.

En savoir plus :
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Le type FormFieldSearchOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Initialise une nouvelle instance de la classe FormFieldSearchOptions avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Le modèle d'expression régulière utilisé pour faire correspondre le nom d'une signature de champ de formulaire lors de la recherche. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Le type de signature de champ de formulaire à rechercher. La valeur par défaut est None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | La valeur de la signature de champ de formulaire à rechercher. La valeur par défaut est None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Le drapeau indiquant s'il faut rechercher sur chaque page du document. Par défaut, cette valeur est True. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Le numéro de page du document pour la recherche (optionnel). (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Les options pour spécifier les pages pour la recherche de signature. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Le drapeau indiquant s'il faut renvoyer la position de la forme dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Le drapeau pour ne retourner que les signatures marquées comme `IsSignature`. Par défaut, la valeur est `False`, ce qui indique que toutes les signatures correspondant aux critères spécifiés sont retournées. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Retourner uniquement les champs texte nommés "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
