---
title: "ImageSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda para firmas de Imagen."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Representa opciones de búsqueda para firmas de Imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Inicializa una nueva instancia de la clase ImageSearchOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Obtiene o establece la bandera para capturar el contenido de imagen de la firma en la página del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtiene o establece la bandera para capturar el contenido de imagen de la firma en la página del documento. |
|
|  | [getMinContentSize()](#getMinContentSize--) | Para un valor distinto de cero, esta bandera especifica el tamaño mínimo de las imágenes para el criterio de búsqueda. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | Para un valor distinto de cero, esta bandera especifica el tamaño mínimo de las imágenes para el criterio de búsqueda. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | Para un valor distinto de cero, esta bandera especifica el tamaño máximo de las imágenes para el criterio de búsqueda. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | Para un valor distinto de cero, esta bandera especifica el tamaño máximo de las imágenes para el criterio de búsqueda. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Especifica el tipo de archivo del contenido devuelto de la firma de imagen cuando la propiedad ReturnContent está habilitada. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el tipo de archivo del contenido devuelto de la firma de imagen cuando la propiedad ReturnContent está habilitada. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Inicializa una nueva instancia de la clase ImageSearchOptions con valores predeterminados.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtiene o establece la bandera para capturar el contenido de imagen de la firma en la página del documento.
Si este indicador se establece en verdadero, el contenido de la firma de imagen mantendrá los datos de imagen sin procesar según el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtiene o establece la bandera para capturar el contenido de imagen de la firma en la página del documento.
Si este indicador se establece en verdadero, el contenido de la firma de imagen mantendrá los datos de imagen sin procesar según el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Para un valor distinto de cero, esta bandera especifica el tamaño mínimo de las imágenes para el criterio de búsqueda.
Por defecto, este indicador se establece en cero y no afecta el resultado de la búsqueda.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Para un valor distinto de cero, esta bandera especifica el tamaño mínimo de las imágenes para el criterio de búsqueda.
Por defecto, este indicador se establece en cero y no afecta el resultado de la búsqueda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Para un valor distinto de cero, esta bandera especifica el tamaño máximo de las imágenes para el criterio de búsqueda.
Por defecto, este indicador se establece en cero y no afecta el resultado de la búsqueda.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Para un valor distinto de cero, esta bandera especifica el tamaño máximo de las imágenes para el criterio de búsqueda.
Por defecto, este indicador se establece en cero y no afecta el resultado de la búsqueda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Especifica el tipo de archivo del contenido devuelto de la firma de imagen cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen en su formato original.
Este formato de imagen se especifica en
ImageSignature.Format

Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, entonces se devolverá el contenido de la imagen en su formato original.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Especifica el tipo de archivo del contenido devuelto de la firma de imagen cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen en su formato original.
Este formato de imagen se especifica en
ImageSignature.Format

Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, entonces se devolverá el contenido de la imagen en su formato original.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

