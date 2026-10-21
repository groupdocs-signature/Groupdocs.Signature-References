---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Risultato dell'elaborazione del processo di firma del documento di archivio per il documento con firme appena create."
type: docs
weight: 170
url: /it/net/groupdocs.signature.domain/documentresultsignature/
---
## DocumentResultSignature class

Risultato dell'elaborazione del processo di firma del documento di archivio per il documento con firme appena create.

```csharp
public class DocumentResultSignature : BaseSignature, IResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [DestinDocumentSize](../../groupdocs.signature.domain/documentresultsignature/destindocumentsize) { get; } | Restituisce la dimensione del documento di destinazione. |
| [ErrorMessage](../../groupdocs.signature.domain/documentresultsignature/errormessage) { get; } | se il documento è stato elaborato con errore questa proprietà conterrà il messaggio di errore |
| [Failed](../../groupdocs.signature.domain/documentresultsignature/failed) { get; } | Elenco delle firme che non sono riuscite durante il processo [`BaseSignature`](../basesignature). |
| [FileName](../../groupdocs.signature.domain/documentresultsignature/filename) { get; } | Nome file del documento |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [ProcessingTime](../../groupdocs.signature.domain/documentresultsignature/processingtime) { get; } | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [SourceDocumentSize](../../groupdocs.signature.domain/documentresultsignature/sourcedocumentsize) { get; } | Restituisce la dimensione del documento di origine. |
| [Succeeded](../../groupdocs.signature.domain/documentresultsignature/succeeded) { get; } | Elenco delle firme elaborate con successo [`BaseSignature`](../basesignature). |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [TotalSignatures](../../groupdocs.signature.domain/documentresultsignature/totalsignatures) { get; } | Restituisce il totale delle firme elaborate. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain/basesignature/clone)() | Clona l'istanza della firma. |
| override [Equals](../../groupdocs.signature.domain/basesignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/basesignature/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Osservazioni

**Learn more**

* More about signing documents withing archives using GroupDocs.Signature: [How to sign documents withing archives using C#](https://docs.groupdocs.com/signature/net/signing-archive-documents/)

### Vedi anche

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
