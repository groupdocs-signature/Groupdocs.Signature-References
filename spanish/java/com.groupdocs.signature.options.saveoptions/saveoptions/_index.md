---
title: "SaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Permite especificar opciones adicionales, como contraseña, al guardar un documento para firmar."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Permite especificar opciones adicionales (como la contraseña) al guardar un documento para firmar.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Inicializa una nueva instancia de la clase SaveOptions con valores predeterminados. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Inicializa una nueva instancia de la clase SaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Obtiene o establece si se debe sobrescribir el archivo existente con el nuevo archivo de salida. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Obtiene o establece si se debe sobrescribir el archivo existente con el nuevo archivo de salida. |
|
|  | [getPassword()](#getPassword--) | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Obtiene o establece si se debe usar la contraseña de LoadOptions para guardar el documento firmado como protegido. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Obtiene o establece si se debe usar la contraseña de LoadOptions para guardar el documento firmado como protegido. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. |
El valor predeterminado es false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. |
El valor predeterminado es false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Inicializa una nueva instancia de la clase SaveOptions con valores predeterminados.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase SaveOptions con el tipo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Bandera que indica si se debe sobrescribir el archivo firmado con el mismo archivo. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Obtiene o establece si se debe sobrescribir el archivo existente con el nuevo archivo de salida.
De lo contrario, se creará un nuevo archivo con un número como sufijo.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Obtiene o establece si se debe sobrescribir el archivo existente con el nuevo archivo de salida.
De lo contrario, se creará un nuevo archivo con un número como sufijo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña.
Esta propiedad no es compatible con documentos de Imagen.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña.
Esta propiedad no es compatible con documentos de Imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Obtiene o establece si se debe usar la contraseña de LoadOptions para guardar el documento firmado como protegido.
El valor predeterminado es true.
Esta propiedad no es compatible con documentos de Imagen.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Obtiene o establece si se debe usar la contraseña de LoadOptions para guardar el documento firmado como protegido.
El valor predeterminado es true.
Esta propiedad no es compatible con documentos de Imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida.
El valor predeterminado es false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida.
El valor predeterminado es false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

