---
title: PdfDigitalSignature
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Contient les propriétés de la signature numérique Pdf.
type: docs
weight: 660
url: /fr/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contient les propriétés de la signature numérique Pdf.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialiser la signature numérique PDF sans certificat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Créer une signature numérique PDF avec le certificat spécifié. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialiser la signature numérique PDF en fonction du magasin X509 spécifié. Le premier certificat du magasin spécifié sera utilisé. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Créer une signature numérique PDF basée sur le magasin X509 spécifié et l'index du certificat. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtient ou définit le certificat X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Spécifie l'emplacement du magasin du certificat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Spécifie le nom de magasin du certificat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtient ou définit le commentaire sur l'objet de la signature. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informations fournies par le signataire pour permettre à un destinataire de contacter le signataire pour vérifier la signature, par exemple un numéro de téléphone. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtenir ou définir la date de création de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtenez l'indicateur qui indique si cette signature a été supprimée du document. Cette propriété est utilisée uniquement pour les enregistrements du journal de l'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenir ou définir un indicateur pour indiquer si ce composant est une signature ou un contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Reste vrai si cette signature numérique est valide et que le document n'a pas été falsifié. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Le nom d'hôte du processeur ou l'emplacement physique de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtenir ou définir la date de modification de la signature. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie que la signature de page a été trouvée sur. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | La raison de la signature, telle que (J'accepteРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Forcer à afficher/masquer les propriétés de signature. Si ShowProperties est vrai, le champ signature a un format d'apparence prédéfini Signé numériquement par {[`ContactInfo`](./contactinfo)} Date : {Date} Raison : {[`Reason`](./reason)} Emplacement : {[`Location`](./location) } ShowProperties est vrai par défaut. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant de signature unique pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel de la méthode Sign ou Search. Si cette propriété a été enregistrée avant de pouvoir être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtient ou définit l'heure à laquelle le document a été signé. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtient l'empreinte numérique d'un certificat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Horodatage pour la signature numérique PDF. La valeur par défaut est null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Type de signature numérique PDF. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | type XAdES[`XAdESType`](../digitalsignature/xadestype) . La valeur par défaut est Aucune (XAdES est désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les feuilles de calcul. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Cloner une instance de signature de code-barres. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Remplace la méthode GetHashCode |

### Voir également

* class [DigitalSignature](../digitalsignature)
* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
