---
title: "PdfDigitalSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma digital PDF."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Contiene propiedades de firma digital PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Inicializar Pdf Digital Signature sin certificado. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Crear Pdf Digital signature con certificado especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Información proporcionada por el firmante para permitir que un destinatario contacte al firmante |
para verificar la firma, p.ej.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Información proporcionada por el firmante para permitir que un destinatario contacte al firmante |
para verificar la firma, p.ej.
|
|  | [getLocation()](#getLocation--) | El nombre de host de la CPU o la ubicación física de la firma. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | El nombre de host de la CPU o la ubicación física de la firma. |
|
|  | [getReason()](#getReason--) | La razón de la firma, como (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | La razón de la firma, como (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Tipo de Pdf digital signature. |
|
|  | [setType(int value)](#setType-int-) | Tipo de Pdf digital signature. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Marca de tiempo para Pdf digital signature. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Marca de tiempo para Pdf digital signature. |
|
|  | [getShowProperties()](#getShowProperties--) | Forzar mostrar/ocultar propiedades de la firma. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Forzar mostrar/ocultar propiedades de la firma. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de Barcode Signature. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Inicializar Pdf Digital Signature sin certificado.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Crear Pdf Digital signature con certificado especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificado | java.security.KeyStore | Certificado X509. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Información proporcionada por el firmante para permitir que un destinatario contacte al firmante
para verificar la firma, p. ej. un número de teléfono.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Información proporcionada por el firmante para permitir que un destinatario contacte al firmante
para verificar la firma, p. ej. un número de teléfono.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


El nombre de host de la CPU o la ubicación física de la firma.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


El nombre de host de la CPU o la ubicación física de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


La razón de la firma, como (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


La razón de la firma, como (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Tipo de Pdf digital signature.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Tipo de Pdf digital signature.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Marca de tiempo para Pdf digital signature.
El valor predeterminado es null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Marca de tiempo para Pdf digital signature.
El valor predeterminado es null.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Forzar la visualización/ocultación de las propiedades de la firma. En caso de que ShowProperties sea verdadero la firma
el campo tiene un formato de apariencia predefinido
Firmado digitalmente por {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Fecha: {Date} Razón: {
Razón
(#getReason.getReason/#setReason(String).setReason(String))}
Ubicación: {
Ubicación
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties es verdadero por defecto.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Forzar la visualización/ocultación de las propiedades de la firma. En caso de que ShowProperties sea verdadero la firma
el campo tiene un formato de apariencia predefinido
Firmado digitalmente por {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Fecha: {Date} Razón: {
Razón
(#getReason.getReason/#setReason(String).setReason(String))}
Ubicación: {
Ubicación
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties es verdadero por defecto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sobrescribe el método Equals para comparar propiedades de la firma


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | firma | java.lang.Object | Objeto de firma con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto de firma pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash de la firma

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clonar instancia de Barcode Signature.


**Returns:**
java.lang.Object - Devuelve una instancia clonada de Barcode Signature.

