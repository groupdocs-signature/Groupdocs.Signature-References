---
title: "classe DataMatrixEncodeMode"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "énumération DataMatrixEncodeMode — référence de l'API GroupDocs.Signature pour Python via .NET."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Le type DataMatrixEncodeMode expose les membres suivants :

### Champs
| Champ | Description |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Sélectionner automatiquement le meilleur mode d'encodage pour l'encodage DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Encode un caractère alphanumérique ou deux caractères numériques par octet |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Encoder des valeurs 8 bits |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Encoder avec le codage spécifié dans BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Utilise le codage C40. Encode les alphanumériques majuscules, minuscules et les caractères spéciaux |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Utilise le codage Text. Encode les alphanumériques minuscules, majuscules et les caractères spéciaux. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Utilise le codage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreuses marques de ponctuation, mais ne prend pas en charge les lettres minuscules. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Utilise le codage ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | Le mode ExtendedCodetext permet de changer manuellement les schémas de codage dans le code-texte. Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Les schémas de codage autorisés sont : EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Exemple de code-texte étendu : @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Tous les barres obliques inverses (\) doivent être doublés dans le texte. |

### Voir aussi
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
