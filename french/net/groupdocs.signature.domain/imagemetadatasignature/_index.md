---
title: "ImageMetadataSignature"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Contient les propriétés de signature des métadonnées d'image."
type: docs
weight: 740
url: /fr/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Contient les propriétés de signature des métadonnées d'image.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Crée Image Metadata Signature avec Id et valeur |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtient ou définit la date de création de la signature. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtient ou définit l'implémentation de l'interface [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtient le drapeau indiquant si cette signature a été supprimée du document. Cette propriété n'est utilisée que pour les enregistrements du journal d'historique du document afin de conserver la liste des signatures supprimées. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Valeur en lecture seule pour obtenir la description de la signature Image Metadata standard |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | L'identifiant de la signature des métadonnées d'image. Voir la classe ImageMetadataSignatures qui contient la signature standard avec une valeur Id prédéfinie. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtient ou définit le drapeau indiquant si ce composant est une Signature ou du contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtient ou définit la date de modification de la signature. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Spécifie le nom unique des métadonnées. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie la page sur laquelle la signature a été trouvée. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel des méthodes Sign ou Search. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Valeur en lecture seule pour obtenir la taille de la valeur des métadonnées |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Spécifie le type de valeur des métadonnées. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Spécifie l'objet de métadonnées. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clone l'instance de Signature de métadonnées. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Cloner l'instance de la signature des métadonnées d'image avec la valeur donnée. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtient l'objet à partir de la valeur de la signature de métadonnées lors de la désérialisation. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtient l'objet à partir du texte de la signature de métadonnées lors de la désérialisation. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Remplace la méthode GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Convertit en booléen. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Convertit en DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Convertit en DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Convertit en Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Convertit en Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Convertit en Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Convertit en Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Convertit en entier. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Convertit en long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Convertit en float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Convertit en float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Convertit en chaîne avec la méthode ToString() surchargée |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Convertit en chaîne avec le format spécifié |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convertit en chaîne avec le format spécifié |

### Voir aussi

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
