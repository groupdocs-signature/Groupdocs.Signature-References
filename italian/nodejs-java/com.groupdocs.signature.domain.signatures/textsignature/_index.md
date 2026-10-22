---
title: "TextSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma Testo."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Contiene le proprietà della firma Testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Inizializza l'oggetto TextSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. |
| [TextSignature()](#TextSignature--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Specifica il testo nella firma. |
| [setText(String value)](#setText-java.lang.String-) | Specifica il testo nella firma. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Specifica l'implementazione della firma testuale. |
| [getNative()](#getNative--) | Specifica l'attributo nativo. |
| [setNative(boolean value)](#setNative-boolean-) | Specifica l'attributo nativo. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Text Signature. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Inizializza l'oggetto TextSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore univoco è utilizzato per trovare proprietà aggiuntive per questa firma dallo strato di informazioni sulla firma del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | java.lang.String | Identificatore unico della firma ottenuto tramite il metodo di firma o di ricerca. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Specifica il testo nella firma.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifica il testo nella firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Specifica l'implementazione della firma testuale.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Specifica l'attributo nativo. È true se la firma è specifica del documento.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Specifica l'attributo nativo. È true se la firma è specifica del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sovrascrive il metodo Equals per confrontare le proprietà della firma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | java.lang.Object | Oggetto firma con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto firma passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash della firma
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza di Text Signature.

**Returns:**
java.lang.Object - Restituisce un'istanza clonata di Text Signature.
