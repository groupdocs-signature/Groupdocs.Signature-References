---
title: "TextSignatureImplementation"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Especifica el tipo de implementación para la firma de texto PDF."
type: docs
weight: 32
url: /es/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Especifica el tipo de implementación para la firma de texto PDF.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Native](#Native) | Firma de texto como objeto de texto nativo en la página del documento. |
|
|  | [Image](#Image) | Firma de texto como objeto de imagen en la página del documento. |
|
|  | [Annotation](#Annotation) | Firma de texto como objeto de anotación de texto en la página PDF. |
|
|  | [Sticker](#Sticker) | Firma de texto como objeto de pegatina en la página PDF. |
|
|  | [FormField](#FormField) | Firma de texto como texto en el campo de formulario especificado. |
|
|  | [Watermark](#Watermark) | Firma de texto como marca de agua en la página del documento. |
|
### Native {#Native}
```
public static final int Native
```


Firma de texto como objeto de texto nativo en la página del documento.


### Image {#Image}
```
public static final int Image
```


Firma de texto como objeto de imagen en la página del documento.


### Annotation {#Annotation}
```
public static final int Annotation
```


Firma de texto como objeto de anotación de texto en la página PDF.
Las anotaciones son visibles solo en la versión con licencia.


### Sticker {#Sticker}
```
public static final int Sticker
```


Firma de texto como objeto de pegatina en la página PDF.


### FormField {#FormField}
```
public static final int FormField
```


Firma de texto como texto en el campo de formulario especificado.
Con este tipo de implementación solo se puede usar TextSignOptions.Text,
Opciones TextSignOptions.FormTextFieldType y TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


Firma de texto como marca de agua en la página del documento.


