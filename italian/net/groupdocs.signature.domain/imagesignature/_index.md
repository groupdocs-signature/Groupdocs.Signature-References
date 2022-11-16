---
title: ImageSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene le proprietà della firma dellimmagine.
type: docs
weight: 570
url: /it/net/groupdocs.signature.domain/imagesignature/
---
## ImageSignature class

Contiene le proprietà della firma dell'immagine.

```csharp
public class ImageSignature : BaseSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSignature](imagesignature)(string) | Inizializza l'oggetto ImageSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore univoco viene utilizzato per trovare proprietà aggiuntive per questa firma dal livello delle informazioni sulla firma del documento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Content](../../groupdocs.signature.domain/imagesignature/content) { get; } | Specifica il contenuto dei dati binari dell'immagine di tipo[`Format`](./format) . Per impostazione predefinita, questa proprietà non verrà impostata. Usa proprietà[`ReturnContent`](../../groupdocs.signature.options/imagesearchoptions/returncontent) per abilitare questa funzione. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro cronologico del documento per conservare l'elenco delle firme eliminate. |
| [Format](../../groupdocs.signature.domain/imagesignature/format) { get; } | Specifica il formato dell'immagine della firma. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della segnatura. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la firma della pagina in cui è stata trovata. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore di firma univoco per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata al metodo Sign o Search. Se questa proprietà è stata salvata prima, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Size](../../groupdocs.signature.domain/imagesignature/size) { get; } | Specifica la dimensione in byte dell'immagine della firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagesignature/clone)() | Clona istanza firma codice a barre. |
| override [Equals](../../groupdocs.signature.domain/imagesignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/imagesignature/gethashcode)() | Sostituisce il metodo GetHashCode |

### Guarda anche

* class [BaseSignature](../basesignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->