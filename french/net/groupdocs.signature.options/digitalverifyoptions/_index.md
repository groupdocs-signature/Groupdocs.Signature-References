---
title: "DigitalVerifyOptions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Conserve les options pour vérifier la signature numérique du document."
type: docs
weight: 1570
url: /fr/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

Conserve les options pour vérifier la signature numérique du document.

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | Crée une option de vérification numérique avec les valeurs par défaut. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | Crée une option de vérification numérique avec le flux de certificat fourni. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | Crée une option de vérification numérique avec le chemin de fichier du certificat numérique fourni. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicateur pour vérifier chaque page du document. La valeur par défaut est vraie. |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | Obtient le certificat X509Certificate2 à partir du chemin de fichier ou du flux du certificat. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | Chemin du fichier du certificat numérique. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | Flux du certificat numérique. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | Commentaires de la signature numérique à valider. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | Contact de la signature à valider. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensions supplémentaires pour la vérification des options de signature alternatives. |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | Nom de l'émetteur du certificat à valider. La valeur est sensible à la casse. Si cette propriété est définie, la vérification vérifiera si le nom de l'émetteur de la signature contient ou est égal à la valeur fournie. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Indicateur de propriété valide. |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | Emplacement de la signature à valider. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Numéro de page du document à vérifier. Si la propriété n'est pas définie - toutes les pages du document seront vérifiées pour la première occurrence. La valeur minimale est 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Options de page pour spécifier les pages à vérifier. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | Mot de passe du certificat numérique si requis. |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | Raison de la signature numérique à valider. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Spécifie la position de la forme dans la mise en page du document. Pour la vérification des signatures dans les en-têtes/pieds de page. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | Nom distinctif du sujet du certificat à valider. La valeur est sensible à la casse. Si cette propriété est définie, la vérification vérifiera si le nom du sujet de la signature contient ou est égal à la valeur fournie. |

### Remarques

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings]()

### Voir aussi

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
