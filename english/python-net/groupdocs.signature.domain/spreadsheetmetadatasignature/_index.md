---
title: SpreadsheetMetadataSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/
is_root: false
weight: 430
---

## SpreadsheetMetadataSignature class

Contains Spreadsheet Metadata Signature properties.



**Inheritance:** [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature) → 
[`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The SpreadsheetMetadataSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/#System.String) | Creates Spreadsheet Metadata Signature with predefined name and empty value. |
| [__init__](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/#System.String-System.Object) | Creates Spreadsheet Metadata Signature with predefined values. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/name) | Specifies unique metadata name. |
| [value](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/value) | Specifies metadata object. |
| [type](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/type) | Specifies metadata value type. |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode signature Value properties. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/clone/#) | Clone Metadata Signature instance. |
| [clone](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/clone/#System.Object) | Clone Spreadsheet Metadata Signature instance with given value. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_boolean/#) | Converts to boolean. |
| [to_integer](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_integer/#) | Converts to integer. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_decimal/#) | Converts to Decimal. |
| [to_double](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_double/#) | Converts to Double. |
| [to_single](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_single/#) | Converts to float. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_date_time/#) | Converts to DateTime. |
| [to_string](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/#System.String) | Converts to String with specified format |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature)
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature)
