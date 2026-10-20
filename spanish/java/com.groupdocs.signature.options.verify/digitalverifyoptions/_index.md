---
title: "DigitalVerifyOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Mantiene opciones para verificar la firma digital del documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Mantiene opciones para verificar la firma digital del documento.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Crea la opción de verificación digital con valores predeterminados. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Crea la opción de verificación digital con el GUID del certificado digital proporcionado. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Crea la opción de verificación digital con el flujo del certificado proporcionado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Obtiene el certificado X509Certificate2 a partir del GUID del certificado o del flujo. |
|
|  | [getPassword()](#getPassword--) | Contraseña del certificado digital si es requerida. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Contraseña del certificado digital si es requerida. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | GUID del archivo del certificado digital. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | GUID del archivo del certificado digital. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Flujo del certificado digital. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Flujo del certificado digital. |
|
|  | [getComments()](#getComments--) | Comentarios de la firma digital a validar. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Comentarios de la firma digital a validar. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Rango de fecha y hora de la firma digital a validar. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Rango de fecha y hora de la firma digital a validar. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Rango de fecha y hora de la firma digital a validar. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Rango de fecha y hora de la firma digital a validar. |
|
|  | [getReason()](#getReason--) | Motivo de la firma digital a validar. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Motivo de la firma digital a validar. |
|
|  | [getContact()](#getContact--) | Contacto de la firma a validar. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Contacto de la firma a validar. |
|
|  | [getLocation()](#getLocation--) | Ubicación de la firma a validar. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Ubicación de la firma a validar. |
|
|  | [getSubjectName()](#getSubjectName--) | Nombre distinguido del sujeto del certificado a validar. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Nombre distinguido del sujeto del certificado a validar. |
|
|  | [getIssuerName()](#getIssuerName--) | Nombre del emisor del certificado a validar. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Nombre del emisor del certificado a validar. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Crea la opción de verificación digital con valores predeterminados.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Crea la opción de verificación digital con el GUID del certificado digital proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Ruta del archivo del certificado digital. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Crea la opción de verificación digital con el flujo del certificado proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flujo del certificado. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Obtiene el certificado X509Certificate2 a partir del GUID del certificado o del flujo.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Contraseña del certificado digital si es requerida.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Contraseña del certificado digital si es requerida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


GUID del archivo del certificado digital.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


GUID del archivo del certificado digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Flujo del certificado digital.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Flujo del certificado digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Comentarios de la firma digital a validar.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Comentarios de la firma digital a validar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Motivo de la firma digital a validar.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Motivo de la firma digital a validar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Contacto de la firma a validar.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Contacto de la firma a validar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Ubicación de la firma a validar.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Ubicación de la firma a validar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Nombre distinguido del sujeto del certificado a validar. El valor distingue entre mayúsculas y minúsculas.
Si esta propiedad está establecida, la verificación comprobará si el nombre del sujeto de la firma contiene o es igual al valor pasado.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Nombre distinguido del sujeto del certificado a validar. El valor distingue entre mayúsculas y minúsculas.
Si esta propiedad está establecida, la verificación comprobará si el nombre del sujeto de la firma contiene o es igual al valor pasado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Nombre del emisor del certificado a validar. El valor distingue entre mayúsculas y minúsculas.
Si esta propiedad está establecida, la verificación comprobará si el nombre del emisor de la firma contiene o es igual al valor proporcionado.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Nombre del emisor del certificado a validar. El valor distingue entre mayúsculas y minúsculas.
Si esta propiedad está establecida, la verificación comprobará si el nombre del emisor de la firma contiene o es igual al valor proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

