---
title: "DigitalSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma digitale."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Contiene le proprietà della firma digitale.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Inizializza Digital signature con i parametri predefiniti. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Inizializza Digital signature con un SignatureId noto. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Crea Digital signature con il certificato specificato. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Crea Digital signature basata sul certificato X509Certificate e sulla PrivateKey. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Ottiene o imposta il certificato KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Ottiene o imposta il certificato KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Ottiene o imposta il certificato X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Ottiene o imposta il certificato X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Ottiene o imposta la PrivateKey del certificato. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Ottiene o imposta la PrivateKey del certificato. |
|
|  | [getCertificateName()](#getCertificateName--) | Ottiene o imposta il nome del certificato X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Ottiene o imposta il nome del certificato X509. |
|
|  | [getComments()](#getComments--) | Ottiene o imposta il commento dello scopo della firma. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Ottiene o imposta il commento dello scopo della firma. |
|
|  | [isValid()](#isValid--) | Restituisce true se questa firma digitale è valida e il documento non è stato manomesso. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Restituisce true se questa firma digitale è valida e il documento non è stato manomesso. |
|
|  | [getSignTime()](#getSignTime--) | Ottiene o imposta l'ora in cui il documento è stato firmato. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Ottiene o imposta l'ora in cui il documento è stato firmato. |
|
|  | [getXAdESType()](#getXAdESType--) | Tipo XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Tipo XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Ottiene l'impronta digitale di un certificato. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza della firma Barcode. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Carica la firma digitale da tutti i negozi di certificati X509 di sistema. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Carica la firma digitale dal negozio di certificati X509 fornito. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Inizializza Digital signature con i parametri predefiniti.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Inizializza Digital signature con un SignatureId noto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Crea Digital signature con il certificato specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificato | java.security.KeyStore | Certificato X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Crea Digital signature basata sul certificato X509Certificate e sulla PrivateKey.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | Certificato X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey del certificato. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Ottiene o imposta il certificato KeyStore.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Ottiene o imposta il certificato KeyStore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Ottiene o imposta il certificato X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Ottiene o imposta il certificato X509.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Ottiene o imposta la PrivateKey del certificato.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Ottiene o imposta la PrivateKey del certificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Ottiene o imposta il nome del certificato X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Ottiene o imposta il nome del certificato X509.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Ottiene o imposta il commento dello scopo della firma.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Ottiene o imposta il commento dello scopo della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Restituisce true se questa firma digitale è valida e il documento non è stato manomesso.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Restituisce true se questa firma digitale è valida e il documento non è stato manomesso.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Ottiene o imposta l'ora in cui il documento è stato firmato.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Ottiene o imposta l'ora in cui il documento è stato firmato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Tipo XAdES
XAdESType
. Il valore predefinito è None (XAdES è disattivato).
Al momento il tipo di firma XAdES è supportato solo per documenti Spreadsheet.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Tipo XAdES
XAdESType
. Il valore predefinito è None (XAdES è disattivato).
Al momento il tipo di firma XAdES è supportato solo per documenti Spreadsheet.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Ottiene l'impronta digitale di un certificato.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sovrascrive il metodo Equals per confrontare le proprietà della firma


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | firma | java.lang.Object | Oggetto Signature da confrontare. |
|

**Returns:**
boolean - Restituisce true se l'oggetto signature passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode


**Returns:**
int - Codice hash della Signature

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza della firma Barcode.


**Returns:**
java.lang.Object - Restituisce l'istanza clonata di Barcode Signature.

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Carica la firma digitale da tutti i negozi di certificati X509 di sistema.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Restituisce l'elenco di [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) firme digitali.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Carica la firma digitale dal negozio di certificati X509 fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Restituisce l'elenco di [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) firme digitali.

