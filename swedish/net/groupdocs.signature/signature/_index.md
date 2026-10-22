---
title: "Signatur"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar huvudklassen som styr dokumentets signeringsprocess."
type: docs
weight: 2170
url: /sv/net/groupdocs.signature/signature/
---
## Signature class

Representerar huvudklassen som styr dokumentets signeringsprocess.

```csharp
public class Signature : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en ström. |
| [Signature](signature#constructor_4)(string) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en filsökväg. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en ström och laddningsalternativ LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en ström och [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en filsökväg och LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en filsökväg och [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en ström, laddningsalternativ LoadOptions och inställningar [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initierar en ny instans av klassen [`Signature`](../signature) med dokument som tillhandahålls via en filsökväg, LoadOptions och [`SignatureSettings`](../signaturesettings). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Tar bort den angivna signaturen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Tar bort den angivna listan av signaturer [`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Tar bort signaturerna av de angivna typerna i listan [`SignatureType`](../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lades till med Sign‑metoden och som är markerade som Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Tar bort den angivna listan av signaturer [`BaseSignature`](../../groupdocs.signature.domain/basesignature) från dokumentet. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Tar bort signaturer av den angivna typen [`SignatureType`](../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lades till med Sign‑metoden och som är markerade som Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Tar bort signaturen med dess specifika signatur‑Id från dokumentet. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementera IDisposable‑gränssnittet för att rensa interna resurser |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genererar förhandsgranskning av dokumentets sidor. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Hämtar information om dokumentets sidor: deras storlekar, maximal sidhöjd, bredden på en sida med den maximala höjden. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Söker efter signaturer i dokumentet med alla tillgängliga sökalternativ och filtrerar resultaten baserat på det angivna predikatet. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Söker efter signaturer i ett dokument med en [`SearchOptions`](../../groupdocs.signature.options/searchoptions)-lista. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Söker efter angivna signaturtyper i dokumentet med värdet för [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Söker efter signaturer i dokumentet med de angivna sökalternativen och filtrerar resultaten baserat på det angivna predikatet. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Söker efter signaturer i ett dokument med [`SearchOptions`](../../groupdocs.signature.options/searchoptions)-alternativ. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Söker efter exakt typ av signaturer i dokumentet med värdet för [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signerar dokumentet med en samling av [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Signerar dokumentet med [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signerar dokumentet med en samling av [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till den angivna filvägen. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Signerar dokumentet med [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till den angivna filvägen. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signerar dokumentet med en samling av [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Signerar dokumentet med [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signerar dokumentet med en samling av [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till den angivna filvägen med fördefinierade [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Signerar dokumentet med [`SignOptions`](../../groupdocs.signature.options/signoptions) och sparar resultatet till den angivna filvägen med fördefinierade [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Uppdaterar den angivna signaturen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) i dokumentet. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Uppdaterar de angivna signaturerna [`BaseSignature`](../../groupdocs.signature.domain/basesignature) i dokumentet. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifierar dokumentets signaturer med en lista av VerifyOptions-data. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifierar dokumentets signaturer med angivna VerifyOptions-data. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Verifierar dokumentets signaturer med alla tillgängliga verifieringsalternativ och filtrerar resultaten baserat på det angivna predikatet. Denna metod söker först efter signaturer som matchar verifieringsalternativen, filtrerar dem med predikatet och verifierar sedan endast de filtrerade signaturerna. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Verifierar dokumentets signaturer med de angivna verifieringsalternativen och filtrerar resultaten baserat på det angivna predikatet. Denna metod söker först efter signaturer som matchar verifieringsalternativen, filtrerar dem med predikatet och verifierar sedan endast de filtrerade signaturerna. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genererar förhandsgranskning av signatur baserat på angivna SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Inträffar när signatursökprocessen har slutförts. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Inträffar när signatursökprocessens framsteg har ändrats. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Inträffar när signatursökprocessen startas. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Inträffar när dokumentets signeringsprocess har slutförts. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Inträffar när dokumentets signeringsprocessens framsteg har ändrats. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Inträffar när dokumentets signeringsprocess startas. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Inträffar när signaturverifieringsprocessen har slutförts. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Inträffar när signaturverifieringsprocessens framsteg har ändrats. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Inträffar när signaturverifieringsprocessen startas. |

### Anmärkningar

**Learn more**

Mer om funktionerna i GroupDocs.Signature: [GroupDocs.Signature Utvecklarguide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Se även

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
