---
title: QrCodeSignOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de signature QRCode.
type: docs
weight: 1550
url: /fr/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Représente les options de signature QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initialise une nouvelle instance de la classe QRCodeSignOptions avec text. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec text. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Mettre la signature sur toutes les pages du document. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apparence de signature supplémentaire. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Obtient ou définit les paramètres d'arrière-plan de la signature. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Spécifier les paramètres de bordure |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Obtient ou définit l'alignement du texte dans l'image de code QR résultante. La valeur par défaut est Aucune. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Obtient ou définit un objet personnalisé à sérialiser en contenu QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Obtient ou définit l'implémentation de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface pour encoder et décoder les propriétés du texte ou des données de la signature QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenir ou définir le type de document des options de signature[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Obtient ou définit le type de code QR. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensions de signature. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Obtient ou définit la police de signature. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Obtient ou définit la couleur de premier plan des barres de code QR L'utilisation de cette propriété peut entraîner des problèmes de vérification. Utilisez-le avec précaution. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Obtient ou définit le titre du champ de formulaire de texte pour y mettre la signature de texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Obtient ou définit le type de champ de formulaire pour y mettre la signature de texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. La valeur par défaut est AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) propriété SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Alignement horizontal de la signature sur la page du document. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Obtient ou définit l'espace entre les éléments QR-Code et les bordures de l'image de résultat. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Position X gauche de la signature sur la page du document dans les valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) Propriété LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Gauche et Haut. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Obtient ou définit le nom du fichier image du logo QR-code. Cette propriété n'est utilisée que si LogoStream n'est pas spécifié. L'utilisation de cette propriété peut entraîner des problèmes de vérification. Utilisez-le avec précaution. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Obtient ou définit le flux d'image du logo QR-code. Si cette propriété est spécifiée, elle est toujours utilisée à la place LogoFilePath. L'utilisation de cette propriété peut entraîner des problèmes de vérification. Utilisez-le avec précaution. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Obtient ou définit l'espace entre les bords du signe et du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Obtient ou définit l'attribut natif. S'il est défini, des signatures spécifiques au document peuvent être utilisées. Le filigrane de texte natif pour les documents de traitement de texte est différent de la norme, par exemple. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la signature. La valeur minimale et par défaut est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options pour spécifier les pages à signer. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Obtient ou définit un indicateur pour obtenir le contenu de l'image QR-Code d'une signature qui a été placée sur la page du document. Si cet indicateur est défini sur vrai, le contenu de l'image de la signature QR-Code conservera les données d'image brutes au format requis[`ReturnContentType`](./returncontenttype) . Par défaut cette option est désactivée. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Spécifie le type de fichier du contenu de l'image renvoyée de la signature QR-Code lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie renvoyer le contenu de l'image QR-Code dans son format d'origine. Ce format d'image est spécifié à[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Les valeurs possibles prises en charge sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas pris en charge, le contenu de l'image QR-Code au format .png sera renvoyé. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Obtient ou définit le type de forme pour mettre du texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextStamp. La valeur par défaut est Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Obtient ou définit l'ID unique de la signature. Il peut être utilisé dans les options de vérification de signature. La propriété est prise en charge uniquement pour les documents PDF. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Obtient ou définit le type d'implémentation de la signature textuelle. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenir le type de signature[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Largeur et Hauteur. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Mode d'étirement sur la page de document. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Obtient ou définit le texte de la signature. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Alignement horizontal du texte à l'intérieur d'une signature. Cette fonctionnalité est prise en charge uniquement pour les implémentations de signature d'image et d'annotation (voir[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Propriété SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Alignement vertical du texte à l'intérieur d'une signature. Cette fonctionnalité est prise en charge uniquement pour la mise en œuvre de la signature d'image (voir[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) propriété SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype)Propriété LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Obtient ou définit la transparence de la signature (valeur comprise entre 0,0 (opaque) et 1,0 (clair)). La valeur par défaut est 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Alignement vertical de la signature sur la page du document. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir[`MeasureType`](../../groupdocs.signature.domain/measuretype) propriété SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtient ou définit la position de l'ordre Z de la signature textuelle. Détermine l'ordre d'affichage des signatures qui se chevauchent. |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la création de signature électronique QR-Code par GroupDocs.Signature : [Comment signer un document avec la signature QR-Code](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Utilisation avancée des paramètres de signature électronique QR-Code avec GroupDocs.Signature : [Utilisation avancée du document eSign avec signature QR-Code et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Voir également

* class [TextSignOptions](../textsignoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
