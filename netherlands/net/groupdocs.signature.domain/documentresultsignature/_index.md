---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Resultaat van het verwerken van het ondertekeningsproces van een archiefdocument voor een document met nieuw aangemaakte handtekeningen."
type: docs
weight: 170
url: /nl/net/groupdocs.signature.domain/documentresultsignature/
---
## DocumentResultSignature class

Resultaat van het verwerken van het ondertekeningsproces van een archiefdocument voor een document met nieuw aangemaakte handtekeningen.

```csharp
public class DocumentResultSignature : BaseSignature, IResult
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Haal op of stel de creatiedatum van de handtekening in. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Haal de vlag op die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logrecords van documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [DestinDocumentSize](../../groupdocs.signature.domain/documentresultsignature/destindocumentsize) { get; } | Retourneert de grootte van het bestemmingsdocument |
| [ErrorMessage](../../groupdocs.signature.domain/documentresultsignature/errormessage) { get; } | Als het document met een fout is verwerkt, zal deze eigenschap het foutbericht bevatten. |
| [Failed](../../groupdocs.signature.domain/documentresultsignature/failed) { get; } | Lijst van de handtekeningen die tijdens het proces zijn mislukt [`BaseSignature`](../basesignature). |
| [FileName](../../groupdocs.signature.domain/documentresultsignature/filename) { get; } | Bestandsnaam van het document |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert de hoogte van de handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Haal op of stel de vlag in om aan te geven of dit component een handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert de linkse positie van de handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Haal op of stel de wijzigingsdatum van de handtekening in. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specificeert de pagina waarop de handtekening is gevonden. |
| [ProcessingTime](../../groupdocs.signature.domain/documentresultsignature/processingtime) { get; } | Retourneert de uitvoeringstijd van het proces in milliseconden |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [SourceDocumentSize](../../groupdocs.signature.domain/documentresultsignature/sourcedocumentsize) { get; } | Retourneert de grootte van het brondocument |
| [Succeeded](../../groupdocs.signature.domain/documentresultsignature/succeeded) { get; } | Lijst van succesvol verwerkte handtekeningen [`BaseSignature`](../basesignature). |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specificeert de bovenste positie van de handtekening. |
| [TotalSignatures](../../groupdocs.signature.domain/documentresultsignature/totalsignatures) { get; } | Retourneert het totale aantal verwerkte handtekeningen |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert de breedte van de handtekening. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain/basesignature/clone)() | Kloon handtekeninginstantie. |
| override [Equals](../../groupdocs.signature.domain/basesignature/equals)(object) | Overschrijft de Equals‑methode om handtekeningeigenschappen te vergelijken |
| override [GetHashCode](../../groupdocs.signature.domain/basesignature/gethashcode)() | Overschrijft de GetHashCode‑methode |

### Opmerkingen

**Learn more**

* More about signing documents withing archives using GroupDocs.Signature: [How to sign documents withing archives using C#](https://docs.groupdocs.com/signature/net/signing-archive-documents/)

### Zie ook

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
