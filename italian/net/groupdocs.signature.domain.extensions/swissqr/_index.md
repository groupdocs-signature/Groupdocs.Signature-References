---
title: "SwissQR"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Classe per la codifica e decodifica del testo incorporato nel codice SwissQR."
type: docs
weight: 520
url: /it/net/groupdocs.signature.domain.extensions/swissqr/
---
## SwissQR class

Classe per la codifica e decodifica del testo incorporato nel codice SwissQR.

```csharp
public class SwissQR
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SwissQR](swissqr)() | Crea un'istanza di SwissQR. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Account](../../groupdocs.signature.domain.extensions/swissqr/account) { get; set; } | Ottiene o imposta il numero di conto del creditore. I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Gli spazi sono consentiti nel numero di conto. |
| [Amount](../../groupdocs.signature.domain.extensions/swissqr/amount) { get; set; } | Ottiene o imposta l'importo del pagamento. I valori validi sono compresi tra 0.01 e 999,999,999.99. |
| [BillInformation](../../groupdocs.signature.domain.extensions/swissqr/billinformation) { get; set; } | Ottiene o imposta le informazioni aggiuntive strutturate della fattura. |
| [Creditor](../../groupdocs.signature.domain.extensions/swissqr/creditor) { get; set; } | Ottiene o imposta l'indirizzo del creditore. |
| [Currency](../../groupdocs.signature.domain.extensions/swissqr/currency) { get; set; } | Ottiene o imposta la valuta del pagamento. I valori validi sono "CHF" e "EUR". |
| [Debtor](../../groupdocs.signature.domain.extensions/swissqr/debtor) { get; set; } | Ottiene o imposta l'indirizzo del debitore. Il debitore è opzionale. Se omesso, è accettabile sia impostare questo campo a null sia impostare un indirizzo con tutti i valori null o vuoti. |
| [Reference](../../groupdocs.signature.domain.extensions/swissqr/reference) { get; set; } | Ottiene o imposta il riferimento di pagamento del creditore. Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx. Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 ("RFxxxx"). Entrambi possono contenere spazi per la formattazione. |
| [UnstructuredMessage](../../groupdocs.signature.domain.extensions/swissqr/unstructuredmessage) { get; set; } | Ottiene o imposta il messaggio aggiuntivo non strutturato. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
