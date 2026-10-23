---
title: "Classe PngSaveOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Les options d’enregistrement PNG pour les documents image."
type: docs
url: /fr/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

Les options d’enregistrement PNG pour les documents image.

Le type PngSaveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Initialise PngSaveOptions avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | La profondeur de bits. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | Le type du `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale et 0 le mode stockage. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | Le type de filtre `PngFilterType` utilisé lors du processus d'enregistrement du fichier PNG. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | L'indicateur progressif indiquant si le PNG est enregistré de manière progressive. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Le drapeau qui détermine s'il faut ajouter automatiquement une extension lorsqu'elle manque dans le chemin du fichier de sortie. La valeur par défaut est False. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Le format de fichier du document signé. (hérité de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Le drapeau indiquant s'il faut écraser un fichier existant avec le nouveau fichier de sortie. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Le mot de passe utilisé pour protéger le document signé enregistré. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Le drapeau indiquant s'il faut utiliser le mot de passe de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) lors de l'enregistrement du document signé en tant que protégé. La valeur par défaut est True. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
