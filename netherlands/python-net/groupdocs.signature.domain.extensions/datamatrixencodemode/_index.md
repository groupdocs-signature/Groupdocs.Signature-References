---
title: "DataMatrixEncodeMode klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "DataMatrixEncodeMode enum — GroupDocs.Signature voor Python via .NET API-referentie."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Het DataMatrixEncodeMode-type geeft de volgende leden weer:

### Velden
| Veld | Beschrijving |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Selecteer automatisch de beste coderingsmodus voor DataMatrix-codering |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Codeert één alfanumeriek of twee numerieke tekens per byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Encodeer 8-bit waarden |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Encodeer met de codering gespecificeerd in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Gebruikt C40-codering. Encodeert hoofdletter alfanumeriek, kleine letters en speciale tekens |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Gebruikt Tekst-codering. Encodeert kleine letters alfanumeriek, hoofdletters en speciale tekens. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, encodeert cijfers, hoofdletters en veel interpunctietekens, maar ondersteunt geen kleine letters. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Gebruikt ANSI X12-codering. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext-modus staat toe om handmatig coderingsschema's te schakelen in code-tekst. Formaat : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Toegestane coderingsschema's zijn: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Voorbeeld van uitgebreide code-tekst: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Alle backslashes (\) moeten in de tekst worden verdubbeld. |

### Zie ook
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
