---
title: PresentationMetadataSignature
second_title: GroupDocs.Signature for .NET API Reference
description: Contains Presentation metadata signature properties.
type: docs
weight: 840
url: /net/groupdocs.signature.domain/presentationmetadatasignature/
---
## PresentationMetadataSignature class

Contains Presentation metadata signature properties.

```csharp
public sealed class PresentationMetadataSignature : MetadataSignature
```

## Constructors

| Name | Description |
| --- | --- |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor)(string) | Creates Presentation Metadata Signature with predefined name and empty value |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor_1)(string, object) | Creates Presentation Metadata Signature with predefined values |

## Properties

| Name | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Get or set the signature creation date. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Gets or sets implementation of [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode signature Value properties. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Get the flag that indicates if this signature was deleted from the document. This property is being used only for document history log records to keep the list of deleted signatures. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifies height of signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifies left position of signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Get or set the signature modification date. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specifies unique metadata name. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifies the page signature was found on. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unique signature identifier to modify signature in the document over Update or Delete methods. This property will be set automatically after Sign or Search method being called. If this property was saved before it can be set manually to manipulate the signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifies the type of signature. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifies top position of signature. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specifies metadata value type. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifies metadata object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifies width of signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone_1)() | Clone Metadata Signature instance. |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone)(object) | Clone Slides Metadata Signature instance with given value. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Overwrites Equals method to compare signature properties |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtain object from Metadata Signature Value over deserialization. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtain object from Metadata Signature Text over deserialization. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Overrides GetHashCode method |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converts to boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Converts to DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Converts to DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Converts to Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Converts to Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Converts to Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Converts to Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converts to integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Converts to float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Converts to float. |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring)() | Converts to String with override ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converts to String with specified format |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converts to String with specified format |

### See Also

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
