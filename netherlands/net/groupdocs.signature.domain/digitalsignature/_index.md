---
title: DigitalSignature
second_title: GroupDocs.Signature voor .NET API-referentie
description: Bevat digitale handtekeningeigenschappen.
type: docs
weight: 150
url: /nl/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Bevat digitale handtekeningeigenschappen.

```csharp
public class DigitalSignature : BaseSignature
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialiseer digitale handtekening met standaardparameters. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialiseer digitale handtekening met bekende SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Digitale handtekening maken met opgegeven certificaat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Maak een digitale handtekening op basis van de opgegeven X509-opslag. Het eerste certificaat van de opgegeven winkel wordt gebruikt. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Digitale handtekening maken op basis van gespecificeerde X509 Store en index van certificaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Haalt of stelt het X509-certificaat in. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specificeert de opslaglocatie van het certificaat |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specificeert de winkelnaam van het certificaat. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Krijgt of stelt de opmerking over het ondertekeningsdoel in. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | De aanmaakdatum van de handtekening ophalen of instellen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Verkrijg de vlag die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logboekrecords van de documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert hoogte van handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Vlag ophalen of instellen om aan te geven of dit onderdeel Handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met Update-methode om element in te stellen als handtekening (true) of documentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Blijft waar als deze digitale handtekening geldig is en er niet met het document is geknoeid. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert linkerpositie van handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | De wijzigingsdatum van de handtekening ophalen of instellen. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Geeft aan dat de paginahandtekening is gevonden op. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekening-ID om de handtekening in het document te wijzigen via de methode Update of Verwijderen. Deze eigenschap wordt automatisch ingesteld nadat de teken- of zoekmethode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Haalt of stelt de tijd in waarop het document werd ondertekend. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Krijgt de vingerafdruk van een certificaat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Geeft de bovenste positie van de handtekening aan. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert breedte van handtekening. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-type[`XAdESType`](./xadestype) . De standaardwaarde is Geen (XAdES staat uit). Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clone Barcode Signature-exemplaar. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Overschrijft GetHashCode-methode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Laad digitale handtekening uit alle X509-certificatenarchieven van het systeem. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Laad digitale handtekening uit doorgegeven X509-certificatenarchief. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Laad digitale handtekening uit doorgegeven X509-certificatenarchief. |

### Zie ook

* class [BaseSignature](../basesignature)
* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
