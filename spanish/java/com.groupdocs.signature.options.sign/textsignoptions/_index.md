---
title: "TextSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma de texto."
type: docs
weight: 18
url: /es/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Representa las opciones de firma de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | Inicializa una nueva instancia de la clase SignTextOptions con valores predeterminados. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Inicializa una nueva instancia de la clase SignTextOptions con texto. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLeft()](#getLeft--) | Posición X izquierda de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Posición X izquierda de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
|
|  | [getTop()](#getTop--) | Posición Y superior de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Posición Y superior de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Ancho de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Ancho de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Altura de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Altura de la Firma en la página del documento en valores de medida |
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).
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
|  | [getText()](#getText--) | Obtiene o establece el texto de la firma. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto de la firma. |
|
|  | [getFont()](#getFont--) | Obtiene o establece la fuente de la firma. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Obtiene o establece la fuente de la firma. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | Interno: la fuente que tenía esta instancia al crearse, o la fuente predeterminada. |
|
|  | [getForeColor()](#getForeColor--) | Obtiene o establece el color de primer plano de la firma. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtiene o establece el color de primer plano de la firma. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Obtiene o establece el tipo de implementación de firma de texto. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Obtiene o establece el tipo de implementación de firma de texto. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Alineación horizontal del texto dentro de una firma. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Alineación horizontal del texto dentro de una firma. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Alineación vertical del texto dentro de una firma. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Alineación vertical del texto dentro de una firma. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él. |
|
|  | [getShapeType()](#getShapeType--) | Obtiene o establece el tipo de forma para colocar texto. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | Obtiene o establece el tipo de forma para colocar texto. |
|
|  | [getSignatureID()](#getSignatureID--) | Obtiene o establece el ID único de la firma. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Obtiene o establece el ID único de la firma. |
|
|  | [getBorder()](#getBorder--) | Especifique la configuración del borde |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Especifique la configuración del borde |
|
|  | [getBackground()](#getBackground--) | Obtiene o establece la configuración de fondo de la firma. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Obtiene o establece la configuración de fondo de la firma. |
|
|  | [getNative()](#getNative--) | Obtiene o establece el atributo nativo. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Obtiene o establece el atributo nativo. |
|
|  | [getShapePosition()](#getShapePosition--) | Define dónde debe presentarse la forma en el diseño del documento |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Define dónde debe presentarse la forma en el diseño del documento |
|
|  | [validate()](#validate--) | Método interno para validar los parámetros de opciones. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Inicializa una nueva instancia de la clase SignTextOptions con valores predeterminados.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Inicializa una nueva instancia de la clase SignTextOptions con texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto de la firma. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posición X izquierda de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
(funciona si la alineación horizontal no está especificada).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posición X izquierda de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
(funciona si la alineación horizontal no está especificada).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posición Y superior de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
(funciona si la alineación vertical no está especificada).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posición Y superior de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad LocationMeasureType).
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
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ancho de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altura de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altura de la Firma en la página del documento en valores de medida
(píxeles, porcentajes o milímetros ver [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propiedad SizeMeasureType).


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

### getText() {#getText--}
```
public final String getText()
```


Obtiene o establece el texto de la firma.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtiene o establece el texto de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Obtiene o establece la fuente de la firma.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Obtiene o establece la fuente de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


Interno: la fuente que tenía esta instancia al crearse, o la fuente predeterminada.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtiene o establece el color de primer plano de la firma.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtiene o establece el color de primer plano de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Obtiene o establece el tipo de implementación de firma de texto.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Obtiene o establece el tipo de implementación de firma de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Alineación horizontal del texto dentro de una firma.
Esta característica solo es compatible con implementaciones de firma de Image y Annotation
(ver [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propiedad SignatureImplementation).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Alineación horizontal del texto dentro de una firma.
Esta característica solo es compatible con implementaciones de firma de Image y Annotation
(ver [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propiedad SignatureImplementation).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Alineación vertical del texto dentro de una firma.
Esta característica solo es compatible con la implementación de firma Image
(ver [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propiedad SignatureImplementation).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Alineación vertical del texto dentro de una firma.
Esta característica solo es compatible con la implementación de firma Image
(ver [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propiedad SignatureImplementation).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él.
Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él.
Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él.
Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField.
El valor por defecto es AllTextTypes.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él.
Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField.
El valor por defecto es AllTextTypes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Obtiene o establece el tipo de forma para colocar texto.
Esta propiedad solo se puede usar con SignatureImplementation = TextStamp.
El valor por defecto es Rectangle.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Obtiene o establece el tipo de forma para colocar texto.
Esta propiedad solo se puede usar con SignatureImplementation = TextStamp.
El valor por defecto es Rectangle.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Obtiene o establece el ID único de la firma. Puede usarse en las opciones de verificación de firma. La propiedad solo es compatible con documentos Pdf.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Obtiene o establece el ID único de la firma. Puede usarse en las opciones de verificación de firma. La propiedad solo es compatible con documentos Pdf.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Obtiene o establece la configuración de fondo de la firma.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Obtiene o establece la configuración de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Obtiene o establece el atributo nativo. Si se establece, se pueden usar firmas específicas del documento.
La marca de agua de texto nativa para documentos WordProcessing es diferente a la regular, por ejemplo.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Obtiene o establece el atributo nativo. Si se establece, se pueden usar firmas específicas del documento.
La marca de agua de texto nativa para documentos WordProcessing es diferente a la regular, por ejemplo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

### validate() {#validate--}
```
public void validate()
```


Método interno para validar los parámetros de opciones.


### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
