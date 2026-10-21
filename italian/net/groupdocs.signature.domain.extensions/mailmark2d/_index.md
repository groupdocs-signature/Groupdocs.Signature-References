---
title: "Mailmark2D"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Classe per codificare e decodificare il testo incorporato nel Royal Mail 2D Mailmark."
type: docs
weight: 400
url: /it/net/groupdocs.signature.domain.extensions/mailmark2d/
---
## Mailmark2D class

Classe per codificare e decodificare il testo incorporato nel Royal Mail 2D Mailmark.

```csharp
public class Mailmark2D : ICloneable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Mailmark2D](mailmark2d)() | Crea i dati combinati Royal Mail Mailmark con i valori predefiniti dei dati primari e secondari. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Class](../../groupdocs.signature.domain.extensions/mailmark2d/class) { get; set; } | Identifica la classe dell'elemento. |
| [CustomerContent](../../groupdocs.signature.domain.extensions/mailmark2d/customercontent) { get; set; } | Spazio opzionale per l'uso del cliente. |
| [CustomerContentEncodeMode](../../groupdocs.signature.domain.extensions/mailmark2d/customercontentencodemode) { get; set; } | Modalità di codifica del codice a barre DataMatrix. Valore predefinito: DataMatrixEncodeMode.C40. [`DataMatrixEncodeMode`](../datamatrixencodemode) |
| [DataMatrixType](../../groupdocs.signature.domain.extensions/mailmark2d/datamatrixtype) { get; set; } | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [DestinationPostCodeAndDPS](../../groupdocs.signature.domain.extensions/mailmark2d/destinationpostcodeanddps) { get; set; } | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri: Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido. La lunghezza massima è 9. |
| [InformationTypeID](../../groupdocs.signature.domain.extensions/mailmark2d/informationtypeid) { get; set; } | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [ItemID](../../groupdocs.signature.domain.extensions/mailmark2d/itemid) { get; set; } | Identifica l'elemento unico all'interno del Supply Chain ID. Ogni codice a barre Mailmark deve contenere un ID in modo da poter essere identificato univocamente per almeno 90 giorni. Valore massimo: 99999999. |
| [ReturnToSenderPostCode](../../groupdocs.signature.domain.extensions/mailmark2d/returntosenderpostcode) { get; set; } | Contiene il codice postale di ritorno al mittente ma senza DPS. Il PC (senza DPS) deve rispettare un formato PAF®. |
| [RTSFlag](../../groupdocs.signature.domain.extensions/mailmark2d/rtsflag) { get; set; } | Flag che indica quale livello di servizio di ritorno al mittente è richiesto. Lunghezza massima è 1. |
| [SupplyChainID](../../groupdocs.signature.domain.extensions/mailmark2d/supplychainid) { get; set; } | Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999. |
| [UPUCountryID](../../groupdocs.signature.domain.extensions/mailmark2d/upucountryid) { get; set; } | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [VersionID](../../groupdocs.signature.domain.extensions/mailmark2d/versionid) { get; } | Identifica la versione del codice a barre in base a ciascun Information Type ID. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.signature.domain.extensions/mailmark2d/clone)() | Ottiene una copia di questo oggetto. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
