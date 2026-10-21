---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "La modalità di codifica degli encoder DataMatrix è impostata di default su Auto"
type: docs
weight: 230
url: /it/net/groupdocs.signature.domain.extensions/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Modalità di codifica dell'encoder DataMatrix, predefinita su Auto

```csharp
public enum DataMatrixEncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Seleziona automaticamente la migliore modalità di codifica per la codifica DataMatrix |
| ASCII | `1` | Codifica un carattere alfanumerico o due caratteri numerici per byte |
| Full | `6` | Codifica valori a 8 bit |
| Custom | `7` | Codifica con la codifica specificata in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Utilizza la codifica C40. Codifica caratteri alfanumerici maiuscoli, minuscoli e caratteri speciali |
| Text | `9` | Utilizza la codifica Text. Codifica caratteri alfanumerici minuscoli, maiuscoli e caratteri speciali. |
| EDIFACT | `10` | Utilizza la codifica EDIFACT. Usa sei bit per carattere, codifica cifre, lettere maiuscole e molte punteggiature, ma non supporta le lettere minuscole. |
| ANSIX12 | `11` | Utilizza la codifica ANSI X12. |
| ExtendedCodetext | `12` | Modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica nel code-text. Formato: "\Encodation_scheme_name:text\Encodation_scheme_name:text". Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Esempio di code-text esteso: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Tutti i backslash (\) devono essere raddoppiati nel testo. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
