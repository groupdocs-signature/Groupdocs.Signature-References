---
title: "DigitalSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma digital."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Representa las opciones de firma digital.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado y el archivo de imagen. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado y el flujo de imagen. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado y el archivo de imagen. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado y el flujo de imagen. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getReason()](#getReason--) | Obtiene o establece la razón de la firma. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Obtiene o establece la razón de la firma. |
|
|  | [getContact()](#getContact--) | Obtiene o establece el contacto de la firma. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Obtiene o establece el contacto de la firma. |
|
|  | [getLocation()](#getLocation--) | Obtiene o establece la ubicación de la firma. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Obtiene o establece la ubicación de la firma. |
|
|  | [getPassword()](#getPassword--) | Obtiene o establece la contraseña del certificado digital. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña del certificado digital. |
|
|  | [getSignature()](#getSignature--) | Obtiene o establece las propiedades de la firma digital del documento. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Obtiene o establece las propiedades de la firma digital del documento. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Obtiene o establece la ruta del archivo del certificado digital. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Obtiene o establece el GUID del archivo del certificado digital. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Obtiene o establece el flujo del certificado digital. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Obtiene o establece el flujo del certificado digital. |
|
|  | [getVisible()](#getVisible--) | Obtiene o establece la visibilidad de la firma. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece la visibilidad de la firma. |
|
|  | [getUseLtv()](#getUseLtv--) | Obtiene/establece la bandera de validación LTV (Validación a Largo Plazo). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Obtiene/establece la bandera de validación LTV (Validación a Largo Plazo). |
|
|  | [getAllowExpired()](#getAllowExpired--) | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Obtiene o establece una implementación personalizada de hash-firmado, permitiendo a los llamadores integrar la suya propia |
lógica de firma digital (HSM, firmante remoto, almacén de claves de software, etc.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Establece una implementación personalizada de hash-firmado, permitiendo a los llamadores integrar la suya propia |
lógica de firma digital.
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
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Ruta del archivo del certificado digital |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flujo del certificado digital |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado y el archivo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Ruta del archivo del certificado digital |
|
|  | imageFilePath | java.lang.String | Ruta del archivo de imagen de apariencia de la firma |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el archivo de certificado y el flujo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Ruta del archivo del certificado digital |
|
|  | appearenceImageStream | java.io.InputStream | Flujo de imagen de apariencia de la firma |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado y el archivo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flujo del certificado digital |
|
|  | imageFilePath | java.lang.String | Ruta del archivo de imagen de apariencia de la firma |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Inicializa una nueva instancia de la clase DigitalSignOptions con el flujo de certificado y el flujo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flujo del certificado digital |
|
|  | appearenceImageStream | java.io.InputStream | Flujo de imagen de apariencia de la firma |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Obtiene o establece la razón de la firma.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Obtiene o establece la razón de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Obtiene o establece el contacto de la firma.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Obtiene o establece el contacto de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Obtiene o establece la ubicación de la firma.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Obtiene o establece la ubicación de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene o establece la contraseña del certificado digital.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtiene o establece la contraseña del certificado digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Obtiene o establece las propiedades de la firma digital del documento.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Obtiene o establece las propiedades de la firma digital del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Obtiene o establece la ruta del archivo del certificado digital.
Esta propiedad se usa solo si CertificateStream no está especificado.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Obtiene o establece el GUID del archivo del certificado digital.
Esta propiedad se usa solo si CertificateStream no está especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Obtiene o establece el flujo del certificado digital.
Si esta propiedad está especificada, siempre se usa en lugar de CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Obtiene o establece el flujo del certificado digital.
Si esta propiedad está especificada, siempre se usa en lugar de CertificateGuid.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Obtiene o establece la visibilidad de la firma.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtiene o establece la visibilidad de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Obtiene/establece la bandera de validación LTV (Validación a Largo Plazo).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Obtiene/establece la bandera de validación LTV (Validación a Largo Plazo).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado.
El valor predeterminado es false: firmar con un certificado expirado genera una excepción
GroupDocsSignatureException
,
y el documento no está firmado.


Los validadores informan que una firma realizada con un certificado expirado no es válida. Establezca esta propiedad en true solo cuando
necesita esa firma de todos modos, por ejemplo para probar con un certificado antiguo. El documento se firma entonces, y un
advertencia se escribe en el logger configurado en
SignatureSettings
.


El certificado se compara con la hora actual en UTC, no con
DigitalSignature.SignTime
. La bandera
se aplica al certificado proporcionado por
CertificateFilePath
,
CertificateStream
o
Firma
,
y, cuando una hoja de cálculo está firmada, al certificado del primero
DigitalVBA
extensión. Digital
las firmas de imágenes no utilizan un certificado y no se verifican. Un certificado cuyo período de validez no ha
comenzado aún está controlado por
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado.
El valor predeterminado es false. Ver #getAllowExpired().getAllowExpired().


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado.
El valor predeterminado es false: firmar con un certificado de este tipo lanza
GroupDocsSignatureException
,
y el documento no está firmado.


Los validadores informan que una firma realizada antes de que el certificado sea válido no es válida. Tal certificado fue
normalmente emitido para una fecha posterior, o el reloj del equipo está incorrecto. Cuando esta propiedad es true, el documento está
firmado, y una advertencia se escribe en el logger configurado en
SignatureSettings
.


El certificado se compara con la hora actual en UTC. La bandera se aplica a los mismos certificados que

AllowExpired
, que controla los certificados cuyo período de validez ha finalizado.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado.
El valor predeterminado es false. Ver #getAllowNotYetValid().getAllowNotYetValid().


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Obtiene o establece una implementación personalizada de hash-firmado, permitiendo a los llamadores integrar la suya propia
lógica de firma digital (HSM, firmante remoto, almacén de claves de software, etc.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Establece una implementación personalizada de hash-firmado, permitiendo a los llamadores integrar la suya propia
lógica de firma digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Tipo XAdES
XAdESType
. El valor predeterminado es None (XAdES está desactivado).
En este momento el tipo de firma XAdES solo es compatible con documentos de Spreadsheet bajo .NET Framework (no bajo .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Tipo XAdES
XAdESType
. El valor predeterminado es None (XAdES está desactivado).
En este momento el tipo de firma XAdES solo es compatible con documentos de Spreadsheet bajo .NET Framework (no bajo .NET Standard).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
