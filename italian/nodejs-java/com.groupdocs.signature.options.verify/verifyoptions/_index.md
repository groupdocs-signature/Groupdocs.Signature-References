---
title: "VerifyOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Mantiene le opzioni per verificare il documento."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Mantiene le opzioni per verificare il documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isValid()](#isValid--) | Flag della proprietà valida. |
| [setValid(boolean value)](#setValid-boolean-) | Flag della proprietà valida. |
| [getPageNumber()](#getPageNumber--) | Numero di pagina del documento da verificare. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Numero di pagina del documento da verificare. |
| [getPagesSetup()](#getPagesSetup--) | Opzioni di pagina per specificare le pagine da verificare. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opzioni di pagina per specificare le pagine da verificare. |
| [getAllPages()](#getAllPages--) | Flag per verificare ogni pagina del documento. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Flag per verificare ogni pagina del documento. |
| [getExtensions()](#getExtensions--) | Estensioni aggiuntive per la verifica delle opzioni di firma alternative. |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Estensioni aggiuntive per la verifica delle opzioni di firma alternative. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
### isValid() {#isValid--}
```
public final boolean isValid()
```


Flag della proprietà valida.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Flag della proprietà valida.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento verranno verificate per la prima occorrenza. Il valore minimo è 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento verranno verificate per la prima occorrenza. Il valore minimo è 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opzioni di pagina per specificare le pagine da verificare.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opzioni di pagina per specificare le pagine da verificare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag per verificare ogni pagina del documento. Il valore predefinito è true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag per verificare ogni pagina del documento. Il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Estensioni aggiuntive per la verifica delle opzioni di firma alternative.

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Estensioni aggiuntive per la verifica delle opzioni di firma alternative.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
