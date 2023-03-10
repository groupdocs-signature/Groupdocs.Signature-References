---
title: Signature
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente la classe principale qui contrôle le processus de signature de document.
type: docs
weight: 1880
url: /fr/net/groupdocs.signature/signature/
---
## Signature class

Représente la classe principale qui contrôle le processus de signature de document.

```csharp
public class Signature : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialise la nouvelle instance de[`Signature`](../signature) classe avec document fourni par stream. |
| [Signature](signature#constructor_4)(string) | Initialise la nouvelle instance de[`Signature`](../signature) instance de classe avec le document fourni par le chemin du fichier. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialise la nouvelle instance de[`Signature`](../signature) classe avec le document fourni par les options de flux et de chargementLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialise la nouvelle instance de[`Signature`](../signature)instance de classe avec le document fourni par le flux et[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialise la nouvelle instance de[`Signature`](../signature) instance de classe avec le document fourni par le chemin du fichier etLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialise la nouvelle instance de[`Signature`](../signature) instance de classe avec le document fourni par le chemin du fichier et[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialise la nouvelle instance de[`Signature`](../signature) instance de classe avec document fourni par stream, options de chargementLoadOptions et paramètres[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialise la nouvelle instance de[`Signature`](../signature) instance de classe avec le document fourni par le chemin du fichier,LoadOptions et[`SignatureSettings`](../signaturesettings) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Supprime la signature transmise[`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Supprime la liste des signatures passées[`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Supprime les signatures de la liste de certains types[`SignatureType`](../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) seront supprimés. Les types de signature suivants sont pris en charge : Texte, Image, Numérique, Code-barres, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Supprime la liste des signatures passées[`BaseSignature`](../../groupdocs.signature.domain/basesignature) du document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Supprime les signatures d'un certain type[`SignatureType`](../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) seront supprimés. Les types de signature suivants sont pris en charge : Texte, Image, Numérique, Code-barres, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Supprime la signature par son identifiant de signature spécifique du document. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implémenter l'interface IDisposable pour nettoyer les ressources internes |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Génère un aperçu des pages du document. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale de la page, la largeur d'une page avec la hauteur maximale. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Recherche les signatures dans un document par[`SearchOptions`](../../groupdocs.signature.options/searchoptions) liste. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Recherche les types de signature spécifiés dans le document en[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valeur. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Recherche les signatures dans un document par[`SearchOptions`](../../groupdocs.signature.options/searchoptions) options. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Recherche le type exact de signatures dans le document par[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valeur. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signe un document avec une collection de[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | signe le document avec[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signe un document avec une collection de[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | signe le document avec[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signe un document avec une collection de[`SignOptions`](../../groupdocs.signature.options/signoptions)et enregistre le résultat dans un flux avec des paramètres prédéfinis[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | signe le document avec[`SignOptions`](../../groupdocs.signature.options/signoptions)et enregistre le résultat dans un flux avec des paramètres prédéfinis[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signe un document avec une collection de[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec prédéfini[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | signe le document avec[`SignOptions`](../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec prédéfini[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Les mises à jour ont passé la signature[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dans le document. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Les mises à jour ont passé les signatures[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dans le document. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Vérifie les signatures des documents avec la liste des données VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Vérifie les signatures des documents avec les données VerifyOptions données. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Génère un aperçu de la signature en fonction des SignOptions données.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Événements

| Nom | La description |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Se produit lorsque le processus de recherche de signature est terminé. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Se produit lorsque la progression du processus de recherche de signature a changé. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Se produit lorsque le processus de recherche de signature a démarré. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Se produit lorsque le processus de signature de document est terminé. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Se produit lorsque la progression du processus de signature de document a changé. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Se produit lorsque le processus de signature de document a démarré. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Se produit lorsque le processus de vérification de signature est terminé. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Se produit lorsque la progression du processus de vérification de signature a changé. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Se produit lorsque le processus de vérification de signature a démarré. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les fonctionnalités de GroupDocs.Signature : [Guide du développeur GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Voir également

* espace de noms [GroupDocs.Signature](../../groupdocs.signature)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
