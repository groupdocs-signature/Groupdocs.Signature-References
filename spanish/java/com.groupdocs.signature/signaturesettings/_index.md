---
title: "SignatureSettings"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Define la configuración para personalizar el comportamiento."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Define la configuración para personalizar el comportamiento de [Signature](../../com.groupdocs.signature/signature).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Crea una instancia predeterminada de SignatureSettings con valores por defecto. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Crea una instancia predeterminada de SignatureSettings con la implementación de Logger. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Obtiene o establece la cultura predeterminada que se usará durante el procesamiento de documentos. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Obtiene o establece la cultura predeterminada que se usará durante el procesamiento de documentos. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Obtiene o establece la bandera que incluye firmas eliminadas en el resultado de Document Info. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Obtiene o establece la bandera que incluye firmas eliminadas en el resultado de Document Info. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas que eliminar. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas que eliminar. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Obtiene o establece la bandera para incluir en la Lista de Metadatos las firmas de metadatos estándar incrustadas del documento, como Autor, Propietario, fecha de creación del documento, fecha de modificación, etc. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Obtiene o establece la bandera para incluir en la Lista de Metadatos las firmas de metadatos estándar incrustadas del documento, como Autor, Propietario, fecha de creación del documento, fecha de modificación, etc. |
|
|  | [getLogger()](#getLogger--) | La implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). |
|
|  | [getLogLevel()](#getLogLevel--) | Obtiene o establece qué tipos de mensajes se envían al registrador. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Obtiene o establece qué tipos de mensajes se envían al registrador. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Crea una instancia predeterminada de SignatureSettings con valores por defecto.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Crea una instancia predeterminada de SignatureSettings con la implementación de Logger.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Obtiene o establece la cultura predeterminada que se usará durante el procesamiento de documentos. El valor predeterminado es "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Obtiene o establece la cultura predeterminada que se usará durante el procesamiento de documentos. El valor predeterminado es "en-US".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Obtiene o establece la bandera que incluye firmas eliminadas en el resultado de Document Info.
Cada firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) tiene la bandera Deleted.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) para detectar si fue eliminado.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Obtiene o establece la bandera que incluye firmas eliminadas en el resultado de Document Info.
Cada firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) tiene la bandera Deleted.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) para detectar si fue eliminado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar.
Si esta bandera está establecida en true (por defecto), el documento se guardará con el registro de historial de proceso correspondiente (fecha y tipo de operación) incluso si el método Update no tiene firmas que actualizar.
Cuando esta bandera está establecida en false, el documento fuente no se modificará en absoluto.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar.
Si esta bandera está establecida en true (por defecto), el documento se guardará con el registro de historial de proceso correspondiente (fecha y tipo de operación) incluso si el método Update no tiene firmas que actualizar.
Cuando esta bandera está establecida en false, el documento fuente no se modificará en absoluto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas que eliminar.
Si esta bandera está establecida en true (por defecto), el documento se guardará con el registro de historial de proceso correspondiente (fecha y tipo de operación) incluso si el método Delete no tiene firmas que eliminar.
Cuando esta bandera está establecida en false, el documento fuente no se modificará en absoluto.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas que eliminar.
Si esta bandera está establecida en true (por defecto), el documento se guardará con el registro de historial de proceso correspondiente (fecha y tipo de operación) incluso si el método Delete no tiene firmas que eliminar.
Cuando esta bandera está establecida en false, el documento fuente no se modificará en absoluto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Obtiene o establece la bandera para incluir en la Lista de Metadatos las firmas de metadatos estándar incrustadas del documento, como Autor, Propietario, fecha de creación del documento, fecha de modificación, etc.
Si esta bandera está establecida en false (por defecto), el método GetDocumentInfo no incluirá estas firmas de metadatos.
Cuando esta bandera está establecida en true, la información del documento incluirá estas firmas de metadatos estándar.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Obtiene o establece la bandera para incluir en la Lista de Metadatos las firmas de metadatos estándar incrustadas del documento, como Autor, Propietario, fecha de creación del documento, fecha de modificación, etc.
Si esta bandera está establecida en false (por defecto), el método GetDocumentInfo no incluirá estas firmas de metadatos.
Cuando esta bandera está establecida en true, la información del documento incluirá estas firmas de metadatos estándar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


La implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Obtiene o establece qué tipos de mensajes se envían al registrador.
El valor es un conjunto de [LogLevel](../../com.groupdocs.signature.logging/loglevel) banderas que pueden combinarse, por ejemplo

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
no registra nada.
El valor predeterminado es
LogLevel.All
: errores, advertencias y rastros.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Obtiene o establece qué tipos de mensajes se envían al registrador.
El valor es un conjunto de [LogLevel](../../com.groupdocs.signature.logging/loglevel) banderas que pueden combinarse, por ejemplo

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
no registra nada.
El valor predeterminado es
LogLevel.All
: errores, advertencias y rastros.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

