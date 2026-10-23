---
title: "EXTENDED_CODETEXT Feld"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata im Code‑Text."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata im Code‑Text. Format : \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Erlaubte Kodierungsschemata sind: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Beispiel für erweiterten Code‑Text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" Alle Rückwärtsschrägstriche (\\) müssen im Text verdoppelt werden.

### Wert
`12`

### Siehe auch
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
