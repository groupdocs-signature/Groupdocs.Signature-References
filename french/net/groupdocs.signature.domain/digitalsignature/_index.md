---
title: DigitalSignature
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Contient les propriétés de la signature numérique.
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

| Nom | La description |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialiser la signature numérique avec les paramètres par défaut. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialiser la signature numérique avec un identifiant de signature connu. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Créer une signature numérique avec le certificat spécifié. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Créer une signature numérique basée sur le magasin X509 spécifié. Le premier certificat du magasin spécifié sera utilisé. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Créer une signature numérique basée sur le magasin X509 spécifié et l'index du certificat. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtient ou définit le certificat X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Spécifie l'emplacement du magasin du certificat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Spécifie le nom de magasin du certificat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtient ou définit le commentaire sur l'objet de la signature. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtenir ou définir la date de création de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtenez l'indicateur qui indique si cette signature a été supprimée du document. Cette propriété est utilisée uniquement pour les enregistrements du journal de l'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenir ou définir un indicateur pour indiquer si ce composant est une signature ou un contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Reste vrai si cette signature numérique est valide et que le document n'a pas été falsifié. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtenir ou définir la date de modification de la signature. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie que la signature de page a été trouvée sur. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant de signature unique pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel de la méthode Sign ou Search. Si cette propriété a été enregistrée avant de pouvoir être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtient ou définit l'heure à laquelle le document a été signé. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtient l'empreinte numérique d'un certificat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | type XAdES[`XAdESType`](./xadestype) . La valeur par défaut est Aucune (XAdES est désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les feuilles de calcul. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Cloner une instance de signature de code-barres. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Remplace la méthode GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Charger la signature numérique de tous les magasins de certificats X509 du système. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Charger la signature numérique à partir du magasin de certificats X509 passé. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Charger la signature numérique à partir du magasin de certificats X509 passé. |

### Voir également

* class [BaseSignature](../basesignature)
* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
