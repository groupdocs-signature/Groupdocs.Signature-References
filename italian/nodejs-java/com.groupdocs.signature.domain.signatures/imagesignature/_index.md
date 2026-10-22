---
title: "ImageSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma Immagine."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Contiene le proprietà della firma Immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Inizializza l'oggetto ImageSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. |
| [ImageSignature()](#ImageSignature--) | Inizializza ImageSignature con i parametri predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Specifica la dimensione in byte dell'immagine della firma. |
| [setSize(int value)](#setSize-int-) | Specifica la dimensione in byte dell'immagine della firma. |
| [getFormat()](#getFormat--) | Specifica il formato dell'immagine della firma. |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il formato dell'immagine della firma. |
| [getContent()](#getContent--) | Specifica il contenuto dei dati binari dell'immagine di tipo  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Barcode Signature. |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Inizializza l'oggetto ImageSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore unico è usato per trovare proprietà aggiuntive per questa firma dal livello di informazioni sulla firma del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | java.lang.String | Identificatore unico della firma ottenuto tramite il metodo Sign o Search della classe Signature [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Inizializza ImageSignature con i parametri predefiniti.

### getSize() {#getSize--}
```
public final int getSize()
```


Specifica la dimensione in byte dell'immagine della firma.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Specifica la dimensione in byte dell'immagine della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifica il formato dell'immagine della firma.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Specifica il formato dell'immagine della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifica il contenuto dei dati binari dell'immagine di tipo  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Per impostazione predefinita questa proprietà non sarà impostata. Usa la proprietà ImageSearchOptions.ReturnContent (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}) per abilitare questa funzionalità.

**Returns:**
byte[]
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


Clona l'istanza di Barcode Signature.

**Returns:**
java.lang.Object - Restituisce un'istanza clonata di Barcode Signature.
