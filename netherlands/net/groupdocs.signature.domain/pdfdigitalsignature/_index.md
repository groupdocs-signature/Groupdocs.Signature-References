---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Bevat PDF‑digitale handtekening‑eigenschappen."
type: docs
weight: 840
url: /nl/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Bevat PDF‑digitale handtekening‑eigenschappen.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialiseer Pdf Digital Signature zonder certificaat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Maak een Pdf Digital signature met het opgegeven certificaat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialiseer Pdf Digital Signature op basis van de opgegeven X509-winkel. Het eerste certificaat uit de opgegeven winkel wordt gebruikt. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Maak een Pdf Digital signature op basis van de opgegeven X509-winkel en index van het certificaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Haalt of stelt het X509-certificaat in. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Specificeert de aangepaste winkelnaam van het certificaat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specificeert de locatie van de winkel van het certificaat. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specificeert de winkelnaam van het certificaat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Haalt of stelt de ondertekeningsdoelcommentaar in. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen de ondertekenaar te contacteren om de handtekening te verifiëren, bijv. een telefoonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Haal op of stel de creatiedatum van de handtekening in. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Haal de vlag op die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logrecords van documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert de hoogte van de handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Haal op of stel de vlag in om aan te geven of dit component een handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Blijft waar (true) als deze digitale handtekening geldig is en het document niet is gemanipuleerd. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert de linkse positie van de handtekening. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | De hostnaam van de CPU of fysieke locatie van de ondertekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Haal op of stel de wijzigingsdatum van de handtekening in. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specificeert de pagina waarop de handtekening is gevonden. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | De reden voor de ondertekening, zoals (Ik ga akkoord…). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Forceer het tonen/verbergen van handtekeningeigenschappen. Als ShowProperties waar is, heeft het handtekeningsveld een vooraf gedefinieerd weergaveformaat Digitaal ondertekend door {[`ContactInfo`](./contactinfo)} Datum: {Date} Reden: {[`Reason`](./reason)} Locatie: {[`Location`](./location)} ShowProperties is standaard waar. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Haalt of stelt de tijd in waarop het document is ondertekend. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Haalt de vingerafdruk van een certificaat op. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Tijdstempel voor Pdf digitale handtekening. Standaardwaarde is null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specificeert de bovenste positie van de handtekening. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Type van Pdf digitale handtekening. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert de breedte van de handtekening. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-type [`XAdESType`](../digitalsignature/xadestype). Standaardwaarde is None (XAdES is uitgeschakeld). Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Kloon Barcode Signature‑instantie. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Overschrijft de Equals‑methode om handtekeningeigenschappen te vergelijken |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Overschrijft de GetHashCode‑methode |

### Zie ook

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
