---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Classe per memorizzare i dati secondari e aggiuntivi del HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 320
url: /it/net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/
---
## HIBCLICSecondaryAdditionalData class

Classe per memorizzare i dati secondari e aggiuntivi HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

```csharp
public class HIBCLICSecondaryAdditionalData : ICloneable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HIBCLICSecondaryAdditionalData](hibclicsecondaryadditionaldata)() | Costruttore predefinito ctor() |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DateOfManufacture](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/dateofmanufacture) { get; set; } | Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue |
| [ExpiryDate](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expirydate) { get; set; } | Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None. |
| [ExpiryDateFormat](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expirydateformat) { get; set; } | Identifica il formato della data di scadenza. |
| [LinkCharacter](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/linkcharacter) { get; set; } | Identifica il carattere di collegamento nella stringa di output. |
| [LotNumber](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/lotnumber) { get; set; } | Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [Quantity](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/quantity) { get; set; } | Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1 |
| [SerialNumber](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/serialnumber) { get; set; } | Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica fino a 18 simboli di lunghezza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/clone)() | Ottiene una copia di questo oggetto. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
