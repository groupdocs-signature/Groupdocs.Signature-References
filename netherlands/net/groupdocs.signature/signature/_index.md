---
title: Signature
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt de hoofdklasse die het documentondertekeningsproces regelt.
type: docs
weight: 1880
url: /nl/net/groupdocs.signature/signature/
---
## Signature class

Vertegenwoordigt de hoofdklasse die het documentondertekeningsproces regelt.

```csharp
public class Signature : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialiseert nieuw exemplaar van[`Signature`](../signature) klasse met document geleverd door stream. |
| [Signature](signature#constructor_4)(string) | Initialiseert nieuw exemplaar van[`Signature`](../signature) klasse-instantie met document geleverd door bestandspad. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialiseert nieuw exemplaar van[`Signature`](../signature) class met document geleverd door stream- en laadoptiesLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialiseert nieuw exemplaar van[`Signature`](../signature)class instantie met document geleverd door stream en[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialiseert nieuw exemplaar van[`Signature`](../signature) class-instantie met document geleverd door bestandspad enLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialiseert nieuw exemplaar van[`Signature`](../signature) class-instantie met document geleverd door bestandspad en[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialiseert nieuw exemplaar van[`Signature`](../signature) klasse-instantie met document geleverd door stream, laadoptiesLoadOptions en instellingen[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialiseert nieuw exemplaar van[`Signature`](../signature) klasse-instantie met document geleverd door bestandspad,LoadOptions En[`SignatureSettings`](../signaturesettings) . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Verwijdert doorgegeven handtekening[`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Verwijdert goedgekeurde lijst met handtekeningen[`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Verwijdert de handtekeningen van de lijst met bepaalde typen[`SignatureType`](../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd met de tekenmethode en zijn gemarkeerd als handtekeningen[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) wordt verwijderd. De volgende typen handtekeningen worden ondersteund: Tekst, Afbeelding, Digitaal, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Verwijdert goedgekeurde lijst met handtekeningen[`BaseSignature`](../../groupdocs.signature.domain/basesignature) uit het document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Verwijdert handtekeningen van het bepaalde type[`SignatureType`](../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd met de tekenmethode en zijn gemarkeerd als handtekeningen[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) wordt verwijderd. De volgende typen handtekeningen worden ondersteund: Tekst, Afbeelding, Digitaal, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Verwijdert handtekening door zijn specifieke handtekening-ID uit het document. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | IDisposable-interface implementeren om interne bronnen op te ruimen |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genereert voorbeeld van documentpagina's. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Krijgt informatie over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Zoekt naar handtekeningen in een document op[`SearchOptions`](../../groupdocs.signature.options/searchoptions) lijst. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Zoekt naar gespecificeerde handtekeningtypes in het document op[`SignatureType`](../../groupdocs.signature.domain/signaturetype) waarde. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Zoekt naar handtekeningen in een document op[`SearchOptions`](../../groupdocs.signature.options/searchoptions) opties. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Zoekt naar het exacte type handtekeningen in het document door[`SignatureType`](../../groupdocs.signature.domain/signaturetype) waarde. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Ondertekent document met verzameling van[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Ondertekent document met[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Ondertekent document met verzameling van[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Ondertekent document met[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Ondertekent document met verzameling van[`SignOptions`](../../groupdocs.signature.options/signoptions)en slaat het resultaat op in een stream met vooraf gedefinieerde[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Ondertekent document met[`SignOptions`](../../groupdocs.signature.options/signoptions)en slaat het resultaat op in een stream met vooraf gedefinieerde[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Ondertekent document met verzameling van[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad met vooraf gedefinieerd[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Ondertekent document met[`SignOptions`](../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad met vooraf gedefinieerd[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Updates geslaagd voor handtekening[`BaseSignature`](../../groupdocs.signature.domain/basesignature) in het document. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Updates doorgegeven handtekeningen[`BaseSignature`](../../groupdocs.signature.domain/basesignature) in het document. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifieert de documenthandtekeningen met een lijst met VerifyOptions-gegevens. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifieert de documenthandtekeningen met gegeven VerifyOptions-gegevens. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genereert handtekeningvoorbeeld op basis van gegeven SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Treedt op wanneer het zoekproces voor handtekeningen is voltooid. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Treedt op wanneer de voortgang van het zoekproces voor handtekeningen is gewijzigd. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Treedt op wanneer het zoekproces voor handtekeningen is gestart. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Treedt op wanneer het documentondertekeningsproces is voltooid. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Doet zich voor wanneer de voortgang van het documentondertekeningsproces is gewijzigd. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Treedt op bij het starten van het documentondertekeningsproces. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Doet zich voor wanneer het handtekeningverificatieproces is voltooid. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Doet zich voor wanneer de voortgang van het handtekeningverificatieproces is gewijzigd. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Treedt op wanneer het handtekeningverificatieproces is gestart. |

### Opmerkingen

**Kom meer te weten**

* Meer over GroupDocs.Signature-functies: [Handleiding voor ontwikkelaars van GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Zie ook

* naamruimte [GroupDocs.Signature](../../groupdocs.signature)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
