---
title: "Classe JpegSaveOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options d’enregistrement JPEG pour les documents image."
type: docs
url: /fr/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Représente les options d’enregistrement JPEG pour les documents image.

Le type JpegSaveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Initialise JpegSaveOptions avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Le nombre de bits par canal pour une image JPEG sans perte. Les valeurs prises en charge vont de 2 à 8 bits par canal. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Le type de couleur pour l'image JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Le commentaire du fichier JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Le type de compression. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | La qualité de l'image. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Le mode d'arrondi d'échantillon utilisé pour adapter une valeur de 8 bits à une valeur de n bits de `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Le drapeau qui détermine s'il faut ajouter automatiquement une extension lorsqu'elle manque dans le chemin du fichier de sortie. La valeur par défaut est False. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Le format de fichier du document signé. (hérité de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Le drapeau indiquant s'il faut écraser un fichier existant avec le nouveau fichier de sortie. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Le mot de passe utilisé pour protéger le document signé enregistré. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Le drapeau indiquant s'il faut utiliser le mot de passe de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) lors de l'enregistrement du document signé en tant que protégé. La valeur par défaut est True. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
