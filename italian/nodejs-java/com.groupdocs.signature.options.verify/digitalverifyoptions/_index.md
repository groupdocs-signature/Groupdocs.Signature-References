---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Mantiene le opzioni per verificare la firma digitale del documento."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Mantiene le opzioni per verificare la firma digitale del documento.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Crea l'opzione di verifica digitale con valori predefiniti. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Crea l'opzione di verifica digitale con il guid del certificato digitale fornito. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Crea l'opzione di verifica digitale con lo stream del certificato fornito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCertificate()](#getCertificate--) | Ottieni il certificato X509Certificate2 dal guid del certificato o dallo stream. |
| [getPassword()](#getPassword--) | Password del certificato digitale, se necessaria. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password del certificato digitale, se necessaria. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Guid del file del certificato digitale. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Guid del file del certificato digitale. |
| [getCertificateStream()](#getCertificateStream--) | Stream del certificato digitale. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Stream del certificato digitale. |
| [getComments()](#getComments--) | Commenti della firma digitale da convalidare. |
| [setComments(String value)](#setComments-java.lang.String-) | Commenti della firma digitale da convalidare. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Intervallo di data e ora della firma digitale da convalidare. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Intervallo di data e ora della firma digitale da convalidare. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Intervallo di data e ora della firma digitale da convalidare. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Intervallo di data e ora della firma digitale da convalidare. |
| [getReason()](#getReason--) | Motivo della firma digitale da convalidare. |
| [setReason(String value)](#setReason-java.lang.String-) | Motivo della firma digitale da convalidare. |
| [getContact()](#getContact--) | Contatto della firma da convalidare. |
| [setContact(String value)](#setContact-java.lang.String-) | Contatto della firma da convalidare. |
| [getLocation()](#getLocation--) | Posizione della firma da convalidare. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Posizione della firma da convalidare. |
| [getSubjectName()](#getSubjectName--) | Nome distinto del soggetto del certificato da convalidare. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Nome distinto del soggetto del certificato da convalidare. |
| [getIssuerName()](#getIssuerName--) | Nome dell'emittente del certificato da convalidare. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Nome dell'emittente del certificato da convalidare. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Crea l'opzione di verifica digitale con valori predefiniti.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Crea l'opzione di verifica digitale con il guid del certificato digitale fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificateGuid | java.lang.String | Percorso del file del certificato digitale. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Crea l'opzione di verifica digitale con lo stream del certificato fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream del certificato. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Ottieni il certificato X509Certificate2 dal guid del certificato o dallo stream.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password del certificato digitale, se necessaria.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password del certificato digitale, se necessaria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Guid del file del certificato digitale.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Guid del file del certificato digitale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Stream del certificato digitale.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Stream del certificato digitale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Commenti della firma digitale da convalidare.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Commenti della firma digitale da convalidare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Intervallo di data e ora della firma digitale da convalidare. Il valore nullable verrà ignorato.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Intervallo di data e ora della firma digitale da convalidare. Il valore nullable verrà ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Intervallo di data e ora della firma digitale da convalidare. Il valore nullable verrà ignorato.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Intervallo di data e ora della firma digitale da convalidare. Il valore nullable verrà ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Motivo della firma digitale da convalidare.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Motivo della firma digitale da convalidare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Contatto della firma da convalidare.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Contatto della firma da convalidare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Posizione della firma da convalidare.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Posizione della firma da convalidare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Nome distinto del soggetto del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome del soggetto della firma contiene o è uguale al valore fornito

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Nome distinto del soggetto del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome del soggetto della firma contiene o è uguale al valore fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Nome dell'emittente del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome dell'emittente della firma contiene o è uguale al valore fornito

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Nome dell'emittente del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome dell'emittente della firma contiene o è uguale al valore fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

