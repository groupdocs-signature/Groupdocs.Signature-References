---
title: "ExportImageSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado para exportar documentos a imagen."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Opciones de guardado para exportar documentos a imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con valores predeterminados. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con el formato de archivo especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtiene o establece el número de página del documento para la exportación. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Obtiene o establece el número de página del documento para la exportación. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Bandera para exportar cada página. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Bandera para exportar cada página. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opciones para especificar las páginas a firmar. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opciones para especificar las páginas a firmar. |
|
|  | [getPageColumns()](#getPageColumns--) | Obtiene o establece el número de columnas para las imágenes exportadas. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Obtiene o establece el número de columnas para las imágenes exportadas. |
|
|  | [getBorder()](#getBorder--) | Obtiene o establece la configuración del borde de la imagen. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Obtiene o establece la configuración del borde de la imagen. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Coloca las páginas del documento en diferentes marcos en una imagen Tiff. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Coloca las páginas del documento en diferentes marcos en una imagen Tiff. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con valores predeterminados.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con el formato de archivo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Formato de archivo de imagen de salida. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Obtiene o establece el número de página del documento para la exportación.
El valor mínimo es 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Obtiene o establece el número de página del documento para la exportación.
El valor mínimo es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Bandera para exportar cada página.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Bandera para exportar cada página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opciones para especificar las páginas a firmar.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opciones para especificar las páginas a firmar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Obtiene o establece el número de columnas para las imágenes exportadas.
Utilice esta propiedad si necesita colocar imágenes en una fila.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Obtiene o establece el número de columnas para las imágenes exportadas.
Utilice esta propiedad si necesita colocar imágenes en una fila.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Obtiene o establece la configuración del borde de la imagen. Por defecto, este valor no está establecido.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Obtiene o establece la configuración del borde de la imagen. Por defecto, este valor no está establecido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Coloca las páginas del documento en diferentes marcos en una imagen Tiff.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Coloca las páginas del documento en diferentes marcos en una imagen Tiff.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
