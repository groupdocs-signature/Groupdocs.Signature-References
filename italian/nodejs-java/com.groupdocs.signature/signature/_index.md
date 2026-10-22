---
title: "Firma"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta la classe principale che controlla il processo di firma del documento."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Rappresenta la classe principale che controlla il processo di firma del documento.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream e opzioni di caricamento LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream e [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream, opzioni di caricamento LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) e impostazioni [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath)](#Signature-java.lang.String-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file e LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file e [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file, LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) e [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite. |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite. |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite. |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite. |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Verifica le firme del documento con i dati VerifyOptions forniti. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Verifica le firme del documento con un elenco di dati VerifyOptions. |
| [getDocumentInfo()](#getDocumentInfo--) | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Genera l'anteprima delle pagine del documento. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Cerca firme in un documento tramite un elenco di [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Cerca firme in un documento tramite le opzioni [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Cerca il tipo esatto di firme nel documento tramite il valore [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [search(int[] signatureTypes)](#search-int...-) | Cerca i tipi di firma specificati nel documento tramite il valore [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aggiorna la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita nel documento. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Elimina la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita dal documento. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Elimina la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita dal documento. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Elimina le firme di un certo tipo [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Elimina le firme dell'elenco di tipi specifici [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Elimina le firme di un certo tipo [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Elimina le firme dell'elenco di tipi specifici [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. |
| [delete(String signatureId)](#delete-java.lang.String-) | Elimina la firma per il suo Id specifico dal documento. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Genera l'anteprima della firma basata su SignOptions forniti. |
| [dispose()](#dispose--) | Implementa l'interfaccia IDisposable per pulire le risorse interne |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso di contenuto del documento. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream e opzioni di caricamento LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Il flusso di contenuto del documento. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Le opzioni di caricamento del documento. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream e [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Il flusso di contenuto del documento. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Le impostazioni della firma. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite stream, opzioni di caricamento LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) e impostazioni [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Il flusso di contenuto del documento. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Le opzioni di caricamento del documento. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Le impostazioni della firma. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso file assoluto o relativo. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file e LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso file assoluto o relativo. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Le opzioni di caricamento del documento. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file e [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso file assoluto o relativo. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Le impostazioni della firma. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Inizializza una nuova istanza della classe [Signature](../../com.groupdocs.signature/signature) con documento fornito tramite percorso file, LoadOptions (\\#getLoadOptions.getLoadOptions/\\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) e [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso file assoluto o relativo. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Le opzioni di caricamento del documento. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Le impostazioni della firma. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Le opzioni della firma. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Le opzioni della firma. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Le opzioni di salvataggio. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | L'elenco delle opzioni della firma. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato in uno stream con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | L'elenco delle opzioni della firma. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Le opzioni di salvataggio. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Le opzioni della firma. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Firma il documento con [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Le opzioni della firma. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Le opzioni di salvataggio. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | L'elenco delle opzioni della firma. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Firma il documento con una collezione di [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) e salva il risultato nel percorso file specificato con [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | L'elenco delle opzioni della firma. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Le opzioni di salvataggio. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Verifica le firme del documento con i dati VerifyOptions forniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Le opzioni di verifica della firma. |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Verifica le firme del documento con un elenco di dati VerifyOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | La collezione delle opzioni di verifica della firma. Istanza di [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima.

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genera l'anteprima delle pagine del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Le opzioni di anteprima. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Cerca firme in un documento tramite un elenco di [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | La collezione delle opzioni di ricerca. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Cerca firme in un documento tramite le opzioni [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Le opzioni di ricerca. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Restituisce l'elenco delle firme trovate.
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Cerca il tipo esatto di firme nel documento tramite il valore [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Il tipo di firme da cercare. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Restituisce l'elenco delle firme trovate con il tipo esatto.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Cerca i tipi di firma specificati nel documento tramite il valore [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signatureTypes | int[] | Uno o più tipi di firme da trovare. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.
### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Aggiorna la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita nel documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Oggetto firma da aggiornare nel documento. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Restituisce true se l'operazione è riuscita.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | firme | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Elenco delle firme da aggiornare nel documento. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | firme | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Elenco delle firme da aggiornare nel documento. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Aggiorna le firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornite nel documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Oggetto firma da aggiornare nel documento. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Restituisce UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) con l'elenco delle firme aggiornate con successo e quelle fallite.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Elimina la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Oggetto firma da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Restituisce true se l'operazione è riuscita.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | firme | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Elenco delle firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Elimina la firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornita dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Oggetto firma da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Restituisce true se l'operazione è riuscita.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | firme | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Elenco delle firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Elimina le firme di un determinato tipo [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. Solo le firme aggiunte con il metodo Sign e contrassegnate come Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) saranno rimosse. I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signatureType | int | Il tipo di firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Elimina le firme di un elenco di determinati tipi [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. Solo le firme aggiunte con il metodo Sign e contrassegnate come Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) saranno rimosse. I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso di output del documento. |
|  | signatureTypes | java.util.List<java.lang.Integer> | L'elenco dei tipi di firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Elimina le firme di un determinato tipo [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. Solo le firme aggiunte con il metodo Sign e contrassegnate come Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) saranno rimosse. I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signatureType | int | Il tipo di firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Elimina le firme di un elenco di determinati tipi [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dal documento. Solo le firme aggiunte con il metodo Sign e contrassegnate come Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) saranno rimosse. I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file di output. |
|  | signatureTypes | java.util.List<java.lang.Integer> | L'elenco dei tipi di firme da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Elimina la firma per il suo Id specifico dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signatureId | java.lang.String | L'Id della firma da rimuovere dal documento. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - Restituisce true se l'operazione è riuscita.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Elimina l'elenco di firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) fornito dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Elenco degli identificatori delle firme da rimuovere dal documento. |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Genera l'anteprima della firma basata su SignOptions forniti. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | L'anteprima della firma con i SignOptions forniti. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


Implementa l'interfaccia IDisposable per pulire le risorse interne

