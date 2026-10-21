---
title: "Handtekening"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Stelt de hoofdklasse voor die het ondertekeningsproces van documenten beheert."
type: docs
weight: 2170
url: /nl/net/groupdocs.signature/signature/
---
## Signature class

Stelt de hoofdklasse voor die het ondertekeningsproces van documenten beheert.

```csharp
public class Signature : IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een stream. |
| [Signature](signature#constructor_4)(string) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een bestandspad. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een stream en laadopties LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een stream en [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een bestandspad en LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een bestandspad en [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een stream, laadopties LoadOptions en instellingen [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialiseert een nieuwe instantie van de klasse [`Signature`](../signature) met een document geleverd via een bestandspad, LoadOptions en [`SignatureSettings`](../signaturesettings). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Verwijdert de meegegeven handtekening [`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Verwijdert de meegegeven lijst van handtekeningen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Verwijdert de handtekeningen van de opgegeven typenlijst [`SignatureType`](../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd via de Sign-methode en gemarkeerd zijn als handtekeningen [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) worden verwijderd. De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code. |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Verwijdert de meegegeven lijst van handtekeningen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Verwijdert handtekeningen van een bepaald type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd via de Sign-methode en gemarkeerd zijn als handtekeningen [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) worden verwijderd. De volgende handtekeningtypen worden ondersteund: Text, Image, Digital, Barcode, QR-Code. |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Verwijdert een handtekening op basis van zijn specifieke handtekening‑Id uit het document. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementeer de IDisposable‑interface om interne bronnen op te ruimen |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genereert een voorbeeld van documentpagina's. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Haalt informatie op over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Zoekt naar handtekeningen in het document met alle beschikbare zoekopties en filtert de resultaten op basis van het opgegeven predicaat. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Zoekt handtekeningen in een document met een lijst van [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Zoekt naar opgegeven handtekeningtypen in het document op basis van de waarde van [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Zoekt handtekeningen in het document met behulp van de opgegeven zoekopties en filtert de resultaten op basis van het opgegeven predicaat. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Zoekt handtekeningen in een document met [`SearchOptions`](../../groupdocs.signature.options/searchoptions) opties. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Zoekt naar het exacte type handtekeningen in het document op basis van de waarde van [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Ondertekent een document met een verzameling van [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Ondertekent een document met [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Ondertekent een document met een verzameling van [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op op het opgegeven bestandspad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Ondertekent een document met [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op op het opgegeven bestandspad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Ondertekent een document met een verzameling van [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream met vooraf gedefinieerde [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Ondertekent een document met [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream met vooraf gedefinieerde [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Ondertekent een document met een verzameling van [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op op het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Ondertekent een document met [`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op op het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Werkt de meegegeven handtekening [`BaseSignature`](../../groupdocs.signature.domain/basesignature) bij in het document. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Werkt de meegegeven handtekeningen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) bij in het document. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifieert de handtekeningen van het document met een lijst van VerifyOptions-gegevens. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Verifieert de handtekeningen van het document met behulp van alle beschikbare verificatieopties en filtert de resultaten op basis van het opgegeven predicaat. Deze methode zoekt eerst naar handtekeningen die overeenkomen met de verificatieopties, filtert ze met het predicaat, en verifieert vervolgens alleen die gefilterde handtekeningen. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Verifieert de handtekeningen van het document met de opgegeven verificatieopties en filtert de resultaten op basis van het opgegeven predicaat. Deze methode zoekt eerst naar handtekeningen die overeenkomen met de verificatieopties, filtert ze met het predicaat, en verifieert vervolgens alleen die gefilterde handtekeningen. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genereert een voorbeeld van de handtekening op basis van de opgegeven SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Vindt plaats wanneer het handtekeningzoekproces is voltooid. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Vindt plaats wanneer de voortgang van het handtekeningzoekproces verandert. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Vindt plaats wanneer het handtekeningzoekproces start. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Vindt plaats wanneer het documentondertekeningsproces is voltooid. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Komt voor wanneer de voortgang van het ondertekeningsproces van het document is gewijzigd. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Komt voor wanneer het ondertekeningsproces van het document is gestart. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Komt voor wanneer het verificatieproces van de handtekening is voltooid. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Komt voor wanneer de voortgang van het verificatieproces van de handtekening is gewijzigd. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Komt voor wanneer het verificatieproces van de handtekening is gestart. |

### Opmerkingen

**Learn more**

Meer over de functies van GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Zie ook

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
