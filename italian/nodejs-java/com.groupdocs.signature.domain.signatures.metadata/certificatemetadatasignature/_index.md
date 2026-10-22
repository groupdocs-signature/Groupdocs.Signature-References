---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma di metadati del certificato."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

Contiene le proprietà della firma di metadati del certificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | Crea Certificate Metadata Signature con nome predefinito e valore vuoto. |
| [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | Crea Certificate Metadata Signature con valori predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Clona l'istanza di Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona l'istanza di Certificate Metadata Signature con il valore fornito. |
| [toString()](#toString--) | Converte in String con il metodo ToString() sovrascritto |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Converte in String con formato specificato |
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


Crea Certificate Metadata Signature con nome predefinito e valore vuoto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della Certificate Metadata Signature. |

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


Crea Certificate Metadata Signature con valori predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto firma Metadata. |
| valore | java.lang.Object | Valore della firma Metadata. |

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


Clona l'istanza di Certificate Metadata Signature con il valore fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Valore per il nuovo oggetto clonato. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


Converte in String con il metodo ToString() sovrascritto

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.

--------------------

Converte una proprietà boolean in "True" o "False". Per un altro tipo di dato verrà utilizzato il provider di formato dati predefinito.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Converte in String con formato specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | java.lang.String | Stringa di formato dati. |
|  | provider | com.aspose.ms.System.IFormatProvider | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Converte una proprietà boolean in "True" o "False". |

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
