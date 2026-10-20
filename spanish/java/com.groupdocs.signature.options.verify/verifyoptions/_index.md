---
title: "VerifyOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Mantiene opciones para verificar el documento."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Mantiene opciones para verificar el documento.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid()](#isValid--) | Bandera de propiedad válida. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Bandera de propiedad válida. |
|
|  | [getPageNumber()](#getPageNumber--) | Número de página del documento a verificar. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Número de página del documento a verificar. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opciones de página para especificar las páginas a verificar. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opciones de página para especificar las páginas a verificar. |
|
|  | [getAllPages()](#getAllPages--) | Bandera para verificar cada página del documento. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Bandera para verificar cada página del documento. |
|
|  | [getExtensions()](#getExtensions--) | Extensiones adicionales para la verificación de opciones de firma alternativas. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Extensiones adicionales para la verificación de opciones de firma alternativas. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Bandera de propiedad válida.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Bandera de propiedad válida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Número de página del documento a verificar. Si la propiedad no está establecida, se verifican todas las páginas de
El documento será verificado para la primera aparición.
El valor mínimo es 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Número de página del documento a verificar. Si la propiedad no está establecida, se verifican todas las páginas de
El documento será verificado para la primera aparición.
El valor mínimo es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opciones de página para especificar las páginas a verificar.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opciones de página para especificar las páginas a verificar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Bandera para verificar cada página del documento. Por defecto, el valor es verdadero.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Bandera para verificar cada página del documento. Por defecto, el valor es verdadero.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Extensiones adicionales para la verificación de opciones de firma alternativas.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Extensiones adicionales para la verificación de opciones de firma alternativas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
