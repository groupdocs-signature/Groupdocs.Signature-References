---
title: ImageMetadataSignature
second_title: GroupDocs.Signature voor .NET API-referentie
description: Bevat handtekeningeigenschappen van afbeeldingmetadata.
type: docs
weight: 570
url: /nl/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Bevat handtekeningeigenschappen van afbeeldingmetadata.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Creëert afbeelding metadata-handtekening met ID en waarde |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | De aanmaakdatum van de handtekening ophalen of instellen. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Haalt of stelt implementatie in van[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface voor het coderen en decoderen van handtekening Waarde-eigenschappen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Verkrijg de vlag die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logboekrecords van de documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Alleen-lezen waarde om een beschrijving op te halen voor standaard handtekening metagegevens afbeelding |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert hoogte van handtekening. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | De identifier van de afbeelding metadatahandtekening. ZieImageMetadataSignatures klasse die standaardhandtekening bevat met vooraf gedefinieerde ID-waarde. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Vlag ophalen of instellen om aan te geven of dit onderdeel Handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met Update-methode om element in te stellen als handtekening (true) of documentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert linkerpositie van handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | De wijzigingsdatum van de handtekening ophalen of instellen. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specificeert unieke metadatanaam. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Geeft aan dat de paginahandtekening is gevonden op. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekening-ID om de handtekening in het document te wijzigen via de methode Update of Verwijderen. Deze eigenschap wordt automatisch ingesteld nadat de teken- of zoekmethode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Alleen-lezen waarde om grootte van metadatawaarde te krijgen |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Geeft de bovenste positie van de handtekening aan. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specificeert het type metadatawaarde. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specificeert metadata-object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert breedte van handtekening. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clone Metadata Signature-instantie. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Clone Image Metadata Signature-instantie met gegeven waarde. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Verkrijg object van Metadata Signature Value over deserialisatie. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Verkrijg object van Metadata Signature Text over deserialisatie. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Overschrijft GetHashCode-methode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Converteert naar boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Converteert naar DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Converteert naar DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Converteert naar decimaal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Converteert naar decimaal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Converteert naar Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Converteert naar Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Converteert naar integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Converteert naar lang. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Converteert naar float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Converteert naar float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Converteert naar String met override ToString() methode |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Converteert naar String met opgegeven formaat |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converteert naar String met opgegeven formaat |

### Zie ook

* class [MetadataSignature](../metadatasignature)
* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
