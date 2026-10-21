---
title: "WordProcessingTextSignatureImplementation"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica el tipo de implementación de firma de texto para documentos de WordProcessing."
type: docs
weight: 1280
url: /es/net/groupdocs.signature.domain/wordprocessingtextsignatureimplementation/
---
## WordProcessingTextSignatureImplementation enumeration

Especifica el tipo de implementación de firma de texto para documentos de WordProcessing.

```csharp
public enum WordProcessingTextSignatureImplementation
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| TextStamp | `0` | Firma de texto como objeto Etiqueta en la página de Words. |
| TextAsImage | `1` | Firma de texto como objeto Imagen en la página de Words. |
| TextToFormField | `2` | Firma de texto como texto en el campo de formulario especificado. Con este tipo de implementación solo se pueden usar las opciones TextSignOptions.Text, TextSignOptions.FormTextFieldTitle y TextSignOptions.FormTextFieldType. |
| Watermark | `3` | Firma de texto como marca de agua en la página de Words. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
