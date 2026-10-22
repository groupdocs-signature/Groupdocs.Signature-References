---
title: "SignOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di firma."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Rappresenta le opzioni di firma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il numero di pagina del documento per la firma. |
| [setPageNumber(int value)](#setPageNumber-int-) | Ottiene o imposta il numero di pagina del documento per la firma. |
| [getAllPages()](#getAllPages--) | Inserisci la firma su tutte le pagine del documento. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Inserisci la firma su tutte le pagine del documento. |
| [getAppearance()](#getAppearance--) | Aspetto aggiuntivo della firma. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Aspetto aggiuntivo della firma. |
| [getExtensions()](#getExtensions--) | Estensioni della firma. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Estensioni della firma. |
| [getPagesSetup()](#getPagesSetup--) | Opzioni per specificare le pagine da firmare. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opzioni per specificare le pagine da firmare. |
| [getSignatureType()](#getSignatureType--) | Ottieni il tipo di firma [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | Ottieni o imposta il tipo di documento delle opzioni di firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | Ottieni o imposta il tipo di documento delle opzioni di firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | Ottiene o imposta la posizione Z-order della firma di testo. |
| [setZOrder(int value)](#setZOrder-int-) | Ottiene o imposta la posizione Z-order della firma di testo. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Inserisci la firma su tutte le pagine del documento.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Inserisci la firma su tutte le pagine del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Aspetto aggiuntivo della firma.

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Aspetto aggiuntivo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Estensioni della firma.

**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Estensioni della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opzioni per specificare le pagine da firmare.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opzioni per specificare le pagine da firmare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Ottieni il tipo di firma [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Ottieni o imposta il tipo di documento delle opzioni di firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Ottieni o imposta il tipo di documento delle opzioni di firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Ottiene o imposta la posizione Z-order della firma di testo. Determina l'ordine di visualizzazione delle firme sovrapposte.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Ottiene o imposta la posizione Z-order della firma di testo. Determina l'ordine di visualizzazione delle firme sovrapposte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
