---
title: "PdfTextStickerAppearance"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Describe la apariencia del objeto adhesivo de anotación de texto PDF y la ventana emergente del adhesivo."
type: docs
weight: 1420
url: /es/net/groupdocs.signature.options.appearances/pdftextstickerappearance/
---
## PdfTextStickerAppearance class

Describe la apariencia del objeto de etiqueta de anotación de texto PDF y la ventana emergente de la etiqueta.

```csharp
public sealed class PdfTextStickerAppearance : SignatureAppearance
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfTextStickerAppearance](pdftextstickerappearance)() | Crea un objeto de apariencia de anotación de texto de firma PDF. |

## Properties

| Nombre | Descripción |
| --- | --- |
| static [DefaultAppearance](../../groupdocs.signature.options.appearances/pdftextstickerappearance/defaultappearance) { get; } | Obtiene la apariencia predeterminada para el adhesivo. Estas propiedades se aplican por defecto si la propiedad Options.SignatureAppearance no está especificada. El usuario puede cambiar las propiedades en cualquier momento. |
| [Contents](../../groupdocs.signature.options.appearances/pdftextstickerappearance/contents) { get; set; } | Obtiene o establece el contenido de la ventana emergente. |
| [Icon](../../groupdocs.signature.options.appearances/pdftextstickerappearance/icon) { get; set; } | Obtiene o establece el ícono del adhesivo. |
| [Opened](../../groupdocs.signature.options.appearances/pdftextstickerappearance/opened) { get; set; } | Configure si la ventana emergente del adhesivo se abrirá por defecto. |
| [Subject](../../groupdocs.signature.options.appearances/pdftextstickerappearance/subject) { get; set; } | Obtiene o establece el asunto. |
| [Title](../../groupdocs.signature.options.appearances/pdftextstickerappearance/title) { get; set; } | Obtiene o establece el título de la ventana emergente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ResetDefaultAppearance](../../groupdocs.signature.options.appearances/pdftextstickerappearance/resetdefaultappearance)() | Borra los valores de la apariencia predeterminada del adhesivo. |

### Ver también

* class [SignatureAppearance](../signatureappearance)
* namespace [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
