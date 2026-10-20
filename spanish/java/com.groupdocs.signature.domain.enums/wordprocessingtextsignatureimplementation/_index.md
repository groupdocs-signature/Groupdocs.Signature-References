---
title: "WordProcessingTextSignatureImplementation"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Especifica el tipo de implementación de firma de texto para documentos de procesamiento de texto."
type: docs
weight: 36
url: /es/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Especifica el tipo de implementación de firma de texto para documentos de procesamiento de texto.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [TextStamp](#TextStamp) | Firma de texto como objeto Etiqueta en la página de Words. |
|
|  | [TextAsImage](#TextAsImage) | Firma de texto como objeto Imagen en la página de Words. |
|
|  | [TextToFormField](#TextToFormField) | Firma de texto como texto en el campo de formulario especificado. |
|
|  | [Watermark](#Watermark) | Firma de texto como marca de agua en la página de Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Firma de texto como objeto Etiqueta en la página de Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Firma de texto como objeto Imagen en la página de Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Firma de texto como texto en el campo de formulario especificado.
Con este tipo de implementación solo se puede usar TextSignOptions.Text,
Opciones TextSignOptions.FormTextFieldTitle y TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Firma de texto como marca de agua en la página de Words.


