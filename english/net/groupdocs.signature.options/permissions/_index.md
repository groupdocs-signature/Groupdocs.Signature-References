---
title: Permissions
second_title: GroupDocs.Signature for .NET API Reference
description: Specifies configurable permissions for PDF documents such as printing content modification and data extraction. These settings are applicable to PDF format only and control user access and interaction capabilities.
type: docs
weight: 1740
url: /net/groupdocs.signature.options/permissions/
---
## Permissions enumeration

Specifies configurable permissions for PDF documents, such as printing, content modification, and data extraction. These settings are applicable to PDF format only and control user access and interaction capabilities.

```csharp
[Flags]
public enum Permissions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AllowAll | `0` | Allow all actions, including printing, modification, and data extraction. |
| DenyPrinting | `1` | Deny printing of the document. |
| DenyModification | `2` | Deny content modification, including filling forms and adding or modifying annotations. |
| DenyDataExtraction | `4` | Deny extraction of text and graphics from the document. |
| DenyAll | `7` | Deny all actions, including printing, modification, and data extraction. |

### See Also

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->