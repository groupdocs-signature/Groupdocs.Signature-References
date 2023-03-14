---
title: PdfMetadataSignature
second_title: GroupDocs.Signature voor .NET API-referentie
description: Bevat Pdf Metadata handtekening eigenschappen.
type: docs
weight: 680
url: /nl/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Bevat Pdf Metadata handtekening eigenschappen.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Creëert Pdf Metadata-handtekening met vooraf gedefinieerde naam en lege waarde |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Creëert Pdf Metadata-handtekening met vooraf gedefinieerde waarden |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Creëert Pdf Metadata-handtekening met vooraf gedefinieerde waarden |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | De aanmaakdatum van de handtekening ophalen of instellen. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Haalt of stelt implementatie in van[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface voor het coderen en decoderen van handtekening Waarde-eigenschappen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Verkrijg de vlag die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logboekrecords van de documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert hoogte van handtekening. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Vlag ophalen of instellen om aan te geven of dit onderdeel Handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met Update-methode om element in te stellen als handtekening (true) of documentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert linkerpositie van handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | De wijzigingsdatum van de handtekening ophalen of instellen. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specificeert unieke metadatanaam. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Geeft aan dat de paginahandtekening is gevonden op. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekening-ID om de handtekening in het document te wijzigen via de methode Update of Verwijderen. Deze eigenschap wordt automatisch ingesteld nadat de teken- of zoekmethode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | De prefix-tag van Pdf Metadata-handtekeningnaam. Deze eigenschap is standaard ingesteld op "xmp". Mogelijke waarden zijn |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Geeft de bovenste positie van de handtekening aan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specificeert het type metadatawaarde. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specificeert metadata-object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert breedte van handtekening. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Clone Metadata Signature-instantie. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Clone Pdf Metadata Signature-instantie met opgegeven waarde. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Verkrijg object van Metadata Signature Value over deserialisatie. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Verkrijg object van Metadata Signature Text over deserialisatie. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Overschrijft GetHashCode-methode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converteert naar boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Converteert naar DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Converteert naar DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Converteert naar decimaal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Converteert naar decimaal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Converteert naar Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Converteert naar Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converteert naar integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Converteert naar float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Converteert naar float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Converteert naar String met override ToString() methode |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converteert naar String met opgegeven formaat |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | Converteert naar String met opgegeven formaat |

### Zie ook

* class [MetadataSignature](../metadatasignature)
* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
