---
title: QrCodeSearchOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de recherche pour les signatures QRCode.
type: docs
weight: 1620
url: /fr/net/groupdocs.signature.options/qrcodesearchoptions/
---
## QrCodeSearchOptions class

Représente les options de recherche pour les signatures QR-Code.

```csharp
public class QrCodeSearchOptions : SearchOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor)() | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_1)(QrCodeType) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec la valeur de type d'encodage. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_2)(QrCodeType, string) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec le type d'encodage et les valeurs de texte. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicateur de recherche sur chaque page de document. Par défaut, cette valeur est définie sur true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesearchoptions/dataencryption) { get; set; } | Obtient ou définit l'implémentation de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface pour encoder et décoder les propriétés du texte ou des données de la signature QR-Code. |
| [EncodeType](../../groupdocs.signature.options/qrcodesearchoptions/encodetype) { get; set; } | Spécifie la propriété Encode Type pour rechercher des codes QR. Si cette valeur n'est pas définie, la recherche est traitée pour tous les types de code QR pris en charge. |
| [MatchType](../../groupdocs.signature.options/qrcodesearchoptions/matchtype) { get; set; } | Obtient ou définit la recherche de type de correspondance de texte QR-Code. Il est utilisé uniquement lorsque la propriété Text est définie. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la recherche. La valeur est facultative. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Options pour spécifier les pages pour la recherche de signature. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) { get; set; } | Obtient ou définit un indicateur pour saisir le contenu de l'image QR-Code de la signature sur la page du document. Si cet indicateur est défini sur vrai, le contenu de l'image de la signature QR-Code conservera les données d'image brutes au format requis[`ReturnContentType`](./returncontenttype) . Par défaut cette option est désactivée. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesearchoptions/returncontenttype) { get; set; } | Spécifie le type de fichier du contenu de l'image renvoyée de la signature QR-Code lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie renvoyer le contenu de l'image QR-Code dans son format d'origine. Ce format d'image est spécifié à[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Les valeurs possibles prises en charge sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas pris en charge, le contenu de l'image QR-Code en .png d'origine sera renvoyé. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicateur pour renvoyer uniquement les signatures marquées comme IsSignature. Par défaut, la valeur est false qui indique de renvoyer toutes les signatures qui correspondent aux critères spécifiés. |
| [Text](../../groupdocs.signature.options/qrcodesearchoptions/text) { get; set; } | Spécifie le texte de la signature du code QR s'il doit être recherché et mis en correspondance. |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la recherche de signature électronique QR-Code par GroupDocs.Signature : [Comment eRechercher des signatures QR-Code dans un document](https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
* Utilisation avancée des paramètres de recherche de signature électronique QR-Code avec GroupDocs.Signature : [Utilisation avancée des signatures eSearch QR-Code dans un document et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

### Voir également

* class [SearchOptions](../searchoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
