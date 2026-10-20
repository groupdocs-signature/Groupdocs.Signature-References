---
title: "SpreadsheetSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado para documentos de hoja de cálculo."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Opciones de guardado para documentos de hoja de cálculo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con valores predeterminados. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con el formato de archivo de salida predefinido. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con valores predeterminados.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con el formato de archivo de salida predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Especifica el formato de archivo de salida. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con el tipo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Especifica el formato de archivo de salida. |
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
