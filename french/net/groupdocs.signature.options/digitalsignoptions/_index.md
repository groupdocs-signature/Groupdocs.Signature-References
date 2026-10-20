---
title: "DigitalSignOptions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Représente les options de signature numérique."
type: docs
weight: 1560
url: /fr/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Représente les options de signature numérique.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux du certificat. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier du certificat. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux du certificat et le flux de l'image. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux du certificat et le fichier de l'image. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier du certificat et le flux de l'image. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier du certificat et le fichier de l'image. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Obtient ou définit un indicateur qui permet de signer avec un certificat dont la période de validité est terminée. La valeur par défaut est false : la signature avec un certificat expiré lève [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), et le document n'est pas signé. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Obtient ou définit un indicateur qui permet de signer avec un certificat dont la période de validité n'a pas encore commencé. La valeur par défaut est false : la signature avec un tel certificat lève [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), et le document n'est pas signé. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Place la signature sur toutes les pages du document. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence supplémentaire de la signature. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Spécifiez les paramètres de bordure |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Obtient ou définit le chemin du fichier du certificat numérique. Cette propriété n'est utilisée que si CertificateStream n'est pas spécifié. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Obtient ou définit le flux du certificat numérique. Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Obtient ou définit le contact de la signature. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Obtient ou définit une fonction de signature de hachage personnalisée, permettant aux utilisateurs d'implémenter leur propre logique de signature numérique. Cela permet de signer avec des certificats externes et prend en charge différents algorithmes de hachage. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenez ou définissez le type de document des options de signature [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtient ou définit l'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtient ou définit le chemin du fichier image de la signature. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtient ou définit le flux d'image de la signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Position X gauche de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Obtient ou définit l'emplacement de la signature. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document à signer. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Obtient ou définit le mot de passe du certificat numérique. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Obtient ou définit le motif de la signature. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle de la zone où placer l'image sur le document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Obtient ou définit les propriétés de la signature numérique du document. Pour signer des documents Pdf, il est possible de définir des propriétés avancées en utilisant une instance de [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenez le type de signature [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Mode d'étirement sur Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Position Y supérieure de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Obtient/définit le drapeau de validation ltv (Long Term Validation). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Obtient ou définit la visibilité de la signature. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Largeur de la Signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Type XAdES [`XAdESType`](./xadestype). La valeur par défaut est None (XAdES désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Efface les ressources internes |

### Remarques

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Voir aussi

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
