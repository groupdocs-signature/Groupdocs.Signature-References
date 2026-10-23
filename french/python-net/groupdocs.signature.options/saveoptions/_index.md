---
title: "Classe SaveOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Spécifie des options supplémentaires (comme le mot de passe) lors de l’enregistrement d’un document à signer."
type: docs
url: /fr/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Spécifie des options supplémentaires (comme le mot de passe) lors de l’enregistrement d’un document à signer.

Le type SaveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Initialise une nouvelle instance de la classe SaveOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Initialise une nouvelle instance de la classe SaveOptions avec le type de sortie spécifié et le drapeau de remplacement. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Le drapeau qui détermine s'il faut ajouter automatiquement une extension lorsqu'elle est absente dans le chemin du fichier de sortie. La valeur par défaut est False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Le drapeau indiquant s'il faut écraser un fichier existant avec le nouveau fichier de sortie. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Le mot de passe utilisé pour protéger le document signé enregistré. Non pris en charge pour les documents Image. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | L'indicateur indiquant s'il faut utiliser le mot de passe provenant de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) lors de l'enregistrement du document signé en tant que protégé. La valeur par défaut est True. Non pris en charge pour les documents Image. |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
