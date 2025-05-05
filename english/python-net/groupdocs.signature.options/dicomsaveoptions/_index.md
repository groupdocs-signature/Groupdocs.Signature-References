---
title: DicomSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/dicomsaveoptions/
is_root: false
weight: 70
---

## DicomSaveOptions class

Save options for DICOM image documents.



**Inheritance:** [`DicomSaveOptions`](/signature/python-net/groupdocs.signature.options/dicomsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The DicomSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/__init__/#) | Creates DicomSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/file_format) | Gets or sets file format of signed document. |
| [xmp_entries](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/xmp_entries) | XMP data for DICOM. Use it for setting image metadata. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`DicomSaveOptions`](/signature/python-net/groupdocs.signature.options/dicomsaveoptions)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
