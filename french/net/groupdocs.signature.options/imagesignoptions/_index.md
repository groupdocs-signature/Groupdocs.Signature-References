---
title: "ImageSignOptions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Représente les options de signature d'image."
type: docs
weight: 1670
url: /fr/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Représente les options de signature d'image.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initialise une nouvelle instance de la classe ImageSignOptions avec le flux d'image. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initialise une nouvelle instance de la classe ImageSignOptions avec le fichier image. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Place la signature sur toutes les pages du document. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence supplémentaire de la signature. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Spécifiez les paramètres de bordure |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenez ou définissez le type de document des options de signature [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtient ou définit l'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtient ou définit le chemin du fichier image de la signature. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtient ou définit le flux d'image de la signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Position X gauche de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document à signer. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle de la zone où placer l'image sur le document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenez le type de signature [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode d'étirement sur Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Position Y supérieure de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Largeur de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Crée une nouvelle instance de la classe ImageSignOptions avec une image prédéfinie depuis Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Efface les ressources internes |

### Remarques

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Voir aussi

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
