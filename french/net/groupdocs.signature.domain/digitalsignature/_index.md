---
title: "DigitalSignature"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Contient les propriétés de la signature numérique."
type: docs
weight: 150
url: /fr/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Contient les propriétés de la signature numérique.

```csharp
public class DigitalSignature : BaseSignature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialise la signature numérique avec les paramètres par défaut. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialise la signature numérique avec un SignatureId connu. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Crée une signature numérique avec le certificat spécifié. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Crée une signature numérique basée sur le magasin X509 spécifié. Le premier certificat du magasin spécifié sera utilisé. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Crée une signature numérique basée sur le magasin X509 spécifié et l'index du certificat. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtient ou définit le certificat X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Spécifie le nom du magasin personnalisé du certificat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Spécifie l'emplacement du magasin du certificat. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Spécifie le nom du magasin du certificat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtient ou définit le commentaire de l'objet de la signature. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtient ou définit la date de création de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtient le drapeau indiquant si cette signature a été supprimée du document. Cette propriété n'est utilisée que pour les enregistrements du journal d'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtient ou définit le drapeau indiquant si ce composant est une Signature ou du contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtient ou définit la date de modification de la signature. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie la page sur laquelle la signature a été trouvée. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel des méthodes Sign ou Search. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtient ou définit l'heure à laquelle le document a été signé. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtient l'empreinte du certificat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Type XAdES [`XAdESType`](./xadestype). La valeur par défaut est None (XAdES désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clonez l'instance de signature de code-barres. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Remplace la méthode GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Charge les signatures numériques depuis tous les magasins de certificats X509 du système. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Charge les signatures numériques depuis un stockage de certificats. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Charge les signatures numériques depuis un stockage de certificats. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Charge les signatures numériques depuis un stockage de certificats numériques placé à un emplacement spécifique. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Charge les signatures numériques depuis un stockage de certificats numériques placé à un emplacement spécifique. |

### Voir aussi

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
