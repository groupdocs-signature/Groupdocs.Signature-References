---
title: "TextVerifyOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Mantiene opciones para verificar la firma de texto del documento."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Mantiene opciones para verificar la firma de texto del documento.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Inicializa una nueva instancia de TextVerifyOptions con texto de verificación. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Inicializa una nueva instancia de TextVerifyOptions con la propiedad Text para verificar y la implementación de firma. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Especifique el Texto de la Firma si debe ser verificado. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Especifique el Texto de la Firma si debe ser verificado. |
|
|  | [getMatchType()](#getMatchType--) | Obtiene o establece la verificación del Tipo de Coincidencia de Texto. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtiene o establece la verificación del Tipo de Coincidencia de Texto. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Tipo de Firma a verificar. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Tipo de Firma a verificar. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Obtiene o establece el título del campo de formulario para verificarlo. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Obtiene o establece el título del campo de formulario para verificarlo. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Obtiene o establece el tipo del campo de formulario para verificarlo. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Obtiene o establece el tipo del campo de formulario para verificarlo. |
|
|  | [getSignatureID()](#getSignatureID--) | Especifique un ID de Firma de Texto mayor que cero si debe ser verificado. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Especifique un ID de Firma de Texto mayor que cero si debe ser verificado. |
|
|  | [toString()](#toString--) | Sobrescribe la conversión a cadena. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Inicializa una nueva instancia de TextVerifyOptions con texto de verificación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto a verificar |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Inicializa una nueva instancia de TextVerifyOptions con la propiedad Text para verificar y la implementación de firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto a verificar. |
|
|  | implementación | int | Tipo de implementación de firma. |
|

### getText() {#getText--}
```
public final String getText()
```


Especifique el Texto de la Firma si debe ser verificado.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Especifique el Texto de la Firma si debe ser verificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtiene o establece la verificación del Tipo de Coincidencia de Texto.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtiene o establece la verificación del Tipo de Coincidencia de Texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Tipo de Firma a verificar.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Tipo de Firma a verificar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Obtiene o establece el título del campo de formulario para verificarlo.
Si el texto de este conjunto de propiedades se encontrará solo en campos de formulario de texto.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Obtiene o establece el título del campo de formulario para verificarlo.
Si el texto de este conjunto de propiedades se encontrará solo en campos de formulario de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Obtiene o establece el tipo del campo de formulario para verificarlo.
Si el texto de este conjunto de propiedades se encontrará solo en campos de formulario de texto.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Obtiene o establece el tipo del campo de formulario para verificarlo.
Si el texto de este conjunto de propiedades se encontrará solo en campos de formulario de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Especifique un ID de firma de texto mayor que cero si debe verificarse. Esta propiedad solo es compatible con documentos PDF.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Especifique un ID de firma de texto mayor que cero si debe verificarse. Esta propiedad solo es compatible con documentos PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribe la conversión a cadena.


**Returns:**
java.lang.String - 
