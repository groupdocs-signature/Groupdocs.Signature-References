---
title: PageSignatureStreamFactory
second_title: GroupDocs.Signature for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.groupdocs.signature.options/pagesignaturestreamfactory/
---```
public interface PageSignatureStreamFactory
```
## Methods

| Method | Description |
| --- | --- |
| [createSignatureStream(PreviewSignatureOptions previewOptions)](#createSignatureStream-com.groupdocs.signature.options.PreviewSignatureOptions-) | Method to create output page preview stream. |
| [closeSignatureStream(PreviewSignatureOptions previewOptions, OutputStream pageStream)](#closeSignatureStream-com.groupdocs.signature.options.PreviewSignatureOptions-java.io.OutputStream-) | Method to release output page preview stream |
### createSignatureStream(PreviewSignatureOptions previewOptions) {#createSignatureStream-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public abstract OutputStream createSignatureStream(PreviewSignatureOptions previewOptions)
```


Method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |  |

**Returns:**
java.io.OutputStream
### closeSignatureStream(PreviewSignatureOptions previewOptions, OutputStream pageStream) {#closeSignatureStream-com.groupdocs.signature.options.PreviewSignatureOptions-java.io.OutputStream-}
```
public abstract void closeSignatureStream(PreviewSignatureOptions previewOptions, OutputStream pageStream)
```


Method to release output page preview stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |  |
| pageStream | java.io.OutputStream |  |

