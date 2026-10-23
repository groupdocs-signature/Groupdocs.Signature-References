---
title: "Classe ImageDigitalVerifyOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Conserve les options pour vérifier les signatures numériques dans les images raster."
type: docs
url: /fr/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Conserve les options pour vérifier les signatures numériques dans les images raster.

Le type ImageDigitalVerifyOptions expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Initialise une nouvelle instance de la classe ImageDigitalVerifyOptions pour vérifier les signatures numériques (stéganographie) dans les images matricielles. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | La probabilité renvoyée par AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Le pourcentage de seuil de détection pour l'extraction partielle (0-100). La valeur par défaut est 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Le mot de passe qui a été utilisé pour incorporer la signature. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | La propriété détermine si une extraction complète des données (AnalyzePercentageDigitalSignature) est effectuée pour une précision maximale. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Le drapeau indiquant si chaque page du document doit être vérifiée. Par défaut, la valeur est True. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Les extensions supplémentaires pour la vérification des options de signature alternatives. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Le drapeau de propriété valide. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Le numéro de page du document à vérifier ; s'il n'est pas défini, toutes les pages du document sont vérifiées pour la première occurrence (la valeur minimale est 1). (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Les options de page pour spécifier les pages à vérifier. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La position de la forme dans la mise en page du document utilisée pour vérifier les signatures dans les en-têtes/pieds de page. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
