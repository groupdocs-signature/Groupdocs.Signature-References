---
title: "Signature"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Représente la classe principale qui contrôle le processus de signature de document."
type: docs
weight: 2170
url: /fr/net/groupdocs.signature/signature/
---
## Signature class

Représente la classe principale qui contrôle le processus de signature de document.

```csharp
public class Signature : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par un flux. |
| [Signature](signature#constructor_4)(string) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par le chemin du fichier. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par un flux et les options de chargement LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par un flux et les [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par le chemin du fichier et LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par le chemin du fichier et les [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par un flux, les options de chargement LoadOptions et les paramètres [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialise une nouvelle instance de la classe [`Signature`](../signature) avec le document fourni par le chemin du fichier, LoadOptions et les [`SignatureSettings`](../signaturesettings). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Supprime la signature passée [`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Supprime la liste de signatures passée [`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Supprime les signatures d’une certaine liste de types [`SignatureType`](../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) seront supprimées. Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Supprime la liste de signatures passée [`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Supprime les signatures d’un certain type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) seront supprimées. Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Supprime la signature par son identifiant de signature spécifique du document. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implémente l’interface IDisposable pour nettoyer les ressources internes |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Génère un aperçu des pages du document. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale d’une page, la largeur d’une page avec la hauteur maximale. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Recherche des signatures dans le document en utilisant toutes les options de recherche disponibles et filtre les résultats selon le prédicat spécifié. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Recherche les signatures dans un document à l'aide de la liste de [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Recherche les types de signature spécifiés dans le document par la valeur de [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Recherche les signatures dans le document en utilisant les options de recherche fournies et filtre les résultats selon le prédicat spécifié. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Recherche les signatures dans un document à l'aide des options [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Recherche le type exact de signatures dans le document par la valeur de [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signe le document avec une collection de [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Signe le document avec [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signe le document avec une collection de [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Signe le document avec [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signe le document avec une collection de [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux avec les [`SaveOptions`](../../groupdocs.signature.options/saveoptions) prédéfinis. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Signe le document avec [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux avec les [`SaveOptions`](../../groupdocs.signature.options/saveoptions) prédéfinis. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signe le document avec une collection de [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [`SaveOptions`](../../groupdocs.signature.options/saveoptions) prédéfinis. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Signe le document avec [`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [`SaveOptions`](../../groupdocs.signature.options/saveoptions) prédéfinis. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Met à jour la signature passée [`BaseSignature`](../../groupdocs.signature.domain/basesignature) dans le document. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Met à jour les signatures passées [`BaseSignature`](../../groupdocs.signature.domain/basesignature) dans le document. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Vérifie les signatures du document avec une liste de données VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Vérifie les signatures du document avec les données VerifyOptions fournies. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Vérifie les signatures du document en utilisant toutes les options de vérification disponibles et filtre les résultats selon le prédicat spécifié. Cette méthode recherche d'abord les signatures correspondant aux options de vérification, les filtre à l'aide du prédicat, puis ne vérifie que les signatures filtrées. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Vérifie les signatures du document en utilisant les options de vérification fournies et filtre les résultats selon le prédicat spécifié. Cette méthode recherche d'abord les signatures correspondant aux options de vérification, les filtre à l'aide du prédicat, puis ne vérifie que les signatures filtrées. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Génère un aperçu de la signature basé sur les [`SignOptions`](../../groupdocs.signature.options/signoptions) fournis. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Événements

| Nom | Description |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Se produit lorsque le processus de recherche de signature est terminé. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Se produit lorsque la progression du processus de recherche de signature change. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Se produit lorsque le processus de recherche de signature démarre. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Se produit lorsque le processus de signature du document est terminé. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Se produit lorsque la progression du processus de signature du document a changé. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Se produit lorsque le processus de signature du document a démarré. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Se produit lorsque le processus de vérification de la signature est terminé. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Se produit lorsque la progression du processus de vérification de la signature a changé. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Se produit lorsque le processus de vérification de la signature a démarré. |

### Remarques

**Learn more**

Plus d'informations sur les fonctionnalités de GroupDocs.Signature : [Guide du développeur GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Voir aussi

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
