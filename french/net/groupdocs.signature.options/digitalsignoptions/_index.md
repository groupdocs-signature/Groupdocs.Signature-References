---
title: DigitalSignOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de signature numérique.
type: docs
weight: 1260
url: /fr/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Représente les options de signature numérique.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificats. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le flux d'image. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le fichier image. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le flux d'images. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le fichier image. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Mettre la signature sur toutes les pages du document. Cette propriété ne peut être utilisée que pour les formats d'image multi-frames (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence de signature supplémentaire. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Spécifier les paramètres de bordure |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Obtient ou définit le chemin du fichier de certificat numérique. Cette propriété est utilisée uniquement si CertificateStream n'est pas spécifié. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Obtient ou définit le flux de certificat numérique. Si cette propriété est spécifiée, elle est toujours utilisée à la place CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Obtient ou définit le contact de signature. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenir ou définir le type de document des options de signature[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtient ou définit le chemin du fichier image de signature. Cette propriété est utilisée uniquement si ImageStream n'est pas spécifié. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtient ou définit le flux d'image de signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Position X gauche de la signature sur la page du document dans les valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Obtient ou définit l'emplacement de la signature. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Gauche et Haut. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtient ou définit l'espace entre les bords du signe et du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la signature. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Obtient ou définit le mot de passe du certificat numérique. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Obtient ou définit la raison de la signature. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle de zone pour mettre l'image sur le document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Obtient ou définit les propriétés de la signature numérique du document. Pour signer des documents PDF, il est possible de définir des propriétés avancées en utilisant l'instance de[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenir le type de signature[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Largeur et Hauteur. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode d'étirement sur la page de document. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur comprise entre 0,0 (opaque) et 1,0 (clair)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Obtient ou définit la visibilité de la signature. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | type XAdES[`XAdESType`](./xadestype) . La valeur par défaut est Aucune (XAdES est désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les feuilles de calcul. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position de l'ordre Z de la signature textuelle. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Efface les ressources internes |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la création de signature électronique numérique par GroupDocs.Signature : [Comment signer un document électronique avec signature numérique](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Utilisation avancée des paramètres de signature électronique numérique avec GroupDocs.Signature : [Utilisation avancée du document eSign avec signature numérique et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Voir également

* class [ImageSignOptions](../imagesignoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
