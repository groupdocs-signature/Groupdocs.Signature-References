---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma Barcode."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Contiene le proprietà della firma Barcode.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Inizializza l'oggetto BarcodeSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. |
| [BarcodeSignature()](#BarcodeSignature--) | Inizializza BarcodeSignature con parametri predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifica il tipo di codifica del Barcode. |
| [getText()](#getText--) | Specifica il testo del Barcode. |
| [getFormat()](#getFormat--) | Specifica il formato dell'immagine della firma Barcode. |
| [getContent()](#getContent--) | Specifica il contenuto dell'immagine dati binari del Barcode di tipo Formato (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Barcode Signature. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Inizializza l'oggetto BarcodeSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore unico è usato per trovare proprietà aggiuntive per questa firma dallo strato di informazioni sulla firma del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | java.lang.String | Identificatore unico della firma ottenuto tramite il metodo Sign o Search della classe Signature [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Inizializza BarcodeSignature con parametri predefiniti.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specifica il tipo di codifica del Barcode.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specifica il testo del Barcode.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifica il formato dell'immagine della firma Barcode.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifica il contenuto dell'immagine dati binari del Barcode di tipo Formato (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Per impostazione predefinita questa proprietà non sarà impostata. Usa la proprietà BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) per abilitare questa funzionalità.

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
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| immagine | java.awt.image.BufferedImage |  |

