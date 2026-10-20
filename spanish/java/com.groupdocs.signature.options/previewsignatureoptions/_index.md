---
title: "PreviewSignatureOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de vista previa de la firma."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Representa opciones de vista previa de la firma.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Inicializa el objeto PreviewSignatureOptions. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Valor único para distinguir la firma. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Valor único para distinguir la firma. |
|
|  | [getSignOptions()](#getSignOptions--) | Opciones de firma para generar vista previa. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Opciones de firma para generar vista previa. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtiene o establece el formato de imágenes de vista previa. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Obtiene o establece el formato de imágenes de vista previa. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Inicializa el objeto PreviewSignatureOptions.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Las opciones de firma para generar la vista previa. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Interfaz que define el método para crear el flujo de vista previa de la página de salida. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Valor único para distinguir la firma.
Utilice SignatureId para identificar las opciones de vista previa.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Valor único para distinguir la firma.
Utilice SignatureId para identificar las opciones de vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Opciones de firma para generar vista previa.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Opciones de firma para generar vista previa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtiene o establece el formato de imágenes de vista previa.
El valor predeterminado es PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Obtiene o establece el formato de imágenes de vista previa.
El valor predeterminado es PNG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

