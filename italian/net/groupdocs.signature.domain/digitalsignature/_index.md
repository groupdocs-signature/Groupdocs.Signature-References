---
title: "DigitalSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma digitale."
type: docs
weight: 150
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
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inizializza la firma digitale con SignatureId noto. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Crea la firma digitale con il certificato specificato. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Crea la firma digitale basata sullo store X509 specificato. Verrà utilizzato il primo certificato dallo store specificato. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Crea la firma digitale basata sullo Store X509 specificato e sull'indice del certificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ottiene o imposta il certificato X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Specifica il nome personalizzato dello store del certificato. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifica la posizione dello store del certificato. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifica il nome dello store del certificato. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ottiene o imposta il commento dello scopo della firma. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Restituisce true se questa firma digitale è valida e il documento non è stato manomesso. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ottiene o imposta l'ora in cui il documento è stato firmato. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ottiene l'impronta digitale di un certificato. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES [`XAdESType`](./xadestype). Il valore predefinito è None (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clona l'istanza della firma Barcode. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Sovrascrive il metodo GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Carica le firme digitali da tutti gli store di certificati X509 di sistema. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Carica le firme digitali da un archivio di certificati. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Carica le firme digitali da un archivio di certificati. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Carica le firme digitali da un archivio di certificati digitali posizionato in una posizione specifica. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Carica le firme digitali da un archivio di certificati digitali posizionato in una posizione specifica. |

### Vedi anche

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
