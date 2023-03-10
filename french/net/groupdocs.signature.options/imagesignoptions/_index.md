---
title: ImageSignOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de signature dimage.
type: docs
weight: 1420
url: /fr/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Représente les options de signature d'image.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initialise une nouvelle instance de la classe ImageSignOptions avec le flux d'images. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initialise une nouvelle instance de la classe ImageSignOptions avec le fichier image. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Mettre la signature sur toutes les pages du document. Cette propriété ne peut être utilisée que pour les formats d'image multi-frames (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence de signature supplémentaire. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Spécifier les paramètres de bordure |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenir ou définir le type de document des options de signature[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtient ou définit le chemin du fichier image de signature. Cette propriété est utilisée uniquement si ImageStream n'est pas spécifié. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtient ou définit le flux d'image de signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Position X gauche de la signature sur la page du document dans les valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Gauche et Haut. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtient ou définit l'espace entre les bords du signe et du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la signature. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle de zone pour mettre l'image sur le document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenir le type de signature[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Largeur et Hauteur. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode d'étirement sur la page de document. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur comprise entre 0,0 (opaque) et 1,0 (clair)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position de l'ordre Z de la signature textuelle. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Crée une nouvelle instance de la classe ImageSignOptions avec Image prédéfinie de Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Efface les ressources internes |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la création de signature électronique d'image par GroupDocs.Signature : [Comment signer un document électronique avec une signature d'image](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Utilisation avancée des paramètres de signature électronique d'image avec GroupDocs.Signature : [Utilisation avancée du document eSign avec signature d'image et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Voir également

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
