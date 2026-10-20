---
title: "ImageSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma de imagen."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Representa las opciones de firma de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Inicializa una nueva instancia de la clase ImageSignOptions con valores predeterminados. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Inicializa una nueva instancia de la clase ImageSignOptions con un archivo de imagen. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Inicializa una nueva instancia de la clase ImageSignOptions con un flujo de imagen. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Obtiene o establece la ruta del archivo de imagen de la firma. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Obtiene o establece la ruta del archivo de imagen de la firma. |
|
|  | [getImageStream()](#getImageStream--) | Obtiene o establece el flujo de imagen de la firma. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Obtiene o establece el flujo de imagen de la firma. |
|
|  | [getLeft()](#getLeft--) | Posición X izquierda de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Posición X izquierda de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Posición Y superior de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Posición Y superior de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Ancho de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Ancho de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Altura de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Altura de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
|
|  | [getStretch()](#getStretch--) | Modo de estiramiento en la página del documento. |
|
|  | [setStretch(int value)](#setStretch-int-) | Modo de estiramiento en la página del documento. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Ángulo de rotación de la firma en la página del documento (en sentido horario). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Ángulo de rotación de la firma en la página del documento (en sentido horario). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Alineación horizontal de la firma en la página del documento. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Alineación horizontal de la firma en la página del documento. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Alineación vertical de la firma en la página del documento. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Alineación vertical de la firma en la página del documento. |
|
|  | [getMargin()](#getMargin--) | Obtiene o establece el espacio entre la firma y los bordes del documento. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Obtiene o establece el espacio entre la firma y los bordes del documento. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [getShapePosition()](#getShapePosition--) | Define dónde debe presentarse la forma en el diseño del documento |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Define dónde debe presentarse la forma en el diseño del documento |
|
|  | [getRectangle()](#getRectangle--) | Rectángulo del área donde colocar la imagen en el documento. |
|
|  | [getBorder()](#getBorder--) | Especifique la configuración del borde |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Especifique la configuración del borde |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Crea una nueva instancia de la clase ImageSignOptions con una Imagen predefinida desde Base64. |
|
|  | [dispose()](#dispose--) | Limpia los recursos internos |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Inicializa una nueva instancia de la clase ImageSignOptions con valores predeterminados.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Inicializa una nueva instancia de la clase ImageSignOptions con un archivo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Ruta del archivo de imagen |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Inicializa una nueva instancia de la clase ImageSignOptions con un flujo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Secuencia de imagen |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Obtiene o establece la ruta del archivo de imagen de la firma.
Esta propiedad se usa solo si ImageStream no está especificado.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Obtiene o establece la ruta del archivo de imagen de la firma.
Esta propiedad se usa solo si ImageStream no está especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Obtiene o establece el flujo de imagen de la firma.
Si se especifica esta propiedad, siempre se usa en lugar de ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Obtiene o establece el flujo de imagen de la firma.
Si se especifica esta propiedad, siempre se usa en lugar de ImageGuid.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Posición X izquierda de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funciona si la alineación horizontal no está especificada).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Posición X izquierda de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funciona si la alineación horizontal no está especificada).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Posición Y superior de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funciona si la alineación vertical no está especificada).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Posición Y superior de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funciona si la alineación vertical no está especificada).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ancho de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ancho de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altura de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altura de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Modo de estiramiento en la página del documento.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Modo de estiramiento en la página del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Ángulo de rotación de la firma en la página del documento (en sentido horario).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Ángulo de rotación de la firma en la página del documento (en sentido horario).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Alineación horizontal de la firma en la página del documento.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Alineación horizontal de la firma en la página del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Alineación vertical de la firma en la página del documento.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Alineación vertical de la firma en la página del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Obtiene o establece el espacio entre la firma y los bordes del documento.
(funciona SÓLO si se especifica la alineación horizontal o vertical).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Obtiene o establece el espacio entre la firma y los bordes del documento.
(funciona SÓLO si se especifica la alineación horizontal o vertical).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (claro)). El valor predeterminado es 0 (opaco).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (claro)). El valor predeterminado es 0 (opaco).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Define dónde debe presentarse la forma en el diseño del documento


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Define dónde debe presentarse la forma en el diseño del documento


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rectángulo del área donde colocar la imagen en el documento.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Especifique la configuración del borde


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Especifique la configuración del borde


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Crea una nueva instancia de la clase ImageSignOptions con una Imagen predefinida desde Base64.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | base64Content | java.lang.String | Contenido de la imagen en formato de cadena Base64 |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Limpia los recursos internos


