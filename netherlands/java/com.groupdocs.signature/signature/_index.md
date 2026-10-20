---
title: "Signature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt de hoofdklasse voor die het ondertekeningsproces van documenten beheert."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Stelt de hoofdklasse voor die het ondertekeningsproces van documenten beheert.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream en laadopties |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream en [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream, laadopties |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) en instellingen [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad en |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad en [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) en [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Ondertekent het document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat het resultaat op naar een stream. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Verifieert de ondertekeningen van het document met de gegeven VerifyOptions-gegevens. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Verifieert de ondertekeningen van het document met een lijst van VerifyOptions-gegevens. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verifieert de ondertekeningen van het document met behulp van de meegeleverde verificatie-opties en filters |
de geslaagde resultaten volgens het opgegeven predicaat.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verifieert de ondertekeningen van het document met een lijst van verificatie-opties en filtert de |
geslaagde resultaten volgens het opgegeven predicaat.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Haalt informatie op over documentpagina's: hun afmetingen, |
maximale paginahoogte, de breedte van een pagina met de maximale hoogte.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Genereert een voorbeeldweergave van documentpagina's. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Zoekt naar ondertekeningen in een document met een lijst van [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Zoekt naar ondertekeningen op basis van een lijst met opties en filtert het resultaat op een predicaat. |
|
|  | [search(Predicate<BaseSignature> predicate)](#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Zoekt in het document naar ondertekeningen van alle typen (tekst, afbeelding, digitaal, barcode, QR-code en metadata) |
en filtert ze op een predicaat.
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Zoekt naar ondertekeningen in een document op basis van [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) opties. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Zoekt naar ondertekeningen van het opgegeven type in het document, eventueel gefilterd op een predicaat. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Zoekt naar exacte ondertekeningstype in het document op basis van de [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) waarde. |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Zoekt naar opgegeven ondertekeningstypen in het document op basis van de [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) waarde. |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Werkt de meegegeven ondertekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Verwijdert doorgegeven handtekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Verwijdert doorgegeven handtekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Verwijdert handtekeningen van een bepaald type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Verwijdert de handtekeningen van de bepaalde typenlijst [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Verwijdert handtekeningen van een bepaald type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Verwijdert de handtekeningen van de bepaalde typenlijst [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Verwijdert handtekening op basis van zijn specifieke handtekening‑Id uit het document. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Genereert handtekeningvoorbeeld op basis van opgegeven SignOptions. |
|
|  | [dispose()](#dispose--) | Implementeer de IDisposable‑interface om interne bronnen op te ruimen |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De inhoudsstroom van het document. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream en laadopties
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De inhoudsstroom van het document. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | De laadopties voor het document. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream en [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De inhoudsstroom van het document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | De handtekeninginstellingen. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een stream, laadopties
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) en instellingen [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De inhoudsstroom van het document. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | De laadopties voor het document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | De handtekeninginstellingen. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Absoluut of relatief bestandspad. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad en
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Absoluut of relatief bestandspad. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | De laadopties voor het document. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad en [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Absoluut of relatief bestandspad. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | De handtekeninginstellingen. |

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


Initialiseert een nieuwe instantie van de [Signature](../../com.groupdocs.signature/signature)‑klasse met een document geleverd via een bestandspad,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) en [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Absoluut of relatief bestandspad. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | De laadopties voor het document. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | De handtekeninginstellingen. |

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


Ondertekent het document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat het resultaat op naar een stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | De handtekeningopties. |

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


Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | De handtekeningopties. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | De opslaan‑opties. |

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


Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | De lijst met handtekeningopties. |

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


Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar een stream met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | De lijst met handtekeningopties. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | De opslaan‑opties. |

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


Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | De handtekeningopties. |

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


Ondertekent document met [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | De handtekeningopties. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | De opslaan‑opties. |

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


Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | De lijst met handtekeningopties. |

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


Ondertekent document met een collectie van [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) en slaat resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | De lijst met handtekeningopties. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | De opslaan‑opties. |

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


Verifieert de ondertekeningen van het document met de gegeven VerifyOptions-gegevens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | De handtekeningverificatie‑opties. |

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


Verifieert de ondertekeningen van het document met een lijst van VerifyOptions-gegevens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | De collectie van handtekeningverificatie‑opties. Een instantie van [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

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


Verifieert de ondertekeningen van het document met behulp van de meegeleverde verificatie-opties en filters
de geslaagde resultaten volgens het opgegeven predicaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | De handtekeningverificatie‑opties. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filterpredicaat toegepast op de lijst met geverifieerde handtekeningen. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Lijst van handtekeningen die de verificatie hebben doorstaan en aan het predicaat voldoen.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Verifieert de ondertekeningen van het document met een lijst van verificatie-opties en filtert de
geslaagde resultaten volgens het opgegeven predicaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | De lijst met handtekeningverificatie‑opties. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filterpredicaat toegepast op de lijst met geverifieerde handtekeningen. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Lijst van handtekeningen die de verificatie hebben doorstaan en aan het predicaat voldoen.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Haalt informatie op over documentpagina's: hun afmetingen,
maximale paginahoogte, de breedte van een pagina met de maximale hoogte.


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


Genereert een voorbeeldweergave van documentpagina's.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | De preview‑opties. |

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


Zoekt naar ondertekeningen in een document met een lijst van [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | De collectie zoekopties. |

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


Zoekt naar ondertekeningen op basis van een lijst met opties en filtert het resultaat op een predicaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | De lijst met zoekopties. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Predicaat gebruikt om de resulterende handtekeningen te filteren. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### search(Predicate<BaseSignature> predicate) {#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> search(Predicate<BaseSignature> predicate)
```


Zoekt in het document naar ondertekeningen van alle typen (tekst, afbeelding, digitaal, barcode, QR-code en metadata)
en filtert ze op een predicaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Het filterpredicaat dat moet worden toegepast op de lijst met gevonden handtekeningen. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Retourneert een lijst van [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) instanties die voldoen aan het opgegeven predicaat.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Zoekt naar ondertekeningen in een document op basis van [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) opties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | De zoekopties. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Retourneert de lijst met gevonden handtekeningen.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Zoekt naar ondertekeningen van het opgegeven type in het document, eventueel gefilterd op een predicaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | Generieke typeparameter van [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Opties voor handtekening zoeken. |
|
|  | predicate | java.util.function.Predicate<T> | Optioneel predicaatfilter toegepast na de zoekopdracht. Kan null zijn. |
|

**Returns:**
java.util.List<T> - Lijst van gevonden handtekeningen, eventueel gefilterd door het predicaat.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Zoekt naar exacte ondertekeningstype in het document op basis van de [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Het type handtekeningen om te zoeken. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Retourneert de lijst met gevonden handtekeningen met exact type.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Zoekt naar opgegeven ondertekeningstypen in het document op basis van de [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureTypes | int[] | Een of meerdere typen handtekeningen om te vinden. |

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


Werkt de meegegeven ondertekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Handtekeningobject dat moet worden bijgewerkt in het document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Retourneert true als de bewerking succesvol was.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | handtekeningen | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Lijst met handtekeningen om bij te werken in het document. |

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


Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | handtekeningen | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Lijst met handtekeningen om bij te werken in het document. |

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


Werk de doorgegeven handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bij in het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Handtekeningobject dat moet worden bijgewerkt in het document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Retourneert UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) met een lijst van succesvol bijgewerkte handtekeningen en mislukte.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Verwijdert doorgegeven handtekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Handtekeningobject dat moet worden verwijderd uit het document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Retourneert true als de bewerking succesvol was.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | handtekeningen | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Lijst met handtekeningen om te verwijderen uit het document. |

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


Verwijdert doorgegeven handtekening [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Handtekeningobject dat moet worden verwijderd uit het document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Retourneert true als de bewerking succesvol was.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | handtekeningen | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Lijst met handtekeningen om te verwijderen uit het document. |

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


Verwijdert handtekeningen van een bepaald type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document.
Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd als Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) zal worden verwijderd.
De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signatureType | int | Het type handtekeningen dat moet worden verwijderd uit het document. |

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


Verwijdert de handtekeningen van de bepaalde typenlijst [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document.
Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd als Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) zal worden verwijderd.
De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De uitvoer‑documentstroom. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | De lijst met handtekeningtypen die moeten worden verwijderd uit het document. |

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


Verwijdert handtekeningen van een bepaald type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document.
Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd als Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) zal worden verwijderd.
De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signatureType | int | Het type handtekeningen dat moet worden verwijderd uit het document. |

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


Verwijdert de handtekeningen van de bepaalde typenlijst [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) uit het document.
Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd als Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) zal worden verwijderd.
De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het uitvoer‑bestandspad. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | De lijst met handtekeningtypen die moeten worden verwijderd uit het document. |

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


Verwijdert handtekening op basis van zijn specifieke handtekening‑Id uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureId | java.lang.String | De Id van de handtekening die moet worden verwijderd uit het document. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - Retourneert true als de bewerking succesvol was.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Verwijdert doorgegeven lijst van handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) uit het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Lijst met de identifiers van de handtekeningen die moeten worden verwijderd uit het document. |

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


Genereert een handtekeningvoorbeeld op basis van de gegeven SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Het voorbeeld van de handtekening met de gegeven SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


Implementeer de IDisposable‑interface om interne bronnen op te ruimen


