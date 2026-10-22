---
title: "DigitalSignature"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Innehåller egenskaper för digital signatur."
type: docs
weight: 150
url: /sv/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Innehåller egenskaper för digital signatur.

```csharp
public class DigitalSignature : BaseSignature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initierar Digital signature med standardparametrar. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initierar Digital signature med känt SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Skapa Digital signature med angivet certifikat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Skapa Digital signature baserat på angivet X509-lager. Första certifikatet från angivet lager kommer att användas. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Skapa Digital signature baserat på angivet X509-lager och certifikatets index. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Hämtar eller anger X509 certificate. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Anger det anpassade lagernamnet för certifikatet. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Anger lagrets plats för certifikatet |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Anger lagrets namn för certifikatet. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Hämtar eller anger kommentaren för signeringsändamålet. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ange signaturens skapandedatum. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur har raderats från dokumentet. Denna egenskap används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är en Signature eller dokumentinnehåll. Denna egenskap används med Update-metoden för att sätta element som signatur (true) eller dokumentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Sann om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ange signaturens ändringsdatum. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidan som signaturen hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att modifiera signatur i dokumentet via Update- eller Delete-metoder. Denna egenskap sätts automatiskt efter att Sign- eller Search-metoden har anropats. Om denna egenskap sparades tidigare kan den sättas manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger signaturens typ. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Hämtar eller anger tiden då dokumentet signerades. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Hämtar fingeravtrycket för ett certifikat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens övre position. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-typ [`XAdESType`](./xadestype). Standardvärdet är None (XAdES är avstängt). För närvarande stöds XAdES-signaturtyp endast för Spreadsheet-dokument. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Klona Barcode Signature-instans. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Åsidosätter GetHashCode-metoden |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Läs in Digital signatures från alla systemets X509-certifikatlagringar. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Läs in Digital signatures från ett certifikatlagringsutrymme. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Läs in Digital signatures från ett certifikatlagringsutrymme. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Läs in Digital signatures från ett digitalt certifikatlagringsutrymme placerat på en specifik plats. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Läs in Digital signatures från ett digitalt certifikatlagringsutrymme placerat på en specifik plats. |

### Se även

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
