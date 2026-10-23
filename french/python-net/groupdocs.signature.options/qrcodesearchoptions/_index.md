---
title: "Classe QrCodeSearchOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de recherche pour les signatures QR-Code."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Représente les options de recherche pour les signatures QR-Code.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Le type QrCodeSearchOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec la valeur du type d'encodage. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec le type d'encodage et les valeurs de texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | L'implémentation de [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilisée pour encoder et décoder le texte ou les propriétés de données de la signature QR‑Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Le type d'encodage à rechercher pour les QR‑codes. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Le type de correspondance de texte QR‑Code utilisé lors de la recherche. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Le drapeau qui détermine si le contenu image du QR‑Code est renvoyé pour chaque signature sur une page de document. Lorsqu'il est défini sur True, les données d'image brutes sont conservées dans la propriété `content` de la signature en utilisant le format spécifié par `return_content_type`. Désactivé par défaut. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Le type de fichier du contenu image renvoyé de la signature QR‑Code lorsque la propriété `return_content` est activée. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | Le texte de la signature QR‑Code à rechercher et à faire correspondre. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Le drapeau indiquant s'il faut rechercher sur chaque page du document. Par défaut, cette valeur est True. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Le numéro de page du document pour la recherche (optionnel). (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Les options pour spécifier les pages pour la recherche de signature. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Le drapeau indiquant s'il faut renvoyer la position de la forme dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Le drapeau pour ne retourner que les signatures marquées comme `IsSignature`. Par défaut, la valeur est `False`, ce qui indique que toutes les signatures correspondant aux critères spécifiés sont retournées. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
