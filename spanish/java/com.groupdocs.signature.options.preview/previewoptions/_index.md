---
title: "PreviewOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de vista previa de documentos."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Representa las opciones de vista previa de documentos.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Inicializa el objeto PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Inicializa el objeto PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Inicializa el objeto PreviewOptions. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene o establece el ancho de las imágenes de vista previa. |
|
|  | [setWidth(int value)](#setWidth-int-) | Obtiene o establece el ancho de las imágenes de vista previa. |
|
|  | [getHeight()](#getHeight--) | Obtiene o establece la altura de las imágenes de vista previa. |
|
|  | [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura de las imágenes de vista previa. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtiene o establece los números de página de las imágenes de vista previa. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Obtiene o establece los números de página de las imágenes de vista previa. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtiene o establece el formato de imágenes de vista previa. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Obtiene o establece el formato de imágenes de vista previa. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Obtiene o establece la bandera para ocultar firmas de la imagen de vista previa de la página. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Obtiene o establece la bandera para ocultar firmas de la imagen de vista previa de la página. |
|
|  | [getResolution()](#getResolution--) | Obtiene la resolución de las imágenes de vista previa en DPI (puntos por pulgada). |
|
|  | [setResolution(int value)](#setResolution-int-) | Establece la resolución de las imágenes de vista previa en DPI (puntos por pulgada). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Inicializa el objeto PreviewOptions.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Interfaz que define el método para crear el flujo de vista previa de la página de salida. |
|
|  | pageNumbers | int[] | Números de página deseados |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Inicializa el objeto PreviewOptions.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Interfaz que define el método para crear el flujo de vista previa de la página de salida. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Inicializa el objeto PreviewOptions.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Ruta al archivo de salida. |
|
|  | pageNumbers | int[] | Números de página deseados |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene o establece el ancho de las imágenes de vista previa.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Obtiene o establece el ancho de las imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene o establece la altura de las imágenes de vista previa.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Obtiene o establece la altura de las imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtiene o establece los números de página de las imágenes de vista previa.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Obtiene o establece los números de página de las imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtiene o establece el formato de imágenes de vista previa.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Obtiene o establece el formato de imágenes de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Obtiene o establece la bandera para ocultar firmas de la imagen de vista previa de la página.
Solo las firmas marcadas como IsSignature se ocultarán de la imagen de página del documento generado.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Obtiene o establece la bandera para ocultar firmas de la imagen de vista previa de la página.
Solo las firmas marcadas como IsSignature se ocultarán de la imagen de página del documento generado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Obtiene la resolución de las imágenes de vista previa en DPI (puntos por pulgada).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Establece la resolución de las imágenes de vista previa en DPI (puntos por pulgada).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

