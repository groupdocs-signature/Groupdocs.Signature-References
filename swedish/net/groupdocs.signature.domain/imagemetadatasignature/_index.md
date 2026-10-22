---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Innehåller egenskaper för bildmetadata‑signatur."
type: docs
weight: 740
url: /sv/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Innehåller egenskaper för bildmetadata‑signatur.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Skapar Image Metadata Signature med Id och värde |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ange signaturens skapandedatum. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Hämtar eller anger implementation av [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-gränssnittet för att koda och avkoda signaturens Value-egenskaper. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur har raderats från dokumentet. Denna egenskap används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Skrivskyddat värde för att hämta beskrivning för standard Image Metadata signature |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Identifieraren för Image Metadata signature. Se ImageMetadataSignatures class som innehåller standard Signature med fördefinierat Id värde. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är en Signature eller dokumentinnehåll. Denna egenskap används med Update-metoden för att sätta element som signatur (true) eller dokumentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ange signaturens ändringsdatum. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Anger unikt metadata-namn. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidan som signaturen hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att modifiera signatur i dokumentet via Update- eller Delete-metoder. Denna egenskap sätts automatiskt efter att Sign- eller Search-metoden har anropats. Om denna egenskap sparades tidigare kan den sättas manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger signaturens typ. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Skrivskyddat värde för att hämta storlek på Metadata value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens övre position. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Anger metadata-värdetyp. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Anger metadata-objekt. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Klona Metadata Signature-instans. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Klona Image Metadata Signature instans med angivet värde. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Hämta objekt från Metadata Signature Value vid deserialisering. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Hämta objekt från Metadata Signature Text vid deserialisering. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Åsidosätter GetHashCode-metoden |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Konverterar till boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Konverterar till DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konverterar till DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Konverterar till Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konverterar till Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Konverterar till Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Konverterar till Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Konverterar till integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Konverterar till long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Konverterar till float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konverterar till float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Konverterar till String med överskuggad ToString()-metod |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Konverterar till String med angivet format |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konverterar till String med angivet format |

### Se även

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
