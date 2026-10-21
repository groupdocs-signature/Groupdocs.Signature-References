---
title: "PreviewSignatureOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Inicializa el objeto PreviewSignatureOptions."
type: docs
weight: 10
url: /es/net/groupdocs.signature.options/previewsignatureoptions/previewsignatureoptions/
---
## PreviewSignatureOptions(SignOptions, CreateSignatureStream) {#constructor}

Inicializa el objeto PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, CreateSignatureStream createSignatureStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signOptions | SignOptions | Las opciones de firma para generar la vista previa. |
| createSignatureStream | CreateSignatureStream | Delegado que define el método para crear el flujo de vista previa de firma de salida. |

### Ver también

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

---

## PreviewSignatureOptions(SignOptions, CreateSignatureStream, ReleaseSignatureStream) {#constructor_1}

Inicializa el objeto PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, 
    CreateSignatureStream createSignatureStream, ReleaseSignatureStream releaseSignatureStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signOptions | SignOptions | Las opciones de firma para generar la vista previa. |
| createSignatureStream | CreateSignatureStream | Delegado que define el método para crear el flujo de vista previa de firma de salida. |
| releaseSignatureStream | ReleaseSignatureStream | Delegado que define el método para liberar el flujo de vista previa de firma de salida. |

### Ver también

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* delegate [ReleaseSignatureStream](../../releasesignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
