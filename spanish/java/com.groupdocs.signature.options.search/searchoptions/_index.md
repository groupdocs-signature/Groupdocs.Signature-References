---
title: "SearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de extracción de firmas del documento."
type: docs
weight: 17
url: /es/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Representa las opciones de extracción de firmas del documento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtiene o establece el número de página del Document para la búsqueda. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Obtiene o establece el número de página del Document para la búsqueda. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opciones para especificar páginas para la búsqueda de Signature. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opciones para especificar páginas para la búsqueda de Signature. |
|
|  | [getAllPages()](#getAllPages--) | Indicador para buscar en cada página del Document. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Indicador para buscar en cada página del Document. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Indicador para devolver solo firmas marcadas como IsSignature. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Indicador para devolver solo firmas marcadas como IsSignature. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Método virtual para obtener la lista de páginas para la extracción de Signature. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Obtiene o establece el número de página del Document para la búsqueda.
El valor es opcional.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Obtiene o establece el número de página del Document para la búsqueda.
El valor es opcional.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opciones para especificar páginas para la búsqueda de Signature.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opciones para especificar páginas para la búsqueda de Signature.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Indicador para buscar en cada página del Document. Por defecto, este valor se establece en true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Indicador para buscar en cada página del Document. Por defecto, este valor se establece en true.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Indicador para devolver solo firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Indicador para devolver solo firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Método virtual para obtener la lista de páginas para la extracción de Signature.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | totalPages | int | Cantidad total de páginas |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Lista de números de página

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
