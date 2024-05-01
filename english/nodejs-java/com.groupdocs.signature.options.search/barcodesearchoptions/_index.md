---
title: BarcodeSearchOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents abstract search Options for Barcode signatures.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Represents abstract search Options for Barcode signatures.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Initializes a new instance of the SearchBarcodeOptions class with default values. |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initializes a new instance of the SearchBarcodeOptions class with encode type value. |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Initializes a new instance of the SearchBarcodeOptions class with encode type and text values. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifies Encode Type property to search Barcodes. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Specifies Encode Type property to search Barcodes. |
| [getText()](#getText--) | Specifies Barcode Signature text if it should be searched and matched. |
| [setText(String value)](#setText-java.lang.String-) | Specifies Barcode Signature text if it should be searched and matched. |
| [getMatchType()](#getMatchType--) | Gets or sets Barcode text Match Type search. |
| [setMatchType(int value)](#setMatchType-int-) | Gets or sets Barcode text Match Type search. |
| [getReturnContent()](#getReturnContent--) | Gets or sets flag to grab Barcode image content of signature on document page. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Gets or sets flag to grab Barcode image content of signature on document page. |
| [getReturnContentType()](#getReturnContentType--) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Initializes a new instance of the SearchBarcodeOptions class with default values.

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Initializes a new instance of the SearchBarcodeOptions class with encode type value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specifies Barcode encode type. |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Initializes a new instance of the SearchBarcodeOptions class with encode type and text values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specifies Barcode encode type. |
| text | java.lang.String | Set Text of Barcode signature. |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specifies Encode Type property to search Barcodes. If this value is not set, search is processed for all supported Barcode Types

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Specifies Encode Type property to search Barcodes. If this value is not set, search is processed for all supported Barcode Types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specifies Barcode Signature text if it should be searched and matched.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifies Barcode Signature text if it should be searched and matched.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Gets or sets Barcode text Match Type search. It is used only when Text property is set.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Gets or sets Barcode text Match Type search. It is used only when Text property is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Gets or sets flag to grab Barcode image content of signature on document page. If this flag is set true, Barcode signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Gets or sets flag to grab Barcode image content of signature on document page. If this flag is set true, Barcode signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at  BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at  BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

