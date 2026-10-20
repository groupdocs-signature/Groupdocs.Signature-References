---
title: "DigitalSignatureAppearance"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Describe la apariencia de la línea de firma para firma digital."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Describe la apariencia de la línea de firma para firma digital.
Una línea de firma solo puede aplicarse a una firma digital.
La línea de firma siempre está en la primera página.
Esta característica puede ser útil para los formatos de archivo .docx, .doc, .odt y .xlsx.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Crea un objeto de apariencia de línea de firma. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crea la apariencia de la línea de firma con los valores especificados (firmante, título, correo electrónico). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSigner()](#getSigner--) | Obtiene o establece el nombre del firmante para la línea de firma. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Obtiene o establece el nombre del firmante para la línea de firma. |
|
|  | [getTitle()](#getTitle--) | Obtiene o establece un título para la línea de firma. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Obtiene o establece un título para la línea de firma. |
|
|  | [getEmail()](#getEmail--) | Obtiene o establece un correo electrónico que se mostrará en la línea de firma. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Obtiene o establece un correo electrónico que se mostrará en la línea de firma. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Crea un objeto de apariencia de línea de firma.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Crea la apariencia de la línea de firma con los valores especificados (firmante, título, correo electrónico).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | firmante | java.lang.String | Nombre del firmante. |
|
|  | título | java.lang.String | Título de la firma. |
|
|  | correo electrónico | java.lang.String | Correo electrónico del autor. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Obtiene o establece el nombre del firmante para la línea de firma.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Obtiene o establece el nombre del firmante para la línea de firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtiene o establece un título para la línea de firma.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtiene o establece un título para la línea de firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Obtiene o establece un correo electrónico que se mostrará en la línea de firma.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Obtiene o establece un correo electrónico que se mostrará en la línea de firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
