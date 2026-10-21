---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Bevat eigenschappen van afbeelding‑metadata‑handtekening."
type: docs
weight: 740
url: /nl/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Bevat eigenschappen van afbeelding‑metadata‑handtekening.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Maakt een Image Metadata Signature aan met Id en waarde |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Haal op of stel de creatiedatum van de handtekening in. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Haalt op of stelt de implementatie van [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface in om handtekening Value-eigenschappen te coderen en decoderen. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Haal de vlag op die aangeeft of deze handtekening uit het document is verwijderd. Deze eigenschap wordt alleen gebruikt voor logrecords van documentgeschiedenis om de lijst met verwijderde handtekeningen bij te houden. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Alleen-lezen waarde om de beschrijving voor een standaard Image Metadata handtekening op te halen |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specificeert de hoogte van de handtekening. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | De identifier van de Image Metadata-handtekening. Zie de ImageMetadataSignatures klasse die een standaardhandtekening bevat met een vooraf gedefinieerde Id-waarde. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Haal op of stel de vlag in om aan te geven of dit component een handtekening of documentinhoud is. Deze eigenschap wordt gebruikt met de Update-methode om het element als handtekening (true) of als documentelement (false) in te stellen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specificeert de linkse positie van de handtekening. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Haal op of stel de wijzigingsdatum van de handtekening in. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specificeert een unieke metadata-naam. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specificeert de pagina waarop de handtekening is gevonden. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unieke handtekeningidentificatie om de handtekening in het document te wijzigen via Update- of Delete-methoden. Deze eigenschap wordt automatisch ingesteld nadat de Sign- of Search-methode is aangeroepen. Als deze eigenschap eerder is opgeslagen, kan deze handmatig worden ingesteld om de handtekening te manipuleren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specificeert het type handtekening. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Alleen-lezen waarde om de grootte van de Metadata-waarde op te halen |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specificeert de bovenste positie van de handtekening. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specificeert het metadata-waardetype. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specificeert het metadata-object. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specificeert de breedte van de handtekening. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Kloon Metadata Signature‑instantie. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Dupliceer Image Metadata Signature‑instantie met de opgegeven waarde. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Overschrijft de Equals‑methode om handtekeningeigenschappen te vergelijken |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Verkrijg object van Metadata Signature Value via deserialisatie. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Verkrijg object van Metadata Signature Text via deserialisatie. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Overschrijft de GetHashCode‑methode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Converteert naar boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Converteert naar DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Converteert naar DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Converteert naar Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Converteert naar Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Converteert naar Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Converteert naar Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Converteert naar integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Converteert naar long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Converteert naar float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Converteert naar float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Converteert naar String met de overschreven ToString() methode |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Converteert naar String met opgegeven formaat |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converteert naar String met opgegeven formaat |

### Zie ook

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
