---
title: "TextShadow"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las propiedades de sombra de texto para firmas de texto. El resultado puede variar según el tipo de firma y el formato del documento. Se recomienda TextShadow para usar con la firma TextAsImage en todos los tipos de documento compatibles, también con TextSignature simple y TextSignature como marca de agua para Spreadsheets .xslx y Presentations .pptx. También se recomienda TextSignature simple para Words .docx, aunque tiene funcionalidad limitada."
type: docs
weight: 560
url: /es/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

Representa las propiedades de sombra de texto para firmas de texto. El resultado puede variar según el tipo de firma y el formato del documento. Se recomienda TextShadow para usar con la firma TextAsImage en todos los tipos de documento compatibles, también con TextSignature simple y TextSignature como marca de agua para Hojas de cálculo (.xslx) y Presentaciones (.pptx). TextSignature simple para Word (.docx) también se recomienda, pero tiene funcionalidad limitada.

```csharp
public class TextShadow : SignatureExtension
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextShadow](textshadow)() | Crea TextShadow con opciones predeterminadas. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | Obtiene o establece el ángulo para colocar la sombra en relación con el texto. El valor predeterminado es 0. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | Obtiene o establece el desenfoque de la sombra. El valor predeterminado es 4. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | Obtiene o establece el color de la sombra. El valor predeterminado es Negro. |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | Obtiene o establece la distancia del texto a la sombra. El valor predeterminado es 1. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | Obtiene o establece la transparencia de la sombra. El valor predeterminado es 0. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Obtiene una copia de este objeto. |

### Ver también

* class [SignatureExtension](../signatureextension)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
