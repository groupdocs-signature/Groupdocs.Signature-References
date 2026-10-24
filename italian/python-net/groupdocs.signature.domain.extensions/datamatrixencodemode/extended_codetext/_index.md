---
title: "campo EXTENDED_CODETEXT"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica in code-text."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica nel code-text. Formato: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text". Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Esempio di code-text esteso: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" Tutti i backslash (\\) devono essere raddoppiati nel testo.

### Valore
`12`

### Vedi anche
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
