---
title: "TextSignatureImplementation"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica el tipo de implementación para la firma de texto PDF."
type: docs
weight: 1200
url: /es/net/groupdocs.signature.domain/textsignatureimplementation/
---
## TextSignatureImplementation enumeration

Especifica el tipo de implementación para la firma de texto PDF.

```csharp
public enum TextSignatureImplementation
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| Native | `1` | Firma de texto como objeto de texto nativo en la página del documento. |
| Image | `2` | Firma de texto como objeto de Imagen en la página del documento. |
| Annotation | `3` | Firma de texto como objeto de Anotación de Texto en la página PDF. Las anotaciones son visibles solo en la versión con licencia. |
| Sticker | `4` | Firma de texto como objeto de Pegatina en la página PDF. |
| FormField | `5` | Firma de texto como texto en un campo de formulario especificado. Con este tipo de implementación solo pueden usarse las opciones TextSignOptions.Text, TextSignOptions.FormTextFieldType y TextSignOptions.FormTextFieldTitle. |
| Watermark | `6` | Firma de texto como marca de agua en la página del documento. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
