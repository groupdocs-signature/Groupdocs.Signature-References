---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma digitale PDF."
type: docs
weight: 840
url: /it/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contiene le proprietà della firma digitale PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inizializza la firma digitale PDF senza certificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Crea una firma digitale PDF con il certificato specificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inizializza la firma digitale PDF basata sullo store X509 specificato. Verrà utilizzato il primo certificato dallo store specificato. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Crea una firma digitale PDF basata sullo store X509 specificato e sull'indice del certificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ottiene o imposta il certificato X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Specifica il nome personalizzato dello store del certificato. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifica la posizione dello store del certificato. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifica il nome dello store del certificato. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ottiene o imposta il commento dello scopo della firma. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Restituisce true se questa firma digitale è valida e il documento non è stato manomesso. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Il nome host della CPU o la posizione fisica della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Il motivo della firma, ad esempio (I agree…). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Forza la visualizzazione/nascondi le proprietà della firma. Nel caso in cui ShowProperties è true, il campo firma ha un formato di aspetto predefinito Firmato digitalmente da {[`ContactInfo`](./contactinfo)} Data: {Date} Motivo: {[`Reason`](./reason)} Posizione: {[`Location`](./location)} ShowProperties è true per impostazione predefinita. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ottiene o imposta l'ora in cui il documento è stato firmato. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ottiene l'impronta digitale di un certificato. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Marca temporale per la firma digitale PDF. Il valore predefinito è null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Tipo di firma digitale PDF. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES [`XAdESType`](../digitalsignature/xadestype). Il valore predefinito è None (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clona l'istanza della firma Barcode. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Vedi anche

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
