---
title: DataMatrixEncodeMode class
second_title: GroupDocs.Signature for Python via .NET API References
description: "DataMatrixEncodeMode enum — GroupDocs.Signature for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

The DataMatrixEncodeMode type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Automatically pick up the best encode mode for DataMatrix encoding |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Encodes one alphanumeric or two numeric characters per byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Encode 8 bit values |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Encode with the encoding specified in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Uses ANSI X12 encoding. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext mode allows to manually switch encoding schemes in code-text. Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encoding schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Extended code-text example: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" All backslashes (\) must be doubled in text. |

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
