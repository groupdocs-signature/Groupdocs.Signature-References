---
title: "TextShadow"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las propiedades de sombra de texto para firmas de texto."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Representa las propiedades de sombra de texto para firmas de texto.
El resultado puede variar según el tipo de firma y el formato del documento.
TextShadow se recomienda para usar con la firma TextAsImage para todos los tipos de documento compatibles,
también con TextSignature simple y TextSignature como marca de agua para Cells (.xslx) y Slides (.pptx).
TextSignature simple para Words (.docx) también se recomienda, pero tiene funcionalidad limitada.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Crea TextShadow con opciones predeterminadas. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDistance()](#getDistance--) | Obtiene o establece la distancia del texto a la sombra. |
|
|  | [setDistance(double value)](#setDistance-double-) | Obtiene o establece la distancia del texto a la sombra. |
|
|  | [getAngle()](#getAngle--) | Obtiene o establece el ángulo para colocar la sombra respecto al texto. |
|
|  | [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo para colocar la sombra respecto al texto. |
|
|  | [getColor()](#getColor--) | Obtiene o establece el color de la sombra. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Obtiene o establece el color de la sombra. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Obtiene o establece el color de la sombra. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia de la sombra. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtiene o establece la transparencia de la sombra. |
|
|  | [getBlur()](#getBlur--) | Obtiene o establece el desenfoque de la sombra. |
|
|  | [setBlur(double value)](#setBlur-double-) | Obtiene o establece el desenfoque de la sombra. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Crea TextShadow con opciones predeterminadas.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Obtiene o establece la distancia del texto a la sombra.
El valor predeterminado es 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Obtiene o establece la distancia del texto a la sombra.
El valor predeterminado es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtiene o establece el ángulo para colocar la sombra respecto al texto.
El valor predeterminado es 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtiene o establece el ángulo para colocar la sombra respecto al texto.
El valor predeterminado es 0.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color de la sombra.
El valor predeterminado es Negro.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color de la sombra.
El valor predeterminado es Negro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtiene o establece el color de la sombra.
El valor predeterminado es Negro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtiene o establece la transparencia de la sombra.
El valor predeterminado es 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtiene o establece la transparencia de la sombra.
El valor predeterminado es 0.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Obtiene o establece el desenfoque de la sombra.
El valor predeterminado es 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Obtiene o establece el desenfoque de la sombra.
El valor predeterminado es 4.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

