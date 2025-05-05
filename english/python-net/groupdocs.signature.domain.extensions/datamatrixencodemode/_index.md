---
title: DataMatrixEncodeMode enumeration
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 360
---

## DataMatrixEncodeMode enumeration

DataMatrix encoder's encoding mode, default to Auto



The DataMatrixEncodeMode type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| AUTO | Automatically pick up the best encode mode for DataMatrix encoding |
| ASCII | Encodes one alphanumeric or two numeric characters per byte |
| FULL | Encode 8 bit values |
| CUSTOM | Encode with the encoding specified in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| TEXT | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters. |
| EDIFACT | Uses EDIFACT encoding. Uses six bits per character, encodes digits, <br/>upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| ANSIX12 | Uses ANSI X12 encoding. |
| EXTENDED_CODETEXT | ExtendedCodetext mode allows to manually switch encoding schemes in code-text.<br/>Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text".<br/>Allowed encoding schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.<br/>Extended code-text example: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\<br/>doubled\edifact:EdifactEncodedText"<br/>All backslashes (\) must be doubled in text. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
