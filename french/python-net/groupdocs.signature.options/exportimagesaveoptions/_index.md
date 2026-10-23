---
title: "Classe ExportImageSaveOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options d'enregistrement pour l'exportation de documents en image."
type: docs
url: /fr/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Représente les options d'enregistrement pour l'exportation de documents en image.

Le type ExportImageSaveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Initialise une nouvelle instance de la classe ExportAsImageSaveOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Initialise une nouvelle instance de ExportAsImageSaveOptions avec le format de fichier spécifié. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Les paramètres de bordure de l'image. Par défaut, cette valeur n'est pas définie. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Le drapeau pour exporter chaque page. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Le nombre de colonnes pour les images exportées. Utilisez cette propriété si vous devez placer les images en ligne. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Le numéro de page du document pour l'exportation (la valeur minimale est 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Les options pour spécifier les pages à signer. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Les pages du document sont placées sur des cadres différents dans une image TIFF. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Le drapeau qui détermine s'il faut ajouter automatiquement une extension lorsqu'elle manque dans le chemin du fichier de sortie. La valeur par défaut est False. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Le format de fichier du document signé. (hérité de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Le drapeau indiquant s'il faut écraser un fichier existant avec le nouveau fichier de sortie. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Le mot de passe utilisé pour protéger le document signé enregistré. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Le drapeau indiquant s'il faut utiliser le mot de passe de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) lors de l'enregistrement du document signé en tant que protégé. La valeur par défaut est True. Non pris en charge pour les documents Image. (hérité de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
