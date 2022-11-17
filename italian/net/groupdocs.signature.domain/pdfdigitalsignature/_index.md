---
title: PdfDigitalSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene Pdf Proprietà firma digitale.
type: docs
weight: 630
url: /it/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contiene Pdf Proprietà firma digitale.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inizializza firma digitale Pdf senza certificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Crea Pdf Firma digitale con certificato specificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inizializza la firma digitale Pdf in base all'archivio X509 specificato. Verrà utilizzato il primo certificato dell'archivio specificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Crea Pdf Firma digitale basata sull'archivio X509 specificato e sull'indice del certificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ottiene o imposta il certificato X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifica il percorso di archiviazione del certificato |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifica il nome dell'archivio del certificato. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ottiene o imposta il commento sullo scopo della firma. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro cronologico del documento per conservare l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della segnatura. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Mantiene vero se questa firma digitale è valida e il documento non è stato manomesso. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Il nome host della CPU o la posizione fisica della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la firma della pagina in cui è stata trovata. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Il motivo della firma, ad esempio (AccettoРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Forza a mostrare/nascondere le proprietà della firma. Nel caso in cui ShowProperties sia true signature il campo ha un formato di aspetto predefinito Firmato digitalmente da {[`ContactInfo`](./contactinfo)} Data: {Data} Motivo: {[`Reason`](./reason)} Località: {[`Location`](./location) } ShowProperties è true per impostazione predefinita. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore di firma univoco per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata al metodo Sign o Search. Se questa proprietà è stata salvata prima, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ottiene o imposta l'ora in cui il documento è stato firmato. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ottiene l'identificazione personale di un certificato. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Marca temporale per firma digitale Pdf. Il valore predefinito è null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Tipo di firma digitale Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES[`XAdESType`](../digitalsignature/xadestype) . Il valore predefinito è Nessuno (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clona istanza firma codice a barre. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Sostituisce il metodo GetHashCode |

### Guarda anche

* class [DigitalSignature](../digitalsignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
