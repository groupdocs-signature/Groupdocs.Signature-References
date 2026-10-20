---
title: "PresentationSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado para documentos de presentación."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Opciones de guardado para documentos de presentación.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Inicializa una nueva instancia de la clase PresentationSaveOptions con valores predeterminados. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Inicializa una nueva instancia de la clase PresentationSaveOptions con el formato de archivo de salida especificado. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Inicializa una nueva instancia de la clase PresentationSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Inicializa una nueva instancia de la clase PresentationSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Inicializa una nueva instancia de la clase PresentationSaveOptions con valores predeterminados.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Inicializa una nueva instancia de la clase PresentationSaveOptions con el formato de archivo de salida especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase PresentationSaveOptions con el tipo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Bandera que indica si se debe sobrescribir el archivo firmado con el mismo archivo. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase PresentationSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
