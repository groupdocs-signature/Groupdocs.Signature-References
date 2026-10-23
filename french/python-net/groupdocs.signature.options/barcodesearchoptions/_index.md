---
title: "Classe BarcodeSearchOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de recherche pour les signatures de code-barres."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Représente les options de recherche pour les signatures de code-barres.

En savoir plus :
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

Le type BarcodeSearchOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Initialise une nouvelle instance de la classe BarcodeSearchOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Initialise une nouvelle instance de la classe BarcodeSearchOptions avec la valeur du type d'encodage. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Initialise une nouvelle instance de la classe BarcodeSearchOptions avec les valeurs du type d'encodage et du texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | Le type d'encodage utilisé pour filtrer la recherche de code-barres ; s'il n'est pas défini, la recherche inclut tous les types de code-barres pris en charge. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | Le type de correspondance du texte du code-barres utilisé pour la recherche. Il n'est utilisé que lorsque la propriété `text` est définie. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | Le drapeau indiquant s'il faut récupérer le contenu image du code-barres d'une signature sur une page du document. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | Le type de fichier du contenu image retourné pour une signature Barcode lorsque la propriété `return_content` est activée. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | Le texte de la signature du code-barres à rechercher et à faire correspondre. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Le drapeau indiquant s'il faut rechercher sur chaque page du document. Par défaut, cette valeur est True. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Le numéro de page du document pour la recherche (optionnel). (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Les options pour spécifier les pages pour la recherche de signature. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Le drapeau indiquant s'il faut renvoyer la position de la forme dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Le drapeau pour ne retourner que les signatures marquées comme `IsSignature`. Par défaut, la valeur est `False`, ce qui indique que toutes les signatures correspondant aux critères spécifiés sont retournées. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Guides de tâches qui utilisent `BarcodeSearchOptions` :

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
