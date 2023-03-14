---
title: PdfDigitalSignature
second_title: GroupDocs.Signature för .NET API-referens
description: Innehåller PDFegenskaper för digitala signaturer.
type: docs
weight: 660
url: /sv/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Innehåller PDF-egenskaper för digitala signaturer.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initiera Pdf digital signatur utan certifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Skapa digital pdf-signatur med specificerat certifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initiera Pdf Digital Signatur baserat på specificerad X509-butik. Det första certifikatet från angiven butik kommer att användas. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Skapa PDF Digital signatur baserat på specificerad X509 Store och certifikatsindex. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Hämtar eller ställer in X509-certifikatet. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Anger butiksplatsen för certifikatet |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Anger butiksnamnet för certifikatet. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Hämtar eller ställer in kommentaren för signeringsändamål. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Information tillhandahållen av undertecknaren för att göra det möjligt för en mottagare att kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ställ in datum för att skapa signaturen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur togs bort från dokumentet. Den här egenskapen används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är signatur eller dokumentinnehåll. Den här egenskapen används med uppdateringsmetoden för att ställa in element som signatur (true) eller dokumentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Behåller sant om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | CPU-värdnamnet eller den fysiska platsen för signeringen. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ställ in datum för signaturändring. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidsignaturen som hittades på. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Orsaken till undertecknandet, såsom (jag håller medРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är sant har signatur fältet fördefinierat format för utseende Digitalt signerat av {[`ContactInfo`](./contactinfo)} Datum: {Date} Orsak: {[`Reason`](./reason)} Plats: {[`Location`](./location) } ShowProperties är sant som standard. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att ändra signaturen i dokumentet över Uppdatera eller Ta bort metoder. Den här egenskapen kommer att ställas in automatiskt efter att Sign- eller Sökmetoden anropas. Om den här egenskapen sparades innan den kan ställas in manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger typen av signatur. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Hämtar eller ställer in tiden då dokumentet signerades. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Får tumavtrycket av ett certifikat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Tidsstämpel för Pdf digital signatur. Standardvärdet är null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens topposition. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Typ av Pdf digital signatur. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-typ[`XAdESType`](../digitalsignature/xadestype) . Standardvärdet är Inget (XAdES är avstängt). För närvarande stöds XAdES-signaturtypen endast för kalkylarksdokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Klona streckkodsignaturinstans. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturegenskaper |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Åsidosätter GetHashCode method |

### Se även

* class [DigitalSignature](../digitalsignature)
* namnutrymme [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
