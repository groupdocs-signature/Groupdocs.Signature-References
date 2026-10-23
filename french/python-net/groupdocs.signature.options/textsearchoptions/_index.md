---
title: "Classe TextSearchOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de recherche pour les signatures de texte."
type: docs
url: /fr/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Représente les options de recherche pour les signatures de texte.

En savoir plus :
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

Le type TextSearchOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur de texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Le type de correspondance de texte utilisé pour la recherche. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | L'implémentation de signature texte à rechercher. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | Le texte de la signature à faire correspondre lors de la recherche. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Le drapeau indiquant s'il faut rechercher sur chaque page du document. Par défaut, cette valeur est True. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Le numéro de page du document pour la recherche (optionnel). (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Les options pour spécifier les pages pour la recherche de signature. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Le drapeau indiquant s'il faut renvoyer la position de la forme dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Le drapeau pour ne retourner que les signatures marquées comme `IsSignature`. Par défaut, la valeur est `False`, ce qui indique que toutes les signatures correspondant aux critères spécifiés sont retournées. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
Guides de tâches qui utilisent `TextSearchOptions` :

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
