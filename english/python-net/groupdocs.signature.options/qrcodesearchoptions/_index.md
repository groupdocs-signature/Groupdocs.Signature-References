---
title: QrCodeSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 350
---

## QrCodeSearchOptions class

Represents search options for QR-Code signatures.



**Inheritance:** [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The QrCodeSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#) | Initializes a new instance of the QRCodeSearchOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#groupdocs.signature.domain.QrCodeType) | Initializes a new instance of the QRCodeSearchOptions class with encode type value. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#groupdocs.signature.domain.QrCodeType-System.String) | Initializes a new instance of the QRCodeSearchOptions class with encode type and text values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type) | Specifies Encode Type property to search QR-Codes.<br/>If this value is not set, search is processed for all supported QR-Code Types. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text) | Specifies QR-Code Signature Text if it should be searched and matched. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type) | Gets or sets QR-Code Text Match Type search. It is used only when Text property is set. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content) | Gets or sets flag to grab QR-Code image content of signature on document page.<br/>If this flag is set true, QR-Code signature image content will keep raw image data by required format [`QrCodeSearchOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions#return_content_type).<br/>By default this option is disabled. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled.<br/>By default it set to Null. That means to return QR-Code image content in original format. <br/>This image format is specified at [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature#format)<br/>Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. <br/>If provided format is not supported than QR-Code image content in original .png will be returned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
