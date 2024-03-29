---
title: SignatureSettings
second_title: GroupDocs.Signature voor .NET API-referentie
description: Definieert instellingen voor aanpassenSignature./signature gedrag.
type: docs
weight: 1890
url: /nl/net/groupdocs.signature/signaturesettings/
---
## SignatureSettings class

Definieert instellingen voor aanpassen[`Signature`](../signature) gedrag.

```csharp
public class SignatureSettings
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SignatureSettings](signaturesettings#constructor)() | Maakt standaard SignatureSettings-instantie met standaardwaarden. |
| [SignatureSettings](signaturesettings#constructor_1)(ILogger) | Maakt standaard SignatureSettings-instantie met de Logger-implementatie. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DefaultCulture](../../groupdocs.signature/signaturesettings/defaultculture) { get; set; } | Haalt de standaardcultuur op of stelt deze in voor gebruik tijdens documentverwerking. Standaardwaarde is "en-US". |
| [IncludeStandardMetadataSignatures](../../groupdocs.signature/signaturesettings/includestandardmetadatasignatures) { get; set; } | Haalt de vlag op of stelt deze in om op te nemen in de metagegevens Maak een lijst van de ingesloten standaard metagegevenshandtekeningen van het document, zoals auteur, eigenaar, aanmaakdatum van het document, wijzigingsdatum, enz. Als deze vlag is ingesteld op onwaar (standaard), zal GetDocumentInfo deze metagegevens niet opnemen signatures. Wanneer deze vlag is ingesteld op true, bevat de documentinformatie deze standaard metadata signatures. |
| [Logger](../../groupdocs.signature/signaturesettings/logger) { get; } | De logger-implementatie die wordt gebruikt voor logboekregistratie (fouten, waarschuwingen, sporen).[`ILogger`](../../groupdocs.signature.logging/ilogger) . |
| [LogLevel](../../groupdocs.signature/signaturesettings/loglevel) { get; set; } | Het niveau van de logging om de berichten te beperken (Alles, Traces, Waarschuwingen, Fouten).[`LogLevel`](./loglevel) . Standaard is het All level type ingesteld. |
| [SaveDocumentOnEmptyDelete](../../groupdocs.signature/signaturesettings/savedocumentonemptydelete) { get; set; } | Haalt de vlag op of stelt deze in om het brondocument opnieuw op te slaan wanneer de methode Verwijderen geen betrokken handtekeningen heeft om te verwijderen. Als deze vlag is ingesteld op waar (standaard), wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en bewerkingstype), zelfs als Verwijdermethode heeft geen handtekeningen om te verwijderen. Wanneer deze flat is ingesteld op false, wordt het brondocument helemaal niet gewijzigd. |
| [SaveDocumentOnEmptyUpdate](../../groupdocs.signature/signaturesettings/savedocumentonemptyupdate) { get; set; } | Haalt de vlag op of stelt deze in om het brondocument opnieuw op te slaan wanneer de methode Update geen handtekeningen heeft om bij te werken. Als deze vlag is ingesteld op waar (standaard), wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en bewerkingstype), zelfs als Update methode heeft geen handtekeningen om bij te werken. Wanneer deze flat is ingesteld op false, wordt het brondocument helemaal niet gewijzigd. |
| [ShowDeletedSignaturesInfo](../../groupdocs.signature/signaturesettings/showdeletedsignaturesinfo) { get; set; } | Hiermee wordt een vlag opgehaald of ingesteld die verwijderde handtekeningen bevat in het documentinformatieresultaat. Elke handtekening[`BaseSignature`](../../groupdocs.signature.domain/basesignature) heeft de vlag verwijderd[`Deleted`](../../groupdocs.signature.domain/basesignature/deleted) om te detecteren of het is verwijderd. |

### Zie ook

* naamruimte [GroupDocs.Signature](../../groupdocs.signature)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
