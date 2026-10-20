---
title: "StampSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma de sello."
type: docs
weight: 17
url: /es/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Representa las opciones de firma de sello.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Inicializa una nueva instancia de la clase StampSignOptions con valores predeterminados. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Inicializa una nueva instancia de la clase StampSignOptions con opciones de alineación. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getStampType()](#getStampType--) | Obtiene o establece el tipo de sello. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Obtiene o establece el tipo de sello. |
|
|  | [getOuterLines()](#getOuterLines--) | Lista de Líneas Externas renderizadas como círculos concéntricos. |
|
|  | [getInnerLines()](#getInnerLines--) | Lista de Líneas Internas renderizadas como conjunto de rectángulos. |
|
|  | [getBackground()](#getBackground--) | Obtiene o establece el fondo del Sello. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Obtiene o establece el fondo del Sello. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece el color de fondo de la firma. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Obtiene o establece el color de fondo de la firma. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Obtiene o establece el pincel de fondo de la firma. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Obtiene o establece el pincel de fondo de la firma. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Obtiene o establece el tipo de recorte de color de fondo de la firma. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Obtiene o establece el tipo de recorte de color de fondo de la firma. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Obtiene o establece el tipo de recorte de imagen de fondo de la firma. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Obtiene o establece el tipo de recorte de imagen de fondo de la firma. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Inicializa una nueva instancia de la clase StampSignOptions con valores predeterminados.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Inicializa una nueva instancia de la clase StampSignOptions con opciones de alineación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | izquierda | int | La coordenada x del borde superior izquierdo de Stamp Signature |
|
|  | superior | int | La coordenada y del borde superior izquierdo de Stamp Signature |
|
|  | ancho | int | El ancho de Stamp Signature |
|
|  | altura | int | La altura de Stamp Signature |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Obtiene o establece el tipo de sello.
El valor por defecto es Round.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Obtiene o establece el tipo de sello.
El valor por defecto es Round.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Lista de Líneas Externas renderizadas como círculos concéntricos.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Lista de Líneas Internas renderizadas como conjunto de rectángulos.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Obtiene o establece el fondo del Sello.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Obtiene o establece el fondo del Sello.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Obtiene o establece el color de fondo de la firma.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Obtiene o establece el color de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Obtiene o establece el pincel de fondo de la firma. El valor por defecto es null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Obtiene o establece el pincel de fondo de la firma. El valor por defecto es null.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Obtiene o establece el tipo de recorte de color de fondo de la firma.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Obtiene o establece el tipo de recorte de color de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Obtiene o establece el tipo de recorte de imagen de fondo de la firma.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Obtiene o establece el tipo de recorte de imagen de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena


**Returns:**
java.lang.String - 
