---
title: PdfMetadataSignature
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Contient les propriétés de signature des métadonnées Pdf.
type: docs
weight: 680
url: /fr/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Contient les propriétés de signature des métadonnées Pdf.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Crée une signature de métadonnées Pdf avec un nom prédéfini et une valeur vide |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Crée une signature de métadonnées PDF avec des valeurs prédéfinies |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Crée une signature de métadonnées PDF avec des valeurs prédéfinies |

## Propriétés

| Nom | La description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtenir ou définir la date de création de la signature. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtient ou définit l'implémentation de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface pour encoder et décoder les propriétés de valeur de signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtenez l'indicateur qui indique si cette signature a été supprimée du document. Cette propriété est utilisée uniquement pour les enregistrements du journal de l'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenir ou définir un indicateur pour indiquer si ce composant est une signature ou un contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtenir ou définir la date de modification de la signature. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Spécifie un nom de métadonnées unique. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie que la signature de page a été trouvée sur. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant de signature unique pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel de la méthode Sign ou Search. Si cette propriété a été enregistrée avant de pouvoir être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | La balise de préfixe du nom de la signature des métadonnées PDF. Par défaut, cette propriété est définie sur "xmp". Les valeurs possibles sont |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Spécifie le type de valeur de métadonnées. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Spécifie l'objet de métadonnées. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Cloner l'instance de signature de métadonnées. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Cloner l'instance de signature de métadonnées PDF avec la valeur donnée. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtenir l'objet à partir de la valeur de signature des métadonnées via la désérialisation. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtenir un objet à partir du texte de signature des métadonnées via la désérialisation. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Remplace la méthode GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Convertit en booléen. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Convertit en DateHeure. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Convertit en DateHeure. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | convertit en décimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | convertit en décimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Convertit en Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Convertit en Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Convertit en entier. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Convertit en float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Convertit en float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Convertit en chaîne avec la méthode override ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | convertit en chaîne avec le format spécifié |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | convertit en chaîne avec le format spécifié |

### Voir également

* class [MetadataSignature](../metadatasignature)
* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
