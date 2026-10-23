---
title: "classe DigitalSearchOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de recherche pour les signatures numériques."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Représente les options de recherche pour les signatures numériques.

En savoir plus

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Le type DigitalSearchOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Initialise une nouvelle instance de la classe DigitalSearchOptions avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | Les commentaires de la signature numérique à rechercher. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Le nom distinctif de l'émetteur du certificat à rechercher lorsque la valeur n'est pas vide. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | La plage de date et d'heure de la signature numérique à rechercher. La valeur nullable sera ignorée. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | La fin de la plage de date et d'heure des signatures numériques à rechercher. Une valeur nulle sera ignorée. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Le nom distinctif du sujet du certificat à rechercher lorsqu'une valeur non vide est fournie. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Le drapeau indiquant s'il faut rechercher sur chaque page du document. Par défaut, cette valeur est True. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Le numéro de page du document pour la recherche (optionnel). (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Les options pour spécifier les pages pour la recherche de signature. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Le drapeau indiquant s'il faut renvoyer la position de la forme dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Le drapeau pour ne retourner que les signatures marquées comme `IsSignature`. Par défaut, la valeur est `False`, ce qui indique que toutes les signatures correspondant aux critères spécifiés sont retournées. (hérité de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
