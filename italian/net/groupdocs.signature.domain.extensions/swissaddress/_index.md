---
title: "SwissAddress"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta l'indirizzo del creditore o del debitore. È possibile impostare il tipo di indirizzo strutturato (via, numero civico, codice postale e città) oppure il tipo di elementi di indirizzo combinati (riga indirizzo 1 e 2)."
type: docs
weight: 510
url: /it/net/groupdocs.signature.domain.extensions/swissaddress/
---
## SwissAddress class

Rappresenta l'indirizzo del creditore o del debitore. È possibile impostare la via, il numero civico, il codice postale e la città (tipo di indirizzo strutturato) oppure la linea indirizzo 1 e 2 (tipo di elementi di indirizzo combinati).

```csharp
public class SwissAddress
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SwissAddress](swissaddress)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddressLine1](../../groupdocs.signature.domain.extensions/swissaddress/addressline1) { get; set; } | Ottiene o imposta la riga indirizzo 1. La riga indirizzo 1 contiene il nome della via, il numero civico o la casella postale. Questo campo è utilizzato solo per gli indirizzi a elementi combinati ed è opzionale. |
| [AddressLine2](../../groupdocs.signature.domain.extensions/swissaddress/addressline2) { get; set; } | Ottiene o imposta la riga indirizzo 2. La riga indirizzo 2 contiene il codice postale e la città. Questo campo è utilizzato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio. |
| [CountryCode](../../groupdocs.signature.domain.extensions/swissaddress/countrycode) { get; set; } | Ottiene o imposta il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo non contenga valori nulli o vuoti. |
| [HouseNo](../../groupdocs.signature.domain.extensions/swissaddress/houseno) { get; set; } | Ottiene o imposta il numero civico. Questo campo è utilizzato solo per gli indirizzi strutturati ed è opzionale. |
| [Name](../../groupdocs.signature.domain.extensions/swissaddress/name) { get; set; } | Ottiene o imposta il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica. |
| [PostalCode](../../groupdocs.signature.domain.extensions/swissaddress/postalcode) { get; set; } | Ottiene o imposta il codice postale. Questo campo è utilizzato solo per gli indirizzi strutturati. Per questo tipo, è obbligatorio. |
| [Street](../../groupdocs.signature.domain.extensions/swissaddress/street) { get; set; } | Ottiene o imposta la via. La via deve essere specificata senza numero civico. Questo campo è utilizzato solo per gli indirizzi strutturati ed è opzionale. |
| [Town](../../groupdocs.signature.domain.extensions/swissaddress/town) { get; set; } | Ottiene o imposta la città o il comune. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
