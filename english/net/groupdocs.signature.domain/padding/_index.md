---
title: Padding
second_title: GroupDocs.Signature for .NET API Reference
description: Represents padding or margin information associated with element.
type: docs
weight: 600
url: /net/groupdocs.signature.domain/padding/
---
## Padding class

Represents padding or margin information associated with element.

```csharp
public class Padding : ICloneable
```

## Constructors

| Name | Description |
| --- | --- |
| [Padding](padding#constructor)() | Initializes a new instance of Padding class using zero values. |
| [Padding](padding#constructor_1)(int) | Initializes a new instance of the Padding class using the supplied padding size for all edges. |
| [Padding](padding#constructor_2)(int, int, int, int) | Initializes a new instance of the Padding class using the supplied padding sizes. |

## Properties

| Name | Description |
| --- | --- |
| [All](../../groupdocs.signature.domain/padding/all) { get; set; } | Gets or sets the padding value for all the edges. Changing of any partial edge like left or top makes this property equal 0; |
| [Bottom](../../groupdocs.signature.domain/padding/bottom) { get; set; } | Gets or sets the padding value for the bottom edge. |
| [Horizontal](../../groupdocs.signature.domain/padding/horizontal) { get; } | Gets the combined padding for the right and left edges. |
| [Left](../../groupdocs.signature.domain/padding/left) { get; set; } | Gets or sets the padding value for the left edge. |
| [Right](../../groupdocs.signature.domain/padding/right) { get; set; } | Gets or sets the padding value for the right edge. |
| [Top](../../groupdocs.signature.domain/padding/top) { get; set; } | Gets or sets the padding value for the top edge. |
| [Vertical](../../groupdocs.signature.domain/padding/vertical) { get; } | Gets the combined padding for the top and bottom edges. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../groupdocs.signature.domain/padding/clone)() | Gets a copy of this object. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Empty](../../groupdocs.signature.domain/padding/empty) | Provides a Padding object with no padding. |

### See Also

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->