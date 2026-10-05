---
title: EXTENDED_CODETEXT field
second_title: GroupDocs.Signature for Python via .NET API References
description: "ExtendedCodetext mode allows to manually switch encoding schemes in code-text."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

ExtendedCodetext mode allows to manually switch encoding schemes in code-text. Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encoding schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Extended code-text example: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" All backslashes (\) must be doubled in text.

### Value
`12`

### See Also
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
