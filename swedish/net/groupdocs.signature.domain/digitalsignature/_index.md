---
title: DigitalSignature
second_title: GroupDocs.Signature för .NET API-referens
description: Innehåller egenskaper för digital signatur.
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

| namn | Beskrivning |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initiera digital signatur med standardparametrar. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initiera digital signatur med känt SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Skapa digital signatur med specificerat certifikat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Skapa digital signatur baserat på specificerad X509-butik. Det första certifikatet från angiven butik kommer att användas. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Skapa digital signatur baserat på specificerad X509 Store och index för certifikat. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Hämtar eller ställer in X509-certifikatet. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Anger butiksplatsen för certifikatet |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Anger butiksnamnet för certifikatet. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Hämtar eller ställer in kommentaren för signeringsändamål. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ställ in datum för att skapa signaturen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur togs bort från dokumentet. Den här egenskapen används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är signatur eller dokumentinnehåll. Den här egenskapen används med uppdateringsmetoden för att ställa in element som signatur (true) eller dokumentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Behåller sant om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ställ in datum för signaturändring. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidsignaturen som hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att ändra signaturen i dokumentet över Uppdatera eller Ta bort metoder. Den här egenskapen kommer att ställas in automatiskt efter att Sign- eller Sökmetoden anropas. Om den här egenskapen sparades innan den kan ställas in manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger typen av signatur. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Hämtar eller ställer in tiden då dokumentet signerades. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Får tumavtrycket av ett certifikat. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens topposition. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-typ[`XAdESType`](./xadestype) . Standardvärdet är Inget (XAdES är avstängt). För närvarande stöds XAdES-signaturtypen endast för kalkylarksdokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Klona streckkodsignaturinstans. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturegenskaper |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Åsidosätter GetHashCode method |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Ladda digital signatur från alla system X509 certifikatbutiker. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Ladda digital signatur från godkänd X509 Certificates Store. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Ladda digital signatur från godkänd X509 Certificates Store. |

### Se även

* class [BaseSignature](../basesignature)
* namnutrymme [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
