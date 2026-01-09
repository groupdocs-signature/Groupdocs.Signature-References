---
title: BarcodeSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---

## BarcodeSearchOptions class

Represents search options for Barcode signatures.



**Inheritance:** [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The BarcodeSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#) | Initializes a new instance of the BarcodeSearchOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#groupdocs.signature.domain.BarcodeType) | Initializes a new instance of the BarcodeSearchOptions class with encode type value. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#groupdocs.signature.domain.BarcodeType-System.String) | Initializes a new instance of the BarcodeSearchOptions class with encode type and text values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type) | Specifies Encode Type property to search Barcodes.<br/>If this value is not set, search is processed for all supported Barcode Types |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text) | Specifies Barcode Signature text if it should be searched and matched. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type) | Gets or sets Barcode text Match Type search. It is used only when Text property is set. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content) | Gets or sets flag to grab Barcode image content of signature on document page.<br/>If this flag is set true, Barcode signature image content will keep raw image data by required format [`BarcodeSearchOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions#return_content_type).<br/>By default this option is disabled. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled.<br/>By default it set to Null. That means to return Barcode image content in original format. <br/>This image format is specified at [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature#format)<br/>Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. <br/>If provided format is not supported than Barcode image content in .png format will be returned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
