---
title: "MetadataSignOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di firma Metadata."
type: docs
weight: 14
url: /it/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Rappresenta le opzioni di firma Metadata.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | Inizializza una nuova istanza della classe SignMetadataOptions con valori predefiniti. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Inizializza una nuova istanza della classe SignMetadataOptions con i Metadati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | Ottiene o imposta i Metadati della firma. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Ottiene o imposta i Metadati della firma. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crea un nuovo PdfMetadataSignature con gli argomenti forniti e lo aggiunge alla collezione. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Crea un nuovo ImageMetadataSignature con gli argomenti forniti e lo aggiunge alla collezione. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Aggiunge un'istanza MetadataSignature esistente alla collezione. |
|
|  | [validate()](#validate--) | Metodo interno per convalidare i parametri delle opzioni. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Inizializza una nuova istanza della classe SignMetadataOptions con valori predefiniti.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Inizializza una nuova istanza della classe SignMetadataOptions con i Metadati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Raccolta di firme di metadati [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Ottiene o imposta i Metadati della firma.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Ottiene o imposta i Metadati della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Crea un nuovo PdfMetadataSignature con gli argomenti forniti e lo aggiunge alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto firma di metadati |
|
|  | valore | java.lang.Object | Valore della firma di metadati |
|
|  | etichetta | java.lang.String | Etichetta prefisso della firma di metadati |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Crea un nuovo ImageMetadataSignature con gli argomenti forniti e lo aggiunge alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | id | int | Identificatore univoco del nome della firma di metadati immagine. Vedi i riferimenti per le specifiche dei tag Exif per i possibili valori di id |
|
|  | valore | java.lang.Object | Valore dei metadati |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Aggiunge un'istanza MetadataSignature esistente alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | L'istanza esistente di MetadataSignature da aggiungere |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


Metodo interno per convalidare i parametri delle opzioni.


### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
