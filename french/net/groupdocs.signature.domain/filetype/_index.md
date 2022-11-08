---
title: FileType
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente le type de fichier.
type: docs
weight: 430
url: /fr/net/groupdocs.signature.domain/filetype/
---
## FileType class

Représente le type de fichier.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Suffixe du nom de fichier (y compris le point "."), par exemple ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Nom du type de fichier, par exemple "Document Microsoft Word". |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Mappe l'extension de fichier au type de fichier. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Détermine si le courant[`FileType`](../filetype)est le même que celui spécifié[`FileType`](../filetype) objet. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Détermine si le courant[`FileType`](../filetype) est le même que l'objet spécifié. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Renvoie le code de hachage pour le courant[`FileType`](../filetype) objet. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Récupère les types de fichiers pris en charge |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Détermine si deux[`FileType`](../filetype) les objets sont les mêmes. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Détermine si deux[`FileType`](../filetype) les objets ne sont pas les mêmes. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) est utilisé pour stocker des images numériques bitmap. Ces images sont indépendantes de la carte graphique et sont également appelées format de fichier bitmap indépendant du périphérique (DIB). En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) est un fichier d'image de dessin vectoriel créé nativement avec CorelDRAW pour stocker des images numériques encodées et compressées. Un tel fichier de dessin contient du texte, des lignes, des formes, des images, des couleurs et des effets pour la représentation vectorielle du contenu de l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) est un format de métafichier standard international gratuit et indépendant de la plate-forme pour le stockage et l'échange de graphiques vectoriels (2D), de graphiques raster et de texte. CGM utilise une approche orientée objet et de nombreuses fonctionnalités pour la production d'images. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | Fichier image d'échange de métafichier CorelDRAW (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Fichier de valeurs séparées par des virgules (.csv) représente des fichiers en texte brut contenant des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | Image DICOM (.dcm) représente une image numérique qui stocke les informations médicales des patients telles que les IRM, les tomodensitogrammes et les images échographiques. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) est un format de fichier graphique destiné aux documents numérisés et aux livres, en particulier ceux qui contiennent une combinaison de texte, de dessins, d'images et de photographies. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc) représente des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) est un document généré par Microsoft Word 2007 ou supérieur avec la possibilité d'exécuter des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée de binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Modèle de document Word (.dot) sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres préformatés pour la génération d'autres fichiers DOC ou DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) représente un fichier de modèle créé avec Microsoft Word 2007 ou une version ultérieure. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres préformatés pour la génération d'autres fichiers DOCX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) représente les images graphiques indépendamment du périphérique. Les méta-fichiers d'EMF comprennent des enregistrements de longueur variable dans l'ordre chronologique qui peuvent restituer l'image stockée après analyse sur n'importe quel périphérique de sortie. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) décrit un programme en langage PostScript encapsulé qui décrit l'apparence d'une seule page. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) est un type d'image hautement compressée. Pour chaque image, le GIF autorise généralement jusqu'à 8 bits par pixel et jusqu'à 256 couleurs sont autorisées sur l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | Image JPEG (.jpeg) est un type de format d'image enregistré à l'aide de la méthode de compression avec perte. L'image de sortie, résultant de la compression, est un compromis entre la taille de stockage et la qualité de l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Image (.jpg) est un type de format d'image enregistré à l'aide de la méthode de compression avec perte. L'image de sortie, résultant de la compression, est un compromis entre la taille de stockage et la qualité de l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) est utilisé par l'application Apache OpenOffice's Draw pour stocker les éléments de dessin sous forme d'image vectorielle. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) signifie le format de document OpenDocument Spreadsheet modifiable par l'utilisateur. Les données sont stockées dans le fichier ODF en lignes et en colonnes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | Les documents texte OpenDocument (.odt) sont des types de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | Modèle de feuille de calcul OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) représente les modèles de documents générés par les applications conformément au format standard OpenDocument d'OASIS. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Document de langage de commande d'imprimante (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) est un type de format de fichier image raster qui utilise une compression sans perte. Ce format de fichier a été créé en remplacement de Graphics Interchange Format (GIF) et n'a aucune limitation de copyright. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | Le modèle PowerPoint (.pot) représente les fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) sont des fichiers de modèle Microsoft PowerPoint prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou supérieur et contiennent des paramètres par défaut qui peuvent être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) représente les modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | Les diaporamas PowerPoint (.pps) sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) représente le format de fichier de diaporama prenant en charge les macros créé avec Microsoft PowerPoint 2007 ou version ultérieure. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | Les fichiers PowerPoint Open XML Slide Show (.ppsx) sont créés à l'aide de Microsoft PowerPoint 2007 et supérieur à des fins de diaporama. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | Présentation PowerPoint (.ppt) représente un fichier PowerPoint composé d'une collection de diapositives à afficher sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation sont des fichiers de présentation prenant en charge les macros qui sont créés avec Microsoft PowerPoint 2007 ou des versions supérieures. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation XML ouvert de Microsoft PowerPoint. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | Fichier PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) représente le format de fichier natif d'Adobe Photoshop utilisé pour la conception et le développement graphiques. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) représente une méthode d'encodage de texte et de graphiques formatés à utiliser dans les applications. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) est un fichier Scalar Vector Graphics qui utilise le format texte basé sur XML pour décrire l'apparence d'une image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. Il est capable de décrire des données d'image à deux niveaux, en niveaux de gris, en palette de couleurs et en couleurs dans plusieurs espaces colorimétriques. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. Il est capable de décrire des données d'image à deux niveaux, en niveaux de gris, en palette de couleurs et en couleurs dans plusieurs espaces colorimétriques. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Fichier de valeurs séparées par des tabulations (.tsv) représente les données séparées par des tabulations au format texte brut. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Fichier de texte brut (.txt) représente un document texte contenant du texte brut sous forme de lignes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Représente un type de fichier inconnu. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) est un format de fichier numérique pour stocker les informations de contact. Le format est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) est un format de fichier d'image Web raster moderne basé sur une compression sans perte et avec perte. Il offre la même qualité d'image tout en réduisant considérablement la taille de l'image. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Le métafichier Windows (.wmf) représente le métafichier Microsoft Windows (WMF) pour le stockage des données d'images au format vectoriel et bitmap. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | Document WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Feuille de calcul Excel (.xls) représente le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Feuille de calcul binaire Excel (.xlsb) spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) est un type de tableur qui prend en charge les macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Le modèle binaire Excel (.xlt) représente le format de fichier de modèle Excel. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Le modèle de fichier Excel Office OpenXML (.xltm) représente le format de fichier de modèle Excel. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Signature : [Formats de documents pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* En savoir plus sur la façon d'obtenir la liste des formats pris en charge en C# : [Comment obtenir les formats de fichiers pris en charge dans le code C#](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Voir également

* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
