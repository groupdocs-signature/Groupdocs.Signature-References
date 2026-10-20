---
title: "SpreadsheetMetadataSignature"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Contient les propriétés de signature des métadonnées de la feuille de calcul."
type: docs
weight: 1060
url: /fr/net/groupdocs.signature.domain/spreadsheetmetadatasignature/
---
## SpreadsheetMetadataSignature class

Contient les propriétés de signature des métadonnées de la feuille de calcul.

```csharp
public sealed class SpreadsheetMetadataSignature : MetadataSignature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor)(string) | Crée Spreadsheet Metadata Signature avec un nom prédéfini et une valeur vide. |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor_1)(string, object) | Crée Spreadsheet Metadata Signature avec des valeurs prédéfinies. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtient ou définit la date de création de la signature. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtient ou définit l'implémentation de l'interface [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtient le drapeau indiquant si cette signature a été supprimée du document. Cette propriété n'est utilisée que pour les enregistrements du journal d'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtient ou définit le drapeau indiquant si ce composant est une Signature ou du contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtient ou définit la date de modification de la signature. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Spécifie le nom unique des métadonnées. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie la page sur laquelle la signature a été trouvée. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel des méthodes Sign ou Search. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Spécifie le type de valeur des métadonnées. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Spécifie l'objet de métadonnées. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone_1)() | Clone l'instance de Signature de métadonnées. |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone)(object) | Clone l'instance de Spreadsheet Metadata Signature avec la valeur donnée. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtient l'objet à partir de la valeur de la signature de métadonnées lors de la désérialisation. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtient l'objet à partir du texte de la signature de métadonnées lors de la désérialisation. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Remplace la méthode GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Convertit en booléen. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Convertit en DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Convertit en DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Convertit en Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Convertit en Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Convertit en Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Convertit en Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Convertit en entier. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Convertit en float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Convertit en float. |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring)() | Convertit en chaîne avec la méthode ToString() surchargée |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Convertit en chaîne avec le format spécifié |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convertit en chaîne avec le format spécifié |

### Voir aussi

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
