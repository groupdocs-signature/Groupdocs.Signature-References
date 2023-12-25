---
title: PreviewSignatureOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents signature preview options.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Represents signature preview options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Initializes PreviewSignatureOptions object. |
## Methods

| Method | Description |
| --- | --- |
| [getSignatureId()](#getSignatureId--) | Unique value to distinct the signature. |
| [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Unique value to distinct the signature. |
| [getSignOptions()](#getSignOptions--) | Signature Options for generate preview. |
| [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Signature Options for generate preview. |
| [getPreviewFormat()](#getPreviewFormat--) | Gets or sets preview images format. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Gets or sets preview images format. |
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Initializes PreviewSignatureOptions object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | The signature options to generate preview for. |
| pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Interface which defines method to create output page preview stream. |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unique value to distinct the signature. Use SignatureId to identify the preview options.

**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Unique value to distinct the signature. Use SignatureId to identify the preview options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Signature Options for generate preview.

**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Signature Options for generate preview.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Gets or sets preview images format. Default value is PNG

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Gets or sets preview images format. Default value is PNG

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

