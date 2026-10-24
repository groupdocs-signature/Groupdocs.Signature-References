---
title: "DataMatrixEncodeMode-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "DataMatrixEncodeMode‑enum — GroupDocs.Signature för Python via .NET API‑referens."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

DataMatrixEncodeMode-typen visar följande medlemmar:

### Fält
| Fält | Beskrivning |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Välj automatiskt det bästa kodningsläget för DataMatrix‑kodning |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Kodar en alfanumerisk eller två numeriska tecken per byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Kodar 8‑bit‑värden |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Kodar med den kodning som anges i BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Använder C40-kodning. Kodar versala alfanumeriska tecken, gemener och specialtecken |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Använder Text-kodning. Kodar gemena alfanumeriska tecken, versaler och specialtecken. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Använder EDIFACT-kodning. Använder sex bitar per tecken, kodar siffror, versala bokstäver och många skiljetecken, men har inget stöd för gemena bokstäver. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Använder ANSI X12-kodning. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman i kod‑text. Format: \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Tillåtna kodningsscheman är: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Exempel på utökad kod‑text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" Alla bakåtsnedstreck (\\) måste dubblas i texten. |

### Se även
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
