---
title: "TextSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma di testo."
type: docs
weight: 1190
url: /it/net/groupdocs.signature.domain/textsignature/
---
## TextSignature class

Contiene le proprietà della firma di testo.

```csharp
public class TextSignature : BaseSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSignature](textsignature)(string) | Inizializza l'oggetto TextSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore unico è usato per trovare proprietà aggiuntive per questa firma dal livello di informazioni sulla firma del documento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [Native](../../groupdocs.signature.domain/textsignature/native) { get; set; } | Specifica l'attributo nativo. È vero se la firma è specifica del documento. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureImplementation](../../groupdocs.signature.domain/textsignature/signatureimplementation) { get; } | Specifica l'implementazione della firma di testo. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Text](../../groupdocs.signature.domain/textsignature/text) { get; set; } | Specifica il testo nella firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/textsignature/clone)() | Clona l'istanza di Text Signature. |
| override [Equals](../../groupdocs.signature.domain/textsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/textsignature/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Vedi anche

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
