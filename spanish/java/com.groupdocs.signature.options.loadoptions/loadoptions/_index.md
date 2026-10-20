---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Permite especificar opciones adicionales, como la contraseña, al abrir un documento para firmar."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Permite especificar opciones adicionales (como la contraseña) al abrir un documento para firmar.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inicializa una nueva instancia de la clase LoadOptions. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Inicializa una nueva instancia de la clase LoadOptions con un tipo de archivo especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Obtiene o establece la contraseña para abrir un documento protegido. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña para abrir un documento protegido. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | Obtiene o establece una bandera que indica si los recursos almacenados fuera del documento se omiten al cargarlo. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Obtiene o establece una bandera que indica si los recursos almacenados fuera del documento se omiten al cargarlo. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Obtiene o establece partes de direcciones de recursos externos que pueden cargarse mientras |
#getSkipExternalResources().getSkipExternalResources() es verdadero.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Obtiene o establece partes de direcciones de recursos externos que pueden cargarse mientras |
#getSkipExternalResources().getSkipExternalResources() es verdadero.
|
|  | [getPermissions()](#getPermissions--) | Los permisos del documento PDF, como impresión, modificación y extracción de datos. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Establecedor interno, usado por los procesadores de carga de documentos para registrar los permisos analizados del archivo. |
|
|  | [getFileType()](#getFileType--) | Obtiene el tipo de archivo del documento. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Establece el tipo de archivo del documento, de modo que no se detecte a partir del contenido del documento. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inicializa una nueva instancia de la clase LoadOptions.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase LoadOptions con un tipo de archivo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | El tipo de archivo del documento, vea #setFileType(FileType).setFileType(FileType). |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene o establece la contraseña para abrir un documento protegido.
También se usará para guardar el documento firmado como protegido.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtiene o establece la contraseña para abrir un documento protegido.
También se usará para guardar el documento firmado como protegido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Obtiene o establece una bandera que indica si los recursos almacenados fuera del documento se omiten al cargarlo.
El valor predeterminado es verdadero.


Un documento puede referirse a recursos externos: imágenes vinculadas y campos INCLUDEPICTURE en procesamiento de texto
documentos, imágenes vinculadas en presentaciones y hojas de cálculo, imágenes y hojas de estilo a las que hace referencia una imagen SVG.
Cargar dicho recurso significa solicitar la dirección escrita en el documento. En un servidor que procesa
documentos de otras personas, lo cual representa un riesgo de falsificación de solicitudes del lado del servidor, y en una instalación fuera de línea el
solicitud falla o espera un tiempo de espera.


Cuando es verdadero, los recursos externos no se cargan, excepto aquellos cuya dirección contiene uno de
#getWhitelistedResources().getWhitelistedResources(). Los recursos omitidos no se dibujan en vistas previas de página o en documentos guardados como
imágenes, y imagen, código de barras y código QR la búsqueda no los ve. Imágenes incrustadas no se ven afectadas, y
Los hipervínculos nunca se siguen. La configuración también se aplica a documentos dentro de archivos.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Obtiene o establece una bandera que indica si los recursos almacenados fuera del documento se omiten al cargarlo.
El valor predeterminado es true. Ver #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Obtiene o establece partes de direcciones de recursos externos que pueden cargarse mientras
#getSkipExternalResources().getSkipExternalResources() es true. Se carga una dirección cuando contiene una de ellas, sin distinguir mayúsculas y minúsculas.
Los valores vacíos se ignoran. El predeterminado es una lista vacía; establecer null lo borra.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Obtiene o establece partes de direcciones de recursos externos que pueden cargarse mientras
#getSkipExternalResources().getSkipExternalResources() es true. Ver #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Los permisos del documento PDF, como impresión, modificación y extracción de datos.
Solo para documentos PDF. Solo lectura \\u2014 poblado automáticamente al cargar el documento.
El valor es una combinación de banderas de [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Establecedor interno, usado por los procesadores de carga de documentos para registrar los permisos analizados del archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Obtiene el tipo de archivo del documento. Cuando es [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (el predeterminado),
el tipo de archivo se detecta a partir del contenido del documento.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Establece el tipo de archivo del documento, de modo que no se detecte a partir del contenido del documento.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

