---
title: "EPC"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta il Quick Response Code del European Payments Council."
type: docs
weight: 250
url: /it/net/groupdocs.signature.domain.extensions/epc/
---
## EPC class

Rappresenta il Quick Response Code del European Payments Council.

```csharp
public sealed class EPC
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EPC](epc)() | Istanzia un nuovo oggetto EPC. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Amount](../../groupdocs.signature.domain.extensions/epc/amount) { get; set; } | Ottiene o imposta l'importo. |
| [BIC](../../groupdocs.signature.domain.extensions/epc/bic) { get; set; } | Ottiene o imposta il BIC del beneficiario con una lunghezza massima di 11 caratteri. |
| [Charset](../../groupdocs.signature.domain.extensions/epc/charset) { get; } | Implementazione del set di caratteri EPC / SEPA QR-Code. Per impostazione predefinita questo valore è 1 |
| [Code](../../groupdocs.signature.domain.extensions/epc/code) { get; set; } | Ottiene o imposta il Codice Azienda fino a 4 caratteri. |
| [IBAN](../../groupdocs.signature.domain.extensions/epc/iban) { get; set; } | Ottiene o imposta il conto del beneficiario (IBAN). L'IBAN è composto da un massimo di 34 caratteri alfanumerici. |
| [Identification](../../groupdocs.signature.domain.extensions/epc/identification) { get; } | Identificazione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è SCT |
| [Information](../../groupdocs.signature.domain.extensions/epc/information) { get; set; } | Ottiene o imposta le informazioni di suggerimento. Massimo 70 caratteri. |
| [Name](../../groupdocs.signature.domain.extensions/epc/name) { get; set; } | Ottiene o imposta il nome del beneficiario. La lunghezza massima è 70 caratteri. |
| [Reference](../../groupdocs.signature.domain.extensions/epc/reference) { get; set; } | Ottiene o imposta il riferimento di pagamento (massimo 35 caratteri). Questo campo e il campo Informazioni di rimessa sono mutualmente esclusivi. |
| [Remittance](../../groupdocs.signature.domain.extensions/epc/remittance) { get; set; } | Ottiene o imposta le informazioni di rimessa (massimo 140 caratteri). Questo campo e il campo Riferimento di pagamento sono mutualmente esclusivi. |
| [Version](../../groupdocs.signature.domain.extensions/epc/version) { get; } | Implementazione della versione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è 002. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.signature.domain.extensions/epc/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà EPC |
| override [GetHashCode](../../groupdocs.signature.domain.extensions/epc/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
