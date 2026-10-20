---
title: "WordProcessingSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado para documentos de procesamiento de texto."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Opciones de guardado para documentos de procesamiento de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con valores predeterminados. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | Nivel de cumplimiento OOXML opcional para el documento firmado. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | Nivel de cumplimiento OOXML opcional para el documento firmado. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Inicializa una nueva instancia de la clase WordProcessingSaveOptions con valores predeterminados.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el tipo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Bandera que indica si se debe sobrescribir el archivo firmado con el mismo archivo. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | int | Tipo de archivo de salida [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


Nivel de cumplimiento OOXML opcional para el documento firmado. Cuando se establece, sobrescribe el
cumplimiento del documento original. Cuando
null
(predeterminado), el cumplimiento del documento cargado
se conserva. Sólo se respeta para formatos OOXML
(Docx, Docm, Dotx, Dotm, FlatOpc y variantes FlatOpc).


El valor es uno de [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


Nivel de cumplimiento OOXML opcional para el documento firmado. Cuando se establece, sobrescribe el
cumplimiento del documento original. Cuando
null
(predeterminado), el cumplimiento del documento cargado
se conserva. Sólo se respeta para formatos OOXML
(Docx, Docm, Dotx, Dotm, FlatOpc y variantes FlatOpc).


El valor es uno de [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena


**Returns:**
java.lang.String - 
