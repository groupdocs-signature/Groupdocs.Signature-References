---
title: DigitalSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene le proprietà della firma digitale.
type: docs
weight: 140
url: /it/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Contiene le proprietà della firma digitale.

```csharp
public class DigitalSignature : BaseSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Inizializza la firma digitale con i parametri predefiniti. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inizializza firma digitale con SignatureId noto. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Crea firma digitale con certificato specificato. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Crea firma digitale basata sull'archivio X509 specificato. Verrà utilizzato il primo certificato dell'archivio specificato. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Crea una firma digitale basata sull'archivio X509 specificato e sull'indice del certificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ottiene o imposta il certificato X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifica il percorso di archiviazione del certificato |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifica il nome dell'archivio del certificato. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ottiene o imposta il commento sullo scopo della firma. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro cronologico del documento per conservare l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della segnatura. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Mantiene vero se questa firma digitale è valida e il documento non è stato manomesso. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la firma della pagina in cui è stata trovata. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore di firma univoco per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata al metodo Sign o Search. Se questa proprietà è stata salvata prima, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ottiene o imposta l'ora in cui il documento è stato firmato. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ottiene l'identificazione personale di un certificato. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES[`XAdESType`](./xadestype) . Il valore predefinito è Nessuno (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clona istanza firma codice a barre. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Sostituisce il metodo GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Carica la firma digitale da tutti gli archivi di certificati X509 del sistema. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Carica la firma digitale dall'archivio dei certificati X509 passati. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Carica la firma digitale dall'archivio dei certificati X509 passati. |

### Guarda anche

* class [BaseSignature](../basesignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
