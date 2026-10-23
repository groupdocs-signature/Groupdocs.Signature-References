---
title: "Classe LoadOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La classe LoadOptions permet de spécifier des options supplémentaires (comme le mot de passe) lors de l’ouverture d’un document à signer."
type: docs
url: /fr/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

La classe LoadOptions permet de spécifier des options supplémentaires (comme le mot de passe) lors de l’ouverture d’un document à signer.

Définissez l'attribut `password` sur le mot de passe du document si le fichier est chiffré.

Le type LoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Initialise une nouvelle instance de la classe LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Initialise une nouvelle instance de la classe [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) avec un type de fichier spécifié. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Le type de fichier associé aux options de chargement, par défaut [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Le drapeau qui détermine si le document charge des ressources externes. Cette propriété est obsolète ; utilisez [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) à la place, qui a le sens opposé. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Le mot de passe utilisé pour ouvrir un document protégé et pour enregistrer un document signé en tant que protégé. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Les autorisations du document PDF telles que l'impression, la modification et l'extraction de données. Uniquement pour les documents PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | L'indicateur qui empêche le document de charger des ressources externes. La valeur par défaut est True ; les ressources externes ne sont pas chargées sauf celles qui correspondent à [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | La liste des fragments d'adresses des ressources externes qui sont chargés même lorsque [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) est vrai. La valeur par défaut est une liste vide. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
