---
title: "PdfSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado para documentos PDF."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Opciones de guardado para documentos PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Inicializa una nueva instancia de la clase PdfSaveOptions con valores predeterminados. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Inicializa una nueva instancia de la clase PdfSaveOptions con la bandera de sobrescritura. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Una contraseña de permisos (la contraseña principal) requiere una contraseña para cambiar la configuración de permisos. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Una contraseña de permisos (la contraseña principal) requiere una contraseña para cambiar la configuración de permisos. |
|
|  | [getPermissions()](#getPermissions--) | Los permisos del documento PDF, como impresión, modificación y extracción de datos. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Los permisos del documento PDF, como impresión, modificación y extracción de datos. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Inicializa una nueva instancia de la clase PdfSaveOptions con valores predeterminados.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase PdfSaveOptions con la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Bandera que indica si se debe sobrescribir el archivo firmado con el mismo archivo. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | Bandera que indica si se debe sobrescribir el archivo firmado con el mismo archivo. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Obtiene o establece el formato de archivo del documento firmado.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Obtiene o establece el formato de archivo del documento firmado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Una contraseña de permisos (la contraseña principal) requiere una contraseña para cambiar la configuración de permisos.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Una contraseña de permisos (la contraseña principal) requiere una contraseña para cambiar la configuración de permisos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Los permisos del documento PDF, como impresión, modificación y extracción de datos.


Para modificar estos permisos, el
PermissionsPassword
debe establecerse.
El valor es una combinación de banderas de [Permissions](../../com.groupdocs.signature.options/permissions).
Un
null
valor significa que no se aplican permisos explícitos.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Los permisos del documento PDF, como impresión, modificación y extracción de datos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
