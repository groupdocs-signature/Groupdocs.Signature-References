---
title: ImageSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 200
---

## ImageSearchOptions class

Represents search options for Image signatures.



**Inheritance:** [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The ImageSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/#) | Initializes a new instance of the ImageSearchOptions class with default values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/imagesearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/imagesearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/imagesearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/imagesearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content) | Gets or sets flag to grab image content of signature on document page.<br/>If this flag is set true, image signature content will keep raw image data by required format [`ImageSearchOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/imagesearchoptions#return_content_type).<br/>By default this option is disabled. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size) | For non zero value this flag specifies minimal size of images for search criteria.<br/>By default this flag is set to zero and does not affect search result. |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size) | For non zero value this flag specifies maximum size of images for search criteria.<br/>By default this flag is set to zero and does not affect search result. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type) | Specifies file type of returned content of the image signature when ReturnContent property is enabled.<br/>By default it set to Null. That means to return image content in original format. <br/>This image format is specified at [`ImageSignature.format`](/signature/python-net/groupdocs.signature.domain/imagesignature#format)<br/>Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. <br/>If provided format is not supported than image content in original format will be returned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
