---
title: "MetadataSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma de metadatos."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Representa las opciones de firma de metadatos.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | Inicializa una nueva instancia de la clase SignMetadataOptions con valores predeterminados. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Inicializa una nueva instancia de la clase SignMetadataOptions con Metadatos. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | Obtiene o establece los Metadatos de la firma. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Obtiene o establece los Metadatos de la firma. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crea una nueva PdfMetadataSignature con los argumentos proporcionados y la agrega a la colección. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Crea una nueva ImageMetadataSignature con los argumentos proporcionados y la agrega a la colección. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Agrega una instancia existente de MetadataSignature a la colección. |
|
|  | [validate()](#validate--) | Método interno para validar los parámetros de opciones. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Inicializa una nueva instancia de la clase SignMetadataOptions con valores predeterminados.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Inicializa una nueva instancia de la clase SignMetadataOptions con Metadatos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Colección de firmas de Metadatos [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Obtiene o establece los Metadatos de la firma.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Obtiene o establece los Metadatos de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

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

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Crea una nueva PdfMetadataSignature con los argumentos proporcionados y la agrega a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de firma de Metadatos |
|
|  | valor | java.lang.Object | Valor de la firma de Metadatos |
|
|  | tag | java.lang.String | Etiqueta de prefijo de la firma de Metadatos |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Crea una nueva ImageMetadataSignature con los argumentos proporcionados y la agrega a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | int | Identificador único del nombre de la firma de Metadatos de Imagen. Consulte las referencias para las especificaciones de etiquetas Exif y los posibles valores de id. |
|
|  | valor | java.lang.Object | Valor de Metadatos |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Agrega una instancia existente de MetadataSignature a la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | La instancia existente de MetadataSignature que se agregará |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


Método interno para validar los parámetros de opciones.


### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
