---
title: "QrCodeSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma QR-Code."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Representa las opciones de firma QR-Code.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Inicializa una nueva instancia de la clase QRCodeSignOptions con texto. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Obtiene o establece el tipo de QRCode. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Obtiene o establece el tipo de QRCode. |
|
|  | [getForeColor()](#getForeColor--) | Obtiene o establece el color de primer plano de las barras QR-Code. |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtiene o establece el color de primer plano de las barras QR-Code. |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Obtiene o establece el color de primer plano de las barras QR-Code. |
El uso de esta propiedad podría causar problemas con la verificación.
|
|  | [getInnerMargins()](#getInnerMargins--) | Obtiene o establece el espacio entre los elementos QRCode y los bordes de la imagen resultante. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Obtiene o establece el espacio entre los elementos QRCode y los bordes de la imagen resultante. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Obtiene o establece la alineación del texto en la imagen QR-code resultante. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Obtiene o establece la alineación del texto en la imagen QR-code resultante. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Obtiene o establece el nombre de archivo de la imagen del logotipo QR-code. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Obtiene o establece el nombre de archivo de la imagen del logotipo QR-code. |
|
|  | [getLogoStream()](#getLogoStream--) | Obtiene o establece el flujo de imagen del logotipo QR-code. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Obtiene o establece el flujo de imagen del logotipo QR-code. |
|
|  | [getData()](#getData--) | Obtiene o establece el objeto personalizado para serializar al contenido QR-Code. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Obtiene o establece el objeto personalizado para serializar al contenido QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtiene o establece la bandera para obtener el contenido de imagen QR-Code de una firma que se colocó en la página del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtiene o establece la bandera para obtener el contenido de imagen QR-Code de una firma que se colocó en la página del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Inicializa una nueva instancia de la clase QRCodeSignOptions con texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto de la firma. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Inicializa una nueva instancia de la clase BarcodeSignOptions con texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Texto QRCode |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipo de codificación QRCode ver [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Obtiene o establece el tipo de QRCode.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Obtiene o establece el tipo de QRCode.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtiene o establece el color de primer plano de las barras QR-Code.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtiene o establece el color de primer plano de las barras QR-Code.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Obtiene o establece el color de primer plano de las barras QR-Code.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Obtiene o establece el espacio entre los elementos QRCode y los bordes de la imagen resultante.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Obtiene o establece el espacio entre los elementos QRCode y los bordes de la imagen resultante.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Obtiene o establece la alineación del texto en la imagen QR-code resultante.
El valor predeterminado es Ninguno.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Obtiene o establece la alineación del texto en la imagen QR-code resultante.
El valor predeterminado es Ninguno.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Obtiene o establece el nombre de archivo de la imagen del logotipo QR-code.
Esta propiedad se usa solo si LogoStream no está especificado.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Obtiene o establece el nombre de archivo de la imagen del logotipo QR-code.
Esta propiedad se usa solo si LogoStream no está especificado.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Obtiene o establece el flujo de imagen del logotipo QR-code.
Si esta propiedad está especificada, siempre se usa en lugar de LogoGuid.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Obtiene o establece el flujo de imagen del logotipo QR-code.
Si esta propiedad está especificada, siempre se usa en lugar de LogoGuid.
El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Obtiene o establece el objeto personalizado para serializar al contenido QR-Code.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Obtiene o establece el objeto personalizado para serializar al contenido QR-Code.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtiene o establece la bandera para obtener el contenido de imagen QR-Code de una firma que se colocó en la página del documento.
Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtiene o establece la bandera para obtener el contenido de imagen QR-Code de una firma que se colocó en la página del documento.
Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar en el formato requerido.
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


Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen QR-Code en el formato original.
Este formato de imagen se especifica en
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen QR-Code en formato .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen QR-Code en el formato original.
Este formato de imagen se especifica en
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen QR-Code en formato .png.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
