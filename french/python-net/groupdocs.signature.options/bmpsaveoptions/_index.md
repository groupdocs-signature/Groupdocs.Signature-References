---
title: "Classe BmpSaveOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options d'enregistrement BMP pour les documents image."
type: docs
url: /fr/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Représente les options d'enregistrement BMP pour les documents image.

Le type BmpSaveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Initialise BmpSaveOptions avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | Le nombre de bits par pixel de l'image. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | La compression. Voir `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de la valeur définie. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | La résolution verticale ; notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de la valeur définie. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Le drapeau qui détermine s'il faut ajouter automatiquement une extension lorsqu'elle manque dans le chemin du fichier de sortie. La valeur par défaut est False. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Le format de fichier du document signé. (hérité de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Le drapeau indiquant s'il faut écraser un fichier existant avec le nouveau fichier de sortie. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Le mot de passe utilisé pour protéger le document signé enregistré. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Le drapeau indiquant s'il faut utiliser le mot de passe de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) lors de l'enregistrement du document signé en tant que protégé. La valeur par défaut est True. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
