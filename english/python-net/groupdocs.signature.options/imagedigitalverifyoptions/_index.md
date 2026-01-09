---
title: ImageDigitalVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 180
---

## ImageDigitalVerifyOptions class

Keeps options to verify digital signatures in raster images.



**Inheritance:** [`ImageDigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions) → 
[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)



The ImageDigitalVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/#) | Initializes a new instance of the ImageDigitalVerifyOptions class for verifying digital (steganography) signatures in raster images. |


### Properties
| Property | Description |
| :- | :- |
| [is_valid](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/is_valid) | Valid property flag. |
| [page_number](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/page_number) | Document Page Number to be verified. If property is not set - all Pages of <br/>Document will be verified for first occurrence.<br/>Minimal value is 1. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/pages_setup) | Page Options to specify pages to be verified. |
| [all_pages](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/all_pages) | Flag to verify each document page. By default value is true. |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/shape_position) | Specifies shape position in the document layout. For verifing signatures in headers/footers |
| [extensions](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/extensions) | Additional extensions for alternative signature options verification. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password) | Password that was used to embed the signature. |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent) | Detection threshold percentage for partial extraction (0-100). Default is 75. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction) | When true, performs full data extraction (AnalyzePercentageDigitalSignature) for maximum accuracy. |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability) | Stores the probability returned by AnalyzePercentageDigitalSignature (0-100). |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`ImageDigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions)
* class [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)
