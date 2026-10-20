---
title: "StampSignOptions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Représente les options de signature de tampon."
type: docs
weight: 2000
url: /fr/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Représente les options de signature de tampon.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Initialise une nouvelle instance de la classe StampSignOptions avec les valeurs par défaut. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Initialise une nouvelle instance de la classe StampSignOptions avec des options d'alignement. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Place la signature sur toutes les pages du document. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence supplémentaire de la signature. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Obtient ou définit l'arrière-plan du Stamp. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Obtient ou définit le type de recadrage de couleur d'arrière-plan de la signature. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Obtient ou définit le type de recadrage d'image d'arrière-plan de la signature. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Spécifiez les paramètres de bordure |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenez ou définissez le type de document des options de signature [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtient ou définit l'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtient ou définit le chemin du fichier image de la signature. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtient ou définit le flux d'image de la signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Liste des lignes internes rendues sous forme d'ensemble de rectangles. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Position X gauche de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Liste des lignes externes rendues sous forme de cercles concentriques. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document à signer. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle de la zone où placer l'image sur le document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenez le type de signature [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Obtient ou définit le type de tampon. La valeur par défaut est Rond. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode d'étirement sur Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Position Y supérieure de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Largeur de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Efface les ressources internes |

### Remarques

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Voir aussi

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
