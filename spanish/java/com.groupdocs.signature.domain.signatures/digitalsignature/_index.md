---
title: "DigitalSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma digital."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Contiene propiedades de firma digital.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Inicializa la firma digital con parámetros predeterminados. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Inicializa la firma digital con un SignatureId conocido. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Crea una firma digital con el certificado especificado. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Crear firma digital basada en el certificado X509Certificate y la PrivateKey. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Obtiene o establece el certificado KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Obtiene o establece el certificado KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Obtiene o establece el certificado X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Obtiene o establece el certificado X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Obtiene o establece la PrivateKey del certificado. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Obtiene o establece la PrivateKey del certificado. |
|
|  | [getCertificateName()](#getCertificateName--) | Obtiene o establece el nombre del certificado X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Obtiene o establece el nombre del certificado X509. |
|
|  | [getComments()](#getComments--) | Obtiene o establece el comentario del propósito de la firma. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Obtiene o establece el comentario del propósito de la firma. |
|
|  | [isValid()](#isValid--) | Mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado. |
|
|  | [getSignTime()](#getSignTime--) | Obtiene o establece la hora en que se firmó el documento. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Obtiene o establece la hora en que se firmó el documento. |
|
|  | [getXAdESType()](#getXAdESType--) | Tipo XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Tipo XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Obtiene la huella digital de un certificado. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de Barcode Signature. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Cargar firma digital desde todos los almacenes de certificados X509 del sistema. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Cargar firma digital desde el almacén de certificados X509 proporcionado. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Inicializa la firma digital con parámetros predeterminados.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Inicializa la firma digital con un SignatureId conocido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Crea una firma digital con el certificado especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificado | java.security.KeyStore | Certificado X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Crear firma digital basada en el certificado X509Certificate y la PrivateKey.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | certificado X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey del certificado. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Obtiene o establece el certificado KeyStore.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Obtiene o establece el certificado KeyStore.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Obtiene o establece el certificado X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Obtiene o establece el certificado X509.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Obtiene o establece la PrivateKey del certificado.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Obtiene o establece la PrivateKey del certificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Obtiene o establece el nombre del certificado X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Obtiene o establece el nombre del certificado X509.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Obtiene o establece el comentario del propósito de la firma.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Obtiene o establece el comentario del propósito de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Obtiene o establece la hora en que se firmó el documento.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Obtiene o establece la hora en que se firmó el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Tipo XAdES
XAdESType
. El valor predeterminado es None (XAdES está desactivado).
En este momento, el tipo de firma XAdES solo es compatible con documentos de hoja de cálculo.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Tipo XAdES
XAdESType
. El valor predeterminado es None (XAdES está desactivado).
En este momento, el tipo de firma XAdES solo es compatible con documentos de hoja de cálculo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Obtiene la huella digital de un certificado.


**Returns:**
java.lang.String
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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Cargar firma digital desde todos los almacenes de certificados X509 del sistema.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Devuelve una lista de [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) firmas digitales.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Cargar firma digital desde el almacén de certificados X509 proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Devuelve una lista de [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) firmas digitales.

