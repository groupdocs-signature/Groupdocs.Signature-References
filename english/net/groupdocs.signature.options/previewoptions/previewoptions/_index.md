---
title: PreviewOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Initializes PreviewOptions object.
type: docs
weight: 10
url: /net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreateDocPageStream, params int[]) {#constructor}

Initializes PreviewOptions object.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, params int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegate which defines method to create output document page preview stream. |
| pageNumbers | Int32[] | Desired page numbers |

### See Also

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreateDocPageStream, ReleaseDocPageStream, params int[]) {#constructor_1}

Initializes PreviewOptions object.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, ReleaseDocPageStream releasePageStream, 
    params int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegate which defines method to create output document page preview stream. |
| releasePageStream | ReleaseDocPageStream | Delegate which defines method to release output document page preview stream. |
| pageNumbers | Int32[] | Desired page numbers |

### See Also

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* delegate [ReleaseDocPageStream](../../previewoptions.releasedocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
