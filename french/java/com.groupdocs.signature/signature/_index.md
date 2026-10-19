---
title: "Signature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente la classe principale qui contrôle le processus de signature de documents."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Représente la classe principale qui contrôle le processus de signature de documents.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux et les options de chargement |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux et [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux, les options de chargement |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) et les paramètres [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier et |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier et [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) et [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis. |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis. |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Vérifie les signatures du document avec les données VerifyOptions fournies. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Vérifie les signatures du document avec une liste de données VerifyOptions. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Vérifie les signatures du document en utilisant les options de vérification fournies et les filtres |
les résultats réussis selon le prédicat spécifié.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Vérifie les signatures du document en utilisant une liste d'options de vérification et filtre le |
résultats réussis selon le prédicat spécifié.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtient des informations sur les pages du document : leurs tailles, |
hauteur maximale de page, la largeur d'une page avec la hauteur maximale.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Génère un aperçu des pages du document. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Recherche des signatures dans un document par liste de [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Recherche des signatures par une liste d'options et filtre le résultat selon un prédicat. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Recherche des signatures dans un document par les options [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Recherche des signatures du type spécifié dans le document, éventuellement filtrées par un prédicat. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Recherche le type exact de signatures dans le document par la valeur [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Recherche les types de signatures spécifiés dans le document par la valeur [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Met à jour la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Supprime la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Supprime la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Supprime les signatures d'un certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Supprime les signatures de la liste de certains types [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Supprime les signatures d'un certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Supprime les signatures de la liste de certains types [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Supprime la signature par son identifiant de signature spécifique du document. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Génère un aperçu de la signature basé sur les SignOptions fournis. |
|
|  | [dispose()](#dispose--) | Implémente l'interface IDisposable pour nettoyer les ressources internes |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux de contenu du document. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux et les options de chargement
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux de contenu du document. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Les options de chargement du document. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux et [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux de contenu du document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Les paramètres de la signature. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par un flux, les options de chargement
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) et les paramètres [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux de contenu du document. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Les options de chargement du document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Les paramètres de la signature. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin de fichier absolu ou relatif. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier et
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin de fichier absolu ou relatif. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Les options de chargement du document. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier et [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin de fichier absolu ou relatif. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Les paramètres de la signature. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Initialise une nouvelle instance de la classe [Signature](../../com.groupdocs.signature/signature) avec le document fourni par le chemin du fichier,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) et [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Chemin de fichier absolu ou relatif. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Les options de chargement du document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Les paramètres de la signature. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Les options de signature. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Les options de signature. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Les options d'enregistrement. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | La liste des options de signature. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat dans un flux avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | La liste des options de signature. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Les options d'enregistrement. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Les options de signature. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Signe le document avec [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Les options de signature. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Les options d'enregistrement. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | La liste des options de signature. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Signe le document avec une collection de [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) et enregistre le résultat à l'emplacement de fichier spécifié avec les [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) prédéfinis.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | La liste des options de signature. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Les options d'enregistrement. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Vérifie les signatures du document avec les données VerifyOptions fournies.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Les options de vérification de la signature. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Vérifie les signatures du document avec une liste de données VerifyOptions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | La collection d'options de vérification de la signature. Instance de [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


Vérifie les signatures du document en utilisant les options de vérification fournies et les filtres
les résultats réussis selon le prédicat spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Les options de vérification de la signature. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Prédicat de filtrage appliqué sur la liste des signatures vérifiées. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Liste des signatures qui ont réussi la vérification et satisfait le prédicat.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Vérifie les signatures du document en utilisant une liste d'options de vérification et filtre le
résultats réussis selon le prédicat spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | La liste des options de vérification de signature. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Prédicat de filtrage appliqué sur la liste des signatures vérifiées. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Liste des signatures qui ont réussi la vérification et satisfait le prédicat.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtient des informations sur les pages du document : leurs tailles,
hauteur maximale de page, la largeur d'une page avec la hauteur maximale.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Génère un aperçu des pages du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Les options d'aperçu. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Recherche des signatures dans un document par liste de [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | La collection d'options de recherche. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


Recherche des signatures par une liste d'options et filtre le résultat selon un prédicat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | La liste des options de recherche. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Prédicat utilisé pour filtrer les signatures résultantes. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Recherche des signatures dans un document par les options [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Les options de recherche. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Retourne la liste des signatures trouvées.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Recherche des signatures du type spécifié dans le document, éventuellement filtrées par un prédicat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | Paramètre de type générique de [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Options pour la recherche de signature. |
|
|  | predicate | java.util.function.Predicate<T> | Filtre de prédicat optionnel appliqué après la recherche. Peut être null. |
|

**Returns:**
java.util.List<T> - Liste des signatures trouvées, éventuellement filtrées par le prédicat.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Recherche le type exact de signatures dans le document par la valeur [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Le type de signatures à rechercher. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Retourne la liste des signatures trouvées avec le type exact.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Recherche les types de signatures spécifiés dans le document par la valeur [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatureTypes | int[] | Un ou plusieurs types de signatures à trouver. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Met à jour la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objet de signature à mettre à jour dans le document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Retourne true si l'opération a réussi.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste des signatures à mettre à jour dans le document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste des signatures à mettre à jour dans le document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Met à jour les signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) dans le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objet de signature à mettre à jour dans le document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Retourne UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) avec la liste des signatures mises à jour avec succès et celles qui ont échoué.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Supprime la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objet Signature à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Retourne true si l'opération a réussi.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste des signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Supprime la signature passée [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objet Signature à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Retourne true si l'opération a réussi.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste des signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Supprime les signatures d'un certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document.
Uniquement les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) sera supprimé.
Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signatureType | int | Le type de signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Supprime les signatures de la liste de certains types [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document.
Uniquement les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) sera supprimé.
Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux du document de sortie. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | La liste des types de signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Supprime les signatures d'un certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document.
Uniquement les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) sera supprimé.
Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signatureType | int | Le type de signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Supprime les signatures de la liste de certains types [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) du document.
Uniquement les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) sera supprimé.
Les types de signature suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier de sortie. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | La liste des types de signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Supprime la signature par son identifiant de signature spécifique du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatureId | java.lang.String | L'Id de la signature à supprimer du document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - Retourne true si l'opération a réussi.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Supprime la liste de signatures passées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Liste des identifiants des signatures à supprimer du document. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Génère un aperçu de Signature basé sur les SignOptions fournis. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | L'aperçu de la signature avec les SignOptions fournis. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


Implémente l'interface IDisposable pour nettoyer les ressources internes


