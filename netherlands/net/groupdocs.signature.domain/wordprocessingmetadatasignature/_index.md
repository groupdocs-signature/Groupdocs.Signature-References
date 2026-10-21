---
title: "WordProcessingMetadataSignature"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Bevat handtekeningeigenschappen voor WordProcessing-metadata."
type: docs
weight: 1260
url: /nl/net/groupdocs.signature.domain/wordprocessingmetadatasignature/
---
## WordProcessingMetadataSignature class

Bevat handtekeningeigenschappen voor WordProcessing-metadata.

```csharp
public sealed class WordProcessingMetadataSignature : MetadataSignature
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor)(string) | Maakt WordProcessing Metadata Signature aan met een vooraf gedefinieerde naam en een lege waarde. |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor_1)(string, object) | Maakt WordProcessing Metadata Signature aan met vooraf gedefinieerde waarden. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Haal op of stel de creatiedatum van de handtekening in. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Haalt op of stelt de implementatie van [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Haal de vlag op die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logrecords van documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert de hoogte van de handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Haal op of stel de vlag in om aan te geven of dit component een handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert de linkse positie van de handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Haal op of stel de wijzigingsdatum van de handtekening in. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specificeert een unieke metadata-naam. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specificeert de pagina waarop de handtekening is gevonden. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specificeert de bovenste positie van de handtekening. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specificeert het metadata-waardetype. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specificeert het metadata-object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert de breedte van de handtekening. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone_1)() | Kloon Metadata Signature‑instantie. |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone)(object) | Kloon Words Metadata Signature‑instantie met de opgegeven waarde. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Overschrijft de Equals‑methode om handtekeningeigenschappen te vergelijken |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Verkrijg object van Metadata Signature Value via deserialisatie. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Verkrijg object van Metadata Signature Text via deserialisatie. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Overschrijft de GetHashCode‑methode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converteert naar boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Converteert naar DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Converteert naar DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Converteert naar Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Converteert naar Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Converteert naar Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Converteert naar Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converteert naar integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Converteert naar float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Converteert naar float. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring)() | Converteert naar String met de overschreven ToString() methode |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converteert naar String met opgegeven formaat |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converteert naar String met opgegeven formaat |

### Zie ook

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
