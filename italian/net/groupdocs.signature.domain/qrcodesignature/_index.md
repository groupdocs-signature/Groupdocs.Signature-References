---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma QRcode."
type: docs
weight: 970
url: /it/net/groupdocs.signature.domain/qrcodesignature/
---
## QrCodeSignature class

Contiene le proprietà della firma del codice QR.

```csharp
public class QrCodeSignature : BaseSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QrCodeSignature](qrcodesignature)(string) | Inizializza l'oggetto QrCodeSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore unico è utilizzato per trovare proprietà aggiuntive per questa firma dal livello di informazioni sulla firma del documento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Content](../../groupdocs.signature.domain/qrcodesignature/content) { get; } | Specifica il contenuto dell'immagine dati binari QR-code di tipo [`Format`](./format). Per impostazione predefinita questa proprietà non sarà impostata. Usa la proprietà [`ReturnContent`](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) per abilitare questa funzionalità. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [EncodeType](../../groupdocs.signature.domain/qrcodesignature/encodetype) { get; } | Specifica il tipo di codifica QR-code. |
| [Format](../../groupdocs.signature.domain/qrcodesignature/format) { get; } | Specifica il formato dell'immagine della firma QR-code. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Text](../../groupdocs.signature.domain/qrcodesignature/text) { get; } | Specifica il testo del QR-code. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/qrcodesignature/clone)() | Clona l'istanza di QR-Code Signature. |
| override [Equals](../../groupdocs.signature.domain/qrcodesignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata)() | Ottieni l'oggetto dal testo della firma QR-Code durante la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata_1)(IDataEncryption) | Ottieni l'oggetto dal testo della firma QR-Code durante la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/qrcodesignature/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Vedi anche

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
