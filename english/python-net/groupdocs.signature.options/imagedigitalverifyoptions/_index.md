---
title: ImageDigitalVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Keeps options to verify digital signatures in raster images."
type: docs
url: /python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Keeps options to verify digital signatures in raster images.

The ImageDigitalVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Initializes a new instance of the ImageDigitalVerifyOptions class for verifying digital (steganography) signatures in raster images. |

### Properties
| Property | Description |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | The probability returned by AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | The detection threshold percentage for partial extraction (0-100). Default is 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | The password that was used to embed the signature. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | The property determines whether full data extraction (AnalyzePercentageDigitalSignature) is performed for maximum accuracy. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | The flag indicating whether each document page should be verified. By default the value is True. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | The additional extensions for alternative signature options verification. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | The valid property flag. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | The document page number to be verified; if not set, all pages of the document are verified for the first occurrence (minimum value is 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | The page options to specify pages to be verified. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | The shape position in the document layout used for verifying signatures in headers/footers. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
