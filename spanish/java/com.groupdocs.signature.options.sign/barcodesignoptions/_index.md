---
title: "BarcodeSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma de código de barras."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Representa las opciones de firma de código de barras.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Obtiene o establece el tipo de código de barras. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Obtiene o establece el tipo de código de barras. |
|
|  | [getForeColor()](#getForeColor--) | Obtiene o establece el color de primer plano de las barras del código de barras |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtiene o establece el color de primer plano de las barras del código de barras |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Obtiene o establece el color de primer plano de las barras del código de barras |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [getInnerMargins()](#getInnerMargins--) | Obtiene o establece el espacio entre los elementos del código de barras y los bordes de la imagen resultante. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Obtiene o establece el espacio entre los elementos del código de barras y los bordes de la imagen resultante. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Obtiene o establece la alineación del texto en la imagen de código de barras resultante. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Obtiene o establece la alineación del texto en la imagen de código de barras resultante. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtiene o establece la bandera para obtener el contenido de la imagen de código de barras de una firma que se colocó en la página del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtiene o establece la bandera para obtener el contenido de la imagen de código de barras de una firma que se colocó en la página del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. |
|
|  | [validate()](#validate--) | Método interno para validar los parámetros de opciones de código de barras. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Inicializa una nueva instancia de la clase BarcodeSignOptions con texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto del código de barras |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Inicializa una nueva instancia de la clase BarcodeSignOptions con texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto del código de barras |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Tipo de codificación de código de barras ver [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Obtiene o establece el tipo de código de barras.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Obtiene o establece el tipo de código de barras.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtiene o establece el color de primer plano de las barras del código de barras
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtiene o establece el color de primer plano de las barras del código de barras
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Obtiene o establece el color de primer plano de las barras del código de barras
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Obtiene o establece el espacio entre los elementos del código de barras y los bordes de la imagen resultante.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Obtiene o establece el espacio entre los elementos del código de barras y los bordes de la imagen resultante.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Obtiene o establece la alineación del texto en la imagen de código de barras resultante.
El valor predeterminado es Ninguno.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Obtiene o establece la alineación del texto en la imagen de código de barras resultante.
El valor predeterminado es Ninguno.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtiene o establece la bandera para obtener el contenido de la imagen de código de barras de una firma que se colocó en la página del documento.
Si esta bandera se establece en verdadero, el contenido de la imagen de la firma de código de barras mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtiene o establece la bandera para obtener el contenido de la imagen de código de barras de una firma que se colocó en la página del documento.
Si esta bandera se establece en verdadero, el contenido de la imagen de la firma de código de barras mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen de código de barras en el formato original.
Este formato de imagen se especifica en
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen de código de barras en formato .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen de código de barras en el formato original.
Este formato de imagen se especifica en
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen de código de barras en formato .png.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Método interno para validar los parámetros de opciones de código de barras.


### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
