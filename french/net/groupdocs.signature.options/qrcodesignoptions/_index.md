---
title: "QrCodeSignOptions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Représente les options de signature QRCode."
type: docs
weight: 1920
url: /fr/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Représente les options de signature QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initialise une nouvelle instance de la classe QRCodeSignOptions avec du texte. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Place la signature sur toutes les pages du document. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence supplémentaire de la signature. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Obtient ou définit les paramètres d'arrière-plan de la signature. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Spécifiez les paramètres de bordure |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Obtient ou définit l'alignement du texte dans l'image QR-code résultante. La valeur par défaut est None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Obtient ou définit l'objet personnalisé à sérialiser dans le contenu QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Obtient ou définit l'implémentation de l'interface [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenez ou définissez le type de document des options de signature [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Obtient ou définit le type QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Obtient ou définit la police de la signature. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Obtient ou définit la couleur de premier plan des barres QR-Code. L'utilisation de cette propriété peut entraîner des problèmes de vérification. Utilisez‑la avec précaution. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Obtient ou définit le titre du champ de formulaire texte dans lequel placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Obtient ou définit le type de champ de formulaire pour placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. La valeur par défaut est AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtient ou définit l'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir la propriété [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Obtient ou définit l'espace entre les éléments QR-Code et les bordures de l'image résultante. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir la propriété [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Obtient ou définit le nom de fichier de l'image du logo QR-code. Cette propriété n'est utilisée que si LogoStream n'est pas spécifié. Son utilisation peut entraîner des problèmes de vérification. Utilisez‑la avec précaution. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Obtient ou définit le flux d'image du logo QR-code. Si cette propriété est spécifiée, elle est toujours utilisée à la place de LogoFilePath. Son utilisation peut entraîner des problèmes de vérification. Utilisez‑la avec précaution. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Obtient ou définit l'attribut natif. S'il est défini, des signatures spécifiques au document peuvent être utilisées. Le filigrane texte natif pour les documents WordProcessing est différent du filigrane ordinaire, par exemple. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document à signer. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Obtient ou définit le drapeau permettant d'obtenir le contenu image QR-Code d'une signature placée sur la page du document. Si ce drapeau est vrai, le contenu image de la signature QR-Code conservera les données brutes au format requis [`ReturnContentType`](./returncontenttype). Par défaut, cette option est désactivée. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie que le contenu image QR-Code est renvoyé dans son format d'origine. Ce format d'image est indiqué à [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas supporté, le contenu image QR-Code sera renvoyé au format .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Obtient ou définit le type de forme pour placer du texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextStamp. La valeur par défaut est Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Obtient ou définit l'ID unique de la signature. Il peut être utilisé dans les options de vérification de signature. La propriété est prise en charge uniquement pour les documents Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Obtient ou définit le type d'implémentation de la signature texte. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenez le type de signature [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Mode d'étirement sur Document Page. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Obtient ou définit le texte de la signature. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Alignement horizontal du texte à l'intérieur d'une signature. Cette fonctionnalité est prise en charge uniquement pour les implémentations de signature Image et Annotation (voir la propriété [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Alignement vertical du texte à l'intérieur d'une signature. Cette fonctionnalité est prise en charge uniquement pour l'implémentation de signature Image (voir la propriété [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir la propriété [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir la propriété [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

### Remarques

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Voir aussi

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
