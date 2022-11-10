---
title: ImageMetadataSignature
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Contient les propriétés de signature des métadonnées dimage.
type: docs
weight: 550
url: /fr/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Contient les propriétés de signature des métadonnées d'image.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | crée une signature de métadonnées d'image avec un identifiant et une valeur |

## Propriétés

| Nom | La description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtenir ou définir la date de création de la signature. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtient ou définit l'implémentation de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface pour encoder et décoder les propriétés de valeur de signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtenez l'indicateur qui indique si cette signature a été supprimée du document. Cette propriété est utilisée uniquement pour les enregistrements du journal de l'historique du document afin de conserver la liste des signatures supprimées. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Valeur en lecture seule pour obtenir la description de la signature standard des métadonnées d'image |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | L'identifiant de la signature des métadonnées d'image. VoirImageMetadataSignatures classe contenant une signature standard avec une valeur d'ID prédéfinie. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenir ou définir un indicateur pour indiquer si ce composant est une signature ou un contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtenir ou définir la date de modification de la signature. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Spécifie un nom de métadonnées unique. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie que la signature de page a été trouvée sur. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant de signature unique pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel de la méthode Sign ou Search. Si cette propriété a été enregistrée avant de pouvoir être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Valeur en lecture seule pour obtenir la taille de la valeur des métadonnées |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Spécifie l'objet de métadonnées. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Cloner l'instance de signature de métadonnées. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Cloner l'instance de signature de métadonnées d'image avec la valeur donnée. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtenir l'objet à partir de la valeur de signature des métadonnées via la désérialisation. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtenir un objet à partir du texte de signature des métadonnées via la désérialisation. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Remplace la méthode GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Convertit en booléen. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Convertit en DateHeure. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Convertit en DateHeure. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | convertit en décimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | convertit en décimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Convertit en Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Convertit en Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Convertit en entier. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Convertit en long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Convertit en float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Convertit en float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Convertit en chaîne avec la méthode override ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | convertit en chaîne avec le format spécifié |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | convertit en chaîne avec le format spécifié |

### Voir également

* class [MetadataSignature](../metadatasignature)
* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
