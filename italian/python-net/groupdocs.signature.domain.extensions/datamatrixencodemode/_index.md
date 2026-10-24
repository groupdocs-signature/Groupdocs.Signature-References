---
title: "classe DataMatrixEncodeMode"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "enum DataMatrixEncodeMode — GroupDocs.Signature per Python tramite riferimento API .NET."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Il tipo DataMatrixEncodeMode espone i seguenti membri:

### Campi
| Campo | Descrizione |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Seleziona automaticamente la modalità di codifica migliore per la codifica DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Codifica un carattere alfanumerico o due caratteri numerici per byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Codifica valori a 8 bit |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Codifica con la codifica specificata in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Utilizza la codifica C40. Codifica alfanumerici maiuscoli, minuscoli e caratteri speciali |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Utilizza la codifica Text. Codifica alfanumerici minuscoli, maiuscoli e caratteri speciali. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Utilizza la codifica EDIFACT. Usa sei bit per carattere, codifica cifre, lettere maiuscole e molti segni di punteggiatura, ma non supporta le lettere minuscole. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Utilizza la codifica ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica nel code-text. Formato: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text". Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Esempio di code-text esteso: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" Tutti i backslash (\\) devono essere raddoppiati nel testo. |

### Vedi anche
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
