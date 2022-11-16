---
title: Signature
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar huvudklass som styr dokumentsigneringsprocessen.
type: docs
weight: 1800
url: /sv/net/groupdocs.signature/signature/
---
## Signature class

Representerar huvudklass som styr dokumentsigneringsprocessen.

```csharp
public class Signature : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initierar ny instans av[`Signature`](../signature) klass med dokument som tillhandahålls av stream. |
| [Signature](signature#constructor_4)(string) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av filsökväg. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initierar ny instans av[`Signature`](../signature) klass med dokument som tillhandahålls av ström- och laddningsalternativLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av stream och[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av filsökväg ochLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av filsökväg och[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av stream, laddningsalternativLoadOptions och inställningar[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initierar ny instans av[`Signature`](../signature) klassinstans med dokument som tillhandahålls av filsökväg,LoadOptions och[`SignatureSettings`](../signaturesettings) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Tar bort godkänd signatur[`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Tar bort godkänd lista med signaturer[`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Tar bort signaturerna för listan med vissa typer[`SignatureType`](../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign-metoden och markerade som Signaturer[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Tar bort godkänd lista med signaturer[`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Tar bort signaturer av en viss typ[`SignatureType`](../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign-metoden och markerade som Signaturer[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Tar bort signatur med dess specifika signatur-ID från dokumentet. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementera IDdisposable-gränssnitt för att rensa upp interna resurser |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genererar förhandsgranskning av dokumentsidor. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Får information om dokumentsidor: deras storlekar, maximal sidhöjd, bredden på en sida med maximal höjd. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Söker efter signaturer i ett dokument av[`SearchOptions`](../../groupdocs.signature.options/searchoptions) list. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Söker efter specificerade signaturtyper i dokumentet med[`SignatureType`](../../groupdocs.signature.domain/signaturetype) värde. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Söker efter signaturer i ett dokument av[`SearchOptions`](../../groupdocs.signature.options/searchoptions) alternativ. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Söker efter exakt typ av signaturer i dokumentet med[`SignatureType`](../../groupdocs.signature.domain/signaturetype) värde. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signerar dokument med samling av[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet i en stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Signerar dokument med[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet i en stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signerar dokument med samling av[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Signerar dokument med[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signerar dokument med samling av[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Signerar dokument med[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signerar dokument med samling av[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierad[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Signerar dokument med[`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierad[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Uppdateringar passerade signatur[`BaseSignature`](../../groupdocs.signature.domain/basesignature) i dokumentet. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Uppdaterar passerade signaturer[`BaseSignature`](../../groupdocs.signature.domain/basesignature) i dokumentet. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifierar dokumentsignaturerna med en lista över VerifyOptions-data. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifierar dokumentsignaturerna med givna VerifyOptions-data. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genererar signaturförhandsgranskning baserat på givna SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## evenemang

| namn | Beskrivning |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Uppstår när signatursökningsprocessen är klar. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Uppstår när signatursökningsprocessens framsteg ändras. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Uppstår när signatursökningsprocessen startade. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Uppstår när dokumentsigneringsprocessen är klar. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Uppstår när dokumentsigneringsprocessens framsteg ändras. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Uppstår när dokumentsigneringsprocessen startade. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Uppstår när signaturverifieringsprocessen är klar. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Uppstår när processen för signaturverifiering ändras. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Uppstår när signaturverifieringsprocessen startade. |

### Anmärkningar

**Läs mer**

* Mer om GroupDocs.Signaturfunktioner: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Se även

* namnutrymme [GroupDocs.Signature](../../groupdocs.signature)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
