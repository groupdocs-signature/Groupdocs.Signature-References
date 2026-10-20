---
title: "PdfDigitalSignature"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Contient les propriétés de signature numérique PDF."
type: docs
weight: 840
url: /fr/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contient les propriétés de signature numérique PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialisez la signature numérique PDF sans certificat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Créez une signature numérique PDF avec le certificat spécifié. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialisez la signature numérique PDF en fonction du magasin X509 spécifié. Le premier certificat du magasin spécifié sera utilisé. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Créez une signature numérique PDF en fonction du magasin X509 spécifié et de l'index du certificat. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtient ou définit le certificat X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Spécifie le nom du magasin personnalisé du certificat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Spécifie l'emplacement du magasin du certificat. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Spécifie le nom du magasin du certificat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtient ou définit le commentaire de l'objet de la signature. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informations fournies par le signataire pour permettre au destinataire de contacter le signataire afin de vérifier la signature, par ex. un numéro de téléphone. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtient ou définit la date de création de la signature. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtient le drapeau indiquant si cette signature a été supprimée du document. Cette propriété n'est utilisée que pour les enregistrements du journal d'historique du document afin de conserver la liste des signatures supprimées. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Spécifie la hauteur de la signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtient ou définit le drapeau indiquant si ce composant est une Signature ou du contenu de document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément de document (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Spécifie la position gauche de la signature. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtient ou définit la date de modification de la signature. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Spécifie la page sur laquelle la signature a été trouvée. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | La raison de la signature, par exemple (I agree…). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Force l'affichage/masquage des propriétés de la signature. Dans le cas où ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini : Signé numériquement par {[`ContactInfo`](./contactinfo)} Date : {Date} Raison : {[`Reason`](./reason)} Lieu : {[`Location`](./location)} ShowProperties est vrai par défaut. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel des méthodes Sign ou Search. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler la signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Spécifie le type de signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtient ou définit l'heure à laquelle le document a été signé. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtient l'empreinte du certificat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Horodatage pour la signature numérique PDF. La valeur par défaut est null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Spécifie la position supérieure de la signature. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Type de signature numérique PDF. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Spécifie la largeur de la signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Type XAdES [`XAdESType`](../digitalsignature/xadestype). La valeur par défaut est None (XAdES désactivé). Pour le moment, le type de signature XAdES n'est pris en charge que pour les documents Tableur. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clonez l'instance de signature de code-barres. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Écrase la méthode Equals pour comparer les propriétés de la signature |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Remplace la méthode GetHashCode |

### Voir aussi

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
