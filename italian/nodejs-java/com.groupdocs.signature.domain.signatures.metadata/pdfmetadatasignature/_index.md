---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene proprietà della firma Metadata Pdf."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Contiene proprietà della firma Metadata Pdf.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Crea una firma Pdf Metadata con nome predefinito e valore vuoto |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Crea una firma Pdf Metadata con valori predefiniti |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crea una firma Pdf Metadata con valori predefiniti |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Il tag prefisso del nome della firma Pdf Metadata. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Il tag prefisso del nome della firma Pdf Metadata. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona l'istanza di Pdf Metadata Signature con il valore fornito. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Crea una firma Pdf Metadata con nome predefinito e valore vuoto

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della firma Pdf Metadata |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Crea una firma Pdf Metadata con valori predefiniti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto firma Metadata |
| valore | java.lang.Object | Valore della firma Metadata |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Crea una firma Pdf Metadata con valori predefiniti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto firma Metadata |
| valore | java.lang.Object | Valore della firma Metadata |
| tag | java.lang.String | Tag prefisso della firma Metadata |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Il tag prefisso del nome della firma Pdf Metadata. Per impostazione predefinita questa proprietà è impostata su "xmp". I valori possibili sono

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Il tag prefisso del nome della firma Pdf Metadata. Per impostazione predefinita questa proprietà è impostata su "xmp". I valori possibili sono

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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


Clona l'istanza di Metadata Signature.

**Returns:**
java.lang.Object - Restituisce l'istanza clonata di Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clona l'istanza di Pdf Metadata Signature con il valore fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Valore per il nuovo oggetto clonato. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
