---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma Digitale PDF."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Contiene le proprietà della firma Digitale PDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfDigitalSignature()](#PdfDigitalSignature--) | Inizializza Pdf Digital Signature senza certificato. |
| [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Crea Pdf Digital signature con certificato specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContactInfo()](#getContactInfo--) | Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad es. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad es. |
| [getLocation()](#getLocation--) | Il nome host della CPU o la posizione fisica della firma. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Il nome host della CPU o la posizione fisica della firma. |
| [getReason()](#getReason--) | Il motivo della firma, ad esempio (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [setReason(String value)](#setReason-java.lang.String-) | Il motivo della firma, ad esempio (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [getType()](#getType--) | Tipo di firma digitale Pdf. |
| [setType(int value)](#setType-int-) | Tipo di firma digitale Pdf. |
| [getTimeStamp()](#getTimeStamp--) | Marca temporale per firma digitale Pdf. |
| [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Marca temporale per firma digitale Pdf. |
| [getShowProperties()](#getShowProperties--) | Forza la visualizzazione/nascondi le proprietà della firma. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Forza la visualizzazione/nascondi le proprietà della firma. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Barcode Signature. |
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Inizializza Pdf Digital Signature senza certificato.

### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Crea Pdf Digital signature con certificato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificato | java.security.KeyStore | Certificato X509. |

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono.

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Il nome host della CPU o la posizione fisica della firma.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Il nome host della CPU o la posizione fisica della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Il motivo della firma, ad esempio (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Il motivo della firma, ad esempio (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Tipo di firma digitale Pdf.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Tipo di firma digitale Pdf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Marca temporale per la firma digitale PDF. Il valore predefinito è null.

**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Marca temporale per la firma digitale PDF. Il valore predefinito è null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito: Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date: \{Date\} Reason: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Location: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties è true per impostazione predefinita.

**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato di aspetto predefinito: Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date: \{Date\} Reason: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Location: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties è true per impostazione predefinita.

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


Clona l'istanza di Barcode Signature.

**Returns:**
java.lang.Object - Restituisce un'istanza clonata di Barcode Signature.
