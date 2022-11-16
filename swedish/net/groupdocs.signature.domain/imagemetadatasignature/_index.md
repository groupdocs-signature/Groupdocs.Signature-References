---
title: ImageMetadataSignature
second_title: GroupDocs.Signature för .NET API-referens
description: Innehåller signaturegenskaper för bildmetadata.
type: docs
weight: 550
url: /sv/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Innehåller signaturegenskaper för bildmetadata.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Skapar bildmetadatasignatur med Id och value |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ställ in datum för att skapa signaturen. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Får eller ställer in implementering av[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) gränssnitt för att koda och avkoda signaturvärdeegenskaper. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur togs bort från dokumentet. Den här egenskapen används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Skrivskyddat värde för att få beskrivning för standardbildmetadatasignatur |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Identifieraren för bildmetadatasignaturen. SeImageMetadataSignatures klass som innehåller standardsignatur med fördefinierat Id-värde. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är signatur eller dokumentinnehåll. Den här egenskapen används med uppdateringsmetoden för att ställa in element som signatur (true) eller dokumentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ställ in datum för signaturändring. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Anger unikt metadatanamn. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidsignaturen som hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att ändra signaturen i dokumentet över Uppdatera eller Ta bort metoder. Den här egenskapen kommer att ställas in automatiskt efter att Sign- eller Sökmetoden anropas. Om den här egenskapen sparades innan den kan ställas in manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger typen av signatur. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Skrivskyddat värde för att få storleken på Metadata value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens topposition. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Anger metadataobjekt. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clone Metadata Signatur-instans. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Klona bildmetadata Signaturinstans med givet värde. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturegenskaper |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Hämta objekt från Metadata Signature Value över deserialization. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Hämta objekt från Metadata Signature Text över deserialisering. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Åsidosätter GetHashCode method |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Konverteras till booleskt. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Konverteras till DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konverteras till DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Konverteras till decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konverteras till decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Konverteras till Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Konverteras till Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Konverteras till heltal. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Konverteras till lång. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Konverteras till flytande. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konverteras till flytande. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Konverterar till String med åsidosätt ToString() method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Konverterar till sträng med specificerat format |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konverterar till sträng med specificerat format |

### Se även

* class [MetadataSignature](../metadatasignature)
* namnutrymme [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
