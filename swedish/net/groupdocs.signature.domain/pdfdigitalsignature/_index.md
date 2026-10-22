---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Innehåller egenskaper för PDF‑digital signatur."
type: docs
weight: 840
url: /sv/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Innehåller egenskaper för PDF‑digital signatur.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initiera Pdf Digital Signature utan certifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Skapa Pdf Digital signature med angivet certifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initiera Pdf Digital Signature baserat på angivet X509 store. First certificate from specified store will be used. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Skapa Pdf Digital signature baserat på angivet X509 Store och index of certificate. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Hämtar eller anger X509 certificate. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Anger det anpassade lagernamnet för certifikatet. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Anger lagrets plats för certifikatet |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Anger lagrets namn för certifikatet. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Hämtar eller anger kommentaren för signeringsändamålet. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Information som tillhandahålls av undertecknaren för att möjliggöra för mottagaren att kontakta undertecknaren för att verifiera signaturen, t.ex. ett telefonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ange signaturens skapandedatum. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur har raderats från dokumentet. Denna egenskap används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är en Signature eller dokumentinnehåll. Denna egenskap används med Update-metoden för att sätta element som signatur (true) eller dokumentelement (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Sann om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | CPU‑värdnamnet eller den fysiska platsen för signeringen. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ange signaturens ändringsdatum. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidan som signaturen hittades på. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Anledningen till signeringen, t.ex. (I agree). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Tvinga att visa/dölja signaturegenskaper. Om ShowProperties är true signature field has predefined format of appearance Digitally signed by {[`ContactInfo`](./contactinfo)} Date: {Date} Reason: {[`Reason`](./reason)} Location: {[`Location`](./location)} ShowProperties is true by default. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att modifiera signatur i dokumentet via Update- eller Delete-metoder. Denna egenskap sätts automatiskt efter att Sign- eller Search-metoden har anropats. Om denna egenskap sparades tidigare kan den sättas manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger signaturens typ. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Hämtar eller anger tiden då dokumentet signerades. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Hämtar fingeravtrycket för ett certifikat. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Tidsstämpel för Pdf digital signature. Default value is null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens övre position. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Typ av PDF-digital signatur. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-typ [`XAdESType`](../digitalsignature/xadestype). Standardvärdet är None (XAdES är avstängt). För närvarande stöds XAdES-signaturtyp endast för kalkylbladsdokument. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Klona Barcode Signature-instans. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Åsidosätter GetHashCode-metoden |

### Se även

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
