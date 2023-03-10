---
title: QrCodeVerifyOptions
second_title: GroupDocs.Signature voor .NET API-referentie
description: Behoudt opties om document QRcode handtekening te verifiëren.
type: docs
weight: 1640
url: /nl/net/groupdocs.signature.options/qrcodeverifyoptions/
---
## QrCodeVerifyOptions class

Behoudt opties om document QR-code handtekening te verifiëren.

```csharp
public class QrCodeVerifyOptions : TextVerifyOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor)() | Creëert verificatieoptie QrCodeVerifyOptions voor QR-Code-handtekeningen. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_1)(string) | Creëert verificatieoptie QrCodeVerifyOptions voor QR-Code Handtekeningen met QR-Code tekst om te verifiëren. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_2)(string, QrCodeType) | Creëert verificatieoptie QrCodeVerifyOptions voor QR-Code-handtekeningen met tekst en QR-Code-coderingstype om te verifiëren. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Vlag om elke documentpagina te verifiëren. De standaardwaarde is waar. |
| [DataEncryption](../../groupdocs.signature.options/qrcodeverifyoptions/dataencryption) { get; set; } | Haalt of stelt implementatie in van[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface om QR-Code Signature Text-eigenschappen te coderen en decoderen. |
| [EncodeType](../../groupdocs.signature.options/qrcodeverifyoptions/encodetype) { get; set; } | Krijgt of stelt QR-code Type verificatie in. Deze eigenschap is optioneel. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Aanvullende extensies voor verificatie van alternatieve handtekeningopties. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | Haalt de titel van het formulierveld op of stelt deze in om het te verifiëren. Als deze eigenschappenset wordt ingesteld, wordt tekst alleen gevonden in tekstformuliervelden. |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | Haalt het type formulierveld op of stelt het in om het te verifiëren. Als deze eigenschappenset wordt ingesteld, wordt tekst alleen gevonden in tekstformuliervelden. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Geldige eigendomsvlag. |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | Verificatie van tekstovereenkomsttype ophalen of instellen. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Documentpaginanummer dat moet worden geverifieerd. Als de eigenschap niet is ingesteld, worden alle pagina's van het -document bij de eerste keer geverifieerd. Minimale waarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Pagina-opties om pagina's op te geven die moeten worden geverifieerd. |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | Geef een teksthandtekening-ID op die groter is dan nul als deze moet worden geverifieerd. Deze eigenschap wordt alleen ondersteund voor pdf-documenten |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | Type handtekening dat moet worden geverifieerd. |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | Geef handtekeningtekst op als deze moet worden geverifieerd. |

### Opmerkingen

**Kom meer te weten**

* Basisgebruik van verificatie voor elektronische handtekening met QR-code door GroupDocs.Signature: [ Hoe eVerificatie van QR-code handtekeningen in een document](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document)
* Geavanceerd gebruik van verificatie-instellingen voor elektronische handtekening met QR-code met GroupDocs.Signature: [Geavanceerd gebruik van eVerification QR-code handtekeningen in een document en aanvullende instellingen](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures)

### Zie ook

* class [TextVerifyOptions](../textverifyoptions)
* naamruimte [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->