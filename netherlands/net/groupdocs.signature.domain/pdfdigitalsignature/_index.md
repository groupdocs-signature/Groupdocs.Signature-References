---
title: PdfDigitalSignature
second_title: GroupDocs.Signature voor .NET API-referentie
description: Bevat Pdf Digitale handtekening eigenschappen.
type: docs
weight: 660
url: /nl/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Bevat Pdf Digitale handtekening eigenschappen.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialiseer digitale pdf-handtekening zonder certificaat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Maak PDF digitale handtekening met opgegeven certificaat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialiseer digitale PDF-handtekening op basis van gespecificeerde X509-opslag. Het eerste certificaat van de opgegeven winkel wordt gebruikt. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Maak PDF digitale handtekening op basis van gespecificeerde X509 Store en index van certificaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Haalt of stelt het X509-certificaat in. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specificeert de opslaglocatie van het certificaat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specificeert de winkelnaam van het certificaat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Krijgt of stelt de opmerking over het ondertekeningsdoel in. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen contact op te nemen met de ondertekenaar om de handtekening te verifiëren, bijvoorbeeld een telefoonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | De aanmaakdatum van de handtekening ophalen of instellen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Verkrijg de vlag die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logboekrecords van de documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert hoogte van handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Vlag ophalen of instellen om aan te geven of dit onderdeel Handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met Update-methode om element in te stellen als handtekening (true) of documentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Blijft waar als deze digitale handtekening geldig is en er niet met het document is geknoeid. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert linkerpositie van handtekening. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | De CPU-hostnaam of fysieke locatie van de ondertekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | De wijzigingsdatum van de handtekening ophalen of instellen. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Geeft aan dat de paginahandtekening is gevonden op. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | De reden voor de ondertekening, zoals (Ik ga akkoordРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Geforceerd om handtekeningeigenschappen te tonen/verbergen. In het geval dat ShowProperties waar is, heeft het veld signature een vooraf gedefinieerd uiterlijkformaat Digitaal ondertekend door {[`ContactInfo`](./contactinfo)} Datum: {Datum} Reden: {[`Reason`](./reason)} Locatie: {[`Location`](./location) } ShowProperties is standaard waar. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekening-ID om de handtekening in het document te wijzigen via de methode Update of Verwijderen. Deze eigenschap wordt automatisch ingesteld nadat de teken- of zoekmethode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Haalt of stelt de tijd in waarop het document werd ondertekend. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Krijgt de vingerafdruk van een certificaat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Tijdstempel voor digitale PDF-handtekening. Standaardwaarde is null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Geeft de bovenste positie van de handtekening aan. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Type digitale PDF-handtekening. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert breedte van handtekening. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-type[`XAdESType`](../digitalsignature/xadestype) . De standaardwaarde is Geen (XAdES staat uit). Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clone Barcode Signature-exemplaar. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Overschrijft GetHashCode-methode |

### Zie ook

* class [DigitalSignature](../digitalsignature)
* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
