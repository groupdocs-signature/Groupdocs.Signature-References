---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Bevat eigenschappen van digitale handtekening."
type: docs
weight: 150
url: /nl/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Bevat eigenschappen van digitale handtekening.

```csharp
public class DigitalSignature : BaseSignature
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialiseer digitale handtekening met standaardparameters. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialiseer digitale handtekening met bekende SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Maak digitale handtekening met opgegeven certificaat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Maak digitale handtekening op basis van opgegeven X509-opslag. Het eerste certificaat uit de opgegeven opslag wordt gebruikt. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Maak digitale handtekening op basis van opgegeven X509-opslag en index van certificaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Haalt of stelt het X509-certificaat in. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Specificeert de aangepaste winkelnaam van het certificaat. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specificeert de locatie van de winkel van het certificaat. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specificeert de winkelnaam van het certificaat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Haalt of stelt de ondertekeningsdoelcommentaar in. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Haal op of stel de creatiedatum van de handtekening in. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Haal de vlag op die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logrecords van documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert de hoogte van de handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Haal op of stel de vlag in om aan te geven of dit component een handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Blijft waar (true) als deze digitale handtekening geldig is en het document niet is gemanipuleerd. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert de linkse positie van de handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Haal op of stel de wijzigingsdatum van de handtekening in. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specificeert de pagina waarop de handtekening is gevonden. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Haalt of stelt de tijd in waarop het document is ondertekend. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Haalt de vingerafdruk van een certificaat op. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specificeert de bovenste positie van de handtekening. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert de breedte van de handtekening. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES type [`XAdESType`](./xadestype). Standaardwaarde is None (XAdES is uitgeschakeld). Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Kloon Barcode Signature‑instantie. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Overschrijft de Equals‑methode om handtekeningeigenschappen te vergelijken |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Overschrijft de GetHashCode‑methode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Laad digitale handtekeningen uit alle systeem X509-certificaatopslagplaatsen. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Laad digitale handtekeningen uit een certificaatopslag. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Laad digitale handtekeningen uit een certificaatopslag. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Laad digitale handtekeningen uit een digitale certificaatopslag op een specifieke locatie. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Laad digitale handtekeningen uit een digitale certificaatopslag op een specifieke locatie. |

### Zie ook

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
