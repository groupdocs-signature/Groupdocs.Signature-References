---
title: "PreviewOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Inicializa el objeto PreviewOptions."
type: docs
weight: 10
url: /es/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreateDocPageStream, int, params int[]) {#constructor}

Inicializa el objeto PreviewOptions.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, int resolution = 96, 
    params int[] pageNumbers)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegado que define el método para crear el flujo de vista previa de la página del documento de salida. |
| resolución | Int32 | Resolución de las imágenes de vista previa en DPI (opcional). |
| pageNumbers | Int32[] | Números de página deseados |

### Ver también

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreateDocPageStream, ReleaseDocPageStream, int, params int[]) {#constructor_1}

Inicializa el objeto PreviewOptions.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, ReleaseDocPageStream releasePageStream, 
    int resolution = 96, params int[] pageNumbers)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegado que define el método para crear el flujo de vista previa de la página del documento de salida. |
| releasePageStream | ReleaseDocPageStream | Delegado que define el método para liberar el flujo de vista previa de la página del documento de salida. |
| resolución | Int32 | Resolución de las imágenes de vista previa en DPI (opcional). |
| pageNumbers | Int32[] | Números de página deseados |

### Ver también

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* delegate [ReleaseDocPageStream](../../previewoptions.releasedocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
