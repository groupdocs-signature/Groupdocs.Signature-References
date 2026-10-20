---
title: "MetadataSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda abstractas para firmas de Metadata."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Representa opciones de búsqueda abstractas para firmas de Metadata.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Inicializa una nueva instancia de la clase SearchMetadataOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Especifica el nombre de la firma de metadatos si debe buscarse y coincidir. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Especifica el nombre de la firma de metadatos si debe buscarse y coincidir. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Obtiene o establece el tipo de coincidencia del nombre de metadatos en la búsqueda. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Obtiene o establece el tipo de coincidencia del nombre de metadatos en la búsqueda. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Indica si las propiedades integradas del documento, como estadísticas del documento, información, etc., deben incluirse en el resultado de la búsqueda. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Indica si las propiedades integradas del documento, como estadísticas del documento, información, etc., deben incluirse en el resultado de la búsqueda. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Inicializa una nueva instancia de la clase SearchMetadataOptions con valores predeterminados.


### getName() {#getName--}
```
public final String getName()
```


Especifica el nombre de la firma de metadatos si debe buscarse y coincidir.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Especifica el nombre de la firma de metadatos si debe buscarse y coincidir.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Obtiene o establece el tipo de coincidencia del nombre de metadatos en la búsqueda. Se usa solo cuando la propiedad Name está establecida.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Obtiene o establece el tipo de coincidencia del nombre de metadatos en la búsqueda. Se usa solo cuando la propiedad Name está establecida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Indica si las propiedades integradas del documento, como estadísticas del documento, información, etc., deben incluirse en el resultado de la búsqueda.
Este indicador tiene sentido para los tipos de archivo de documentos de Presentación, Hoja de cálculo y Procesamiento de texto.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Indica si las propiedades integradas del documento, como estadísticas del documento, información, etc., deben incluirse en el resultado de la búsqueda.
Este indicador tiene sentido para los tipos de archivo de documentos de Presentación, Hoja de cálculo y Procesamiento de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

