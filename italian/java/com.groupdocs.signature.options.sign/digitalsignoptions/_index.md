---
title: "DigitalSignOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di firma digitale."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Rappresenta le opzioni di firma digitale.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Inizializza una nuova istanza della classe DigitalSignOptions con i valori predefiniti. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e il file immagine. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e lo stream dell'immagine. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e il file immagine. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e lo stream dell'immagine. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getReason()](#getReason--) | Ottiene o imposta il motivo della firma. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Ottiene o imposta il motivo della firma. |
|
|  | [getContact()](#getContact--) | Ottiene o imposta il contatto della firma. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Ottiene o imposta il contatto della firma. |
|
|  | [getLocation()](#getLocation--) | Ottiene o imposta la posizione della firma. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Ottiene o imposta la posizione della firma. |
|
|  | [getPassword()](#getPassword--) | Ottiene o imposta la password del certificato digitale. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password del certificato digitale. |
|
|  | [getSignature()](#getSignature--) | Ottiene o imposta le proprietà della firma digitale del documento. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Ottiene o imposta le proprietà della firma digitale del documento. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Ottiene o imposta il percorso del file del certificato digitale. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Ottiene o imposta il GUID del file del certificato digitale. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Ottiene o imposta lo stream del certificato digitale. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Ottiene o imposta lo stream del certificato digitale. |
|
|  | [getVisible()](#getVisible--) | Ottiene o imposta la visibilità della firma. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta la visibilità della firma. |
|
|  | [getUseLtv()](#getUseLtv--) | Ottiene/imposta il flag di convalida LTV (Long Term Validation). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Ottiene/imposta il flag di convalida LTV (Long Term Validation). |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Ottiene o imposta un'implementazione personalizzata di hash-signing, consentendo ai chiamanti di inserire la propria |
logica di firma digitale (HSM, firmatario remoto, keystore software, ecc.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Imposta un'implementazione personalizzata di hash-signing, consentendo ai chiamanti di inserire la propria |
logica di firma digitale.
|
|  | [getXAdESType()](#getXAdESType--) | Tipo XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Tipo XAdES |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Inizializza una nuova istanza della classe DigitalSignOptions con i valori predefiniti.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Percorso del file del certificato digitale |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Stream del certificato digitale |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e il file immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Percorso del file del certificato digitale |
|
|  | imageFilePath | java.lang.String | Percorso del file immagine dell'aspetto della firma |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e lo stream dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Percorso del file del certificato digitale |
|
|  | appearenceImageStream | java.io.InputStream | Stream immagine dell'aspetto della firma |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e il file immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Stream del certificato digitale |
|
|  | imageFilePath | java.lang.String | Percorso del file immagine dell'aspetto della firma |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e lo stream dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Stream del certificato digitale |
|
|  | appearenceImageStream | java.io.InputStream | Stream immagine dell'aspetto della firma |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Ottiene o imposta il motivo della firma.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Ottiene o imposta il motivo della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Ottiene o imposta il contatto della firma.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Ottiene o imposta il contatto della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Ottiene o imposta la posizione della firma.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Ottiene o imposta la posizione della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password del certificato digitale.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password del certificato digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Ottiene o imposta le proprietà della firma digitale del documento.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Ottiene o imposta le proprietà della firma digitale del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Ottiene o imposta il percorso del file del certificato digitale.
Questa proprietà è usata solo se CertificateStream non è specificato.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Ottiene o imposta il GUID del file del certificato digitale.
Questa proprietà è usata solo se CertificateStream non è specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Ottiene o imposta lo stream del certificato digitale.
Se questa proprietà è specificata, viene sempre usata al posto di CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Ottiene o imposta lo stream del certificato digitale.
Se questa proprietà è specificata, viene sempre usata al posto di CertificateGuid.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Ottiene o imposta la visibilità della firma.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ottiene o imposta la visibilità della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Ottiene/imposta il flag di convalida LTV (Long Term Validation).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Ottiene/imposta il flag di convalida LTV (Long Term Validation).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Ottiene o imposta un'implementazione personalizzata di hash-signing, consentendo ai chiamanti di inserire la propria
logica di firma digitale (HSM, firmatario remoto, keystore software, ecc.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Imposta un'implementazione personalizzata di hash-signing, consentendo ai chiamanti di inserire la propria
logica di firma digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Tipo XAdES
XAdESType
. Il valore predefinito è None (XAdES è disattivato).
Al momento il tipo di firma XAdES è supportato solo per documenti Spreadsheet sotto .NET Framework (non sotto .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Tipo XAdES
XAdESType
. Il valore predefinito è None (XAdES è disattivato).
Al momento il tipo di firma XAdES è supportato solo per documenti Spreadsheet sotto .NET Framework (non sotto .NET Standard).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
