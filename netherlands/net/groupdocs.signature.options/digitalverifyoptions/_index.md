---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Bevat opties om de digitale handtekening van een document te verifiëren."
type: docs
weight: 1570
url: /nl/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

Bevat opties om de digitale handtekening van een document te verifiëren.

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | Maakt Digital Verification Option aan met standaardwaarden. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | Maakt Digital Verification Option aan met de opgegeven certificaat‑stream. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | Maakt Digital Verification Option aan met het opgegeven bestandspad van het digitale certificaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Vlag om elke documentpagina te verifiëren. Standaardwaarde is true. |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | Haalt X509Certificate2‑certificaat op uit certificaat‑bestandspad of stream. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | Bestandspad van digitaal certificaat. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | Stream van digitaal certificaat. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | Opmerkingen van digitale handtekening om te valideren. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | Handtekeningcontact om te valideren. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Aanvullende extensies voor verificatie van alternatieve handtekeningopties. |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | Naam van uitgever van het certificaat om te valideren. Waarde is hoofdlettergevoelig. Als deze eigenschap is ingesteld, controleert de verificatie of de uitgeversnaam van de handtekening de opgegeven waarde bevat of gelijk is. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Geldige eigenschapsvlag. |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | Handtekeninglocatie om te valideren. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Documentpaginanummer dat moet worden geverifieerd. Als de eigenschap niet is ingesteld - worden alle pagina's van het document geverifieerd voor de eerste keer. Minimale waarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Pagina-opties om de te verifiëren pagina's op te geven. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | Wachtwoord van digitaal certificaat indien vereist. |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | Reden van digitale handtekening om te valideren. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Specificeert de positie van de vorm in de documentlay-out. Voor het verifiëren van handtekeningen in kop- en voetteksten. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | Datum- en tijdsbereik van de digitale handtekening om te valideren. Null-waarde wordt genegeerd. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | Datum- en tijdsbereik van de digitale handtekening om te valideren. Null-waarde wordt genegeerd. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | Onderwerp distinguished name van het certificaat om te valideren. Waarde is hoofdlettergevoelig. Als deze eigenschap is ingesteld, controleert de verificatie of de handtekeningonderwerpnaam de opgegeven waarde bevat of gelijk is aan die waarde. |

### Opmerkingen

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings]()

### Zie ook

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
