---
title: "DigitalVBA"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa la firma digital para proyectos VBA de hojas de cálculo."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Representa la firma digital para proyectos VBA de hojas de cálculo.
Proporciona la capacidad de firmar proyectos VBA en formatos de documento de Hojas de cálculo específicos como Xlsm o Xltm.
Si se añaden varias extensiones DigitalVBA a DigitalSignOptions.Extensions, solo la primera interviene en la firma del documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase DigitalVBA con un archivo de certificado. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Inicializa una nueva instancia de la clase DigitalVBA con un flujo de certificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getComments()](#getComments--) | Obtiene o establece los comentarios de la firma. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Obtiene o establece los comentarios de la firma. |
|
|  | [getPassword()](#getPassword--) | Obtiene o establece la contraseña del certificado digital. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña del certificado digital. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Obtiene o establece la configuración de firma solo del proyecto VBA. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Obtiene o establece la configuración de firma solo del proyecto VBA. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Obtiene la ruta del archivo del certificado digital. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Obtiene el flujo del certificado digital. |
|
|  | [release()](#release--) | Método sobrescrito para limpiar los recursos después de la firma. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Inicializa una nueva instancia de la clase DigitalVBA con un archivo de certificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Ruta del archivo del certificado digital |
|
|  | contraseña | java.lang.String | Contraseña del certificado digital |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Inicializa una nueva instancia de la clase DigitalVBA con un flujo de certificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flujo del certificado digital |
|
|  | contraseña | java.lang.String | Contraseña del certificado digital |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Obtiene o establece los comentarios de la firma.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Obtiene o establece los comentarios de la firma.


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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Obtiene o establece la configuración de firma solo del proyecto VBA.
Si se establece en true, el documento SpreadSheet no se firmará, pero el proyecto VBA sí se firmará.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Obtiene o establece la configuración de firma solo del proyecto VBA.
Si se establece en true, el documento SpreadSheet no se firmará, pero el proyecto VBA sí se firmará.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Obtiene la ruta del archivo del certificado digital.
Esta propiedad se usa solo si CertificateStream no está especificado.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Obtiene el flujo del certificado digital.
Si se especifica esta propiedad, siempre se usa en lugar de CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Método sobrescrito para limpiar los recursos después de la firma.


