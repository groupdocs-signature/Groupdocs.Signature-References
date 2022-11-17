---
title: MetadataSignature
second_title: GroupDocs.Signature för .NET API-referens
description: Innehåller metadatasignaturegenskaper.
type: docs
weight: 590
url: /sv/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Innehåller metadatasignaturegenskaper.

```csharp
public abstract class MetadataSignature : BaseSignature
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ställ in datum för att skapa signaturen. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Får eller ställer in implementering av[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) gränssnitt för att koda och avkoda signaturvärdeegenskaper. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur togs bort från dokumentet. Den här egenskapen används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är signatur eller dokumentinnehåll. Den här egenskapen används med uppdateringsmetoden för att ställa in element som signatur (true) eller dokumentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ställ in datum för signaturändring. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Anger unikt metadatanamn. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidsignaturen som hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att ändra signaturen i dokumentet över Uppdatera eller Ta bort metoder. Den här egenskapen kommer att ställas in automatiskt efter att Sign- eller Sökmetoden anropas. Om den här egenskapen sparades innan den kan ställas in manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger typen av signatur. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens topposition. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Anger metadataobjekt. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Clone Metadata Signatur-instans. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Clone Metadata Signatur-instans med givet värde. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturegenskaper |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Hämta objekt från Metadata Signature Value över deserialization. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Hämta objekt från Metadata Signature Text över deserialisering. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Åsidosätter GetHashCode method |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konverteras till booleskt. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Konverteras till DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konverteras till DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Konverteras till decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konverteras till decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Konverteras till Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Konverteras till Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Konverteras till heltal. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Konverteras till flytande. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konverteras till flytande. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Konverterar till String med åsidosätt ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Konverterar till sträng med specificerat format |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konverterar till sträng med specificerat format |

### Se även

* class [BaseSignature](../basesignature)
* namnutrymme [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
