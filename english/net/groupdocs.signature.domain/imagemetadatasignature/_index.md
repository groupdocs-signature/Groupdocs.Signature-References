---
title: ImageMetadataSignature
second_title: GroupDocs.Signature for .NET API Reference
description: Contains Image Metadata signature properties.
type: docs
weight: 640
url: /net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Contains Image Metadata signature properties.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Creates Image Metadata Signature with Id and value |

## Properties

| Name | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Get or set the signature creation date. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Gets or sets implementation of [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode signature Value properties. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Get the flag that indicates if this signature was deleted from the document. This property is being used only for document history log records to keep the list of deleted signatures. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Read-only value to get description for standard Image Metadata signature |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifies height of signature. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | The identifier of Image Metadata signature. See ImageMetadataSignatures class that contains standard Signature with predefined Id value. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifies left position of signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Get or set the signature modification date. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specifies unique metadata name. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifies the page signature was found on. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unique signature identifier to modify signature in the document over Update or Delete methods. This property will be set automatically after Sign or Search method being called. If this property was saved before it can be set manually to manipulate the signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifies the type of signature. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Read-only value to get size of Metadata value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifies top position of signature. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specifies metadata value type. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifies metadata object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifies width of signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clone Metadata Signature instance. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Clone Image Metadata Signature instance with given value. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Overwrites Equals method to compare signature properties |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtain object from Metadata Signature Value over deserialization. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtain object from Metadata Signature Text over deserialization. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Overrides GetHashCode method |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Converts to boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Converts to DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Converts to DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Converts to Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Converts to Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Converts to Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Converts to Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Converts to integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Converts to long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Converts to float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Converts to float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Converts to String with override ToString() method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Converts to String with specified format |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converts to String with specified format |

### See Also

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
