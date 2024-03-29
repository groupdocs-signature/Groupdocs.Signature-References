---
title: SearchResult
second_title: GroupDocs.Signature voor .NET API-referentie
description: Resultaat van zoeken naar handtekeningen in opgegeven document.
type: docs
weight: 830
url: /nl/net/groupdocs.signature.domain/searchresult/
---
## SearchResult class

Resultaat van zoeken naar handtekeningen in opgegeven document.

```csharp
public class SearchResult : IEnumerable<BaseSignature>, IResult
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/searchresult/destindocumentsize) { get; } | Retourneert de grootte van het bestemmingsdocument. Voor zoekmethode retourneert het altijd 0. |
| [ProcessingTime](../../groupdocs.signature.domain/searchresult/processingtime) { get; } | Retourneert de uitvoeringstijd van het zoekproces in milliseconden. |
| [Signatures](../../groupdocs.signature.domain/searchresult/signatures) { get; } | Lijst met gevonden handtekeningen[`BaseSignature`](../basesignature) . |
| [SourceDocumentSize](../../groupdocs.signature.domain/searchresult/sourcedocumentsize) { get; } | Retourneert brondocument size |
| [Succeeded](../../groupdocs.signature.domain/searchresult/succeeded) { get; } | Lijst met gevonden handtekeningen[`BaseSignature`](../basesignature) . Deze lijst is altijd gelijk aan[`Signatures`](./signatures) eigendom. |
| [TotalSignatures](../../groupdocs.signature.domain/searchresult/totalsignatures) { get; } | Retourneert het totale aantal verwerkte handtekeningen door het zoekproces |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetEnumerator](../../groupdocs.signature.domain/searchresult/getenumerator)() | Retourneert teller. |
| [ToList&lt;T&gt;](../../groupdocs.signature.domain/searchresult/tolist)() | Biedt conversie naar sterk getypte lijst met handtekeningen. |

### Zie ook

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
