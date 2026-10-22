---
title: "MetadataSignatur"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Innehåller egenskaper för metadata‑signatur."
type: docs
weight: 780
url: /sv/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Innehåller egenskaper för metadata‑signatur.

```csharp
public abstract class MetadataSignature : BaseSignature
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Hämta eller ange signaturens skapandedatum. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Hämtar eller anger implementation av [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-gränssnittet för att koda och avkoda signaturens Value-egenskaper. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Hämta flaggan som indikerar om denna signatur har raderats från dokumentet. Denna egenskap används endast för dokumenthistorikloggposter för att behålla listan över raderade signaturer. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Anger signaturens höjd. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Hämta eller ange flagga för att indikera om denna komponent är en Signature eller dokumentinnehåll. Denna egenskap används med Update-metoden för att sätta element som signatur (true) eller dokumentelement (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Anger signaturens vänstra position. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Hämta eller ange signaturens ändringsdatum. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Anger unikt metadata-namn. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Anger sidan som signaturen hittades på. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unik signaturidentifierare för att modifiera signatur i dokumentet via Update- eller Delete-metoder. Denna egenskap sätts automatiskt efter att Sign- eller Search-metoden har anropats. Om denna egenskap sparades tidigare kan den sättas manuellt för att manipulera signaturen. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Anger signaturens typ. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Anger signaturens övre position. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Anger metadata-värdetyp. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Anger metadata-objekt. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Anger signaturens bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Klona Metadata Signature-instans. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Klona Metadata Signatur-instans med givet värde. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Hämta objekt från Metadata Signature Value vid deserialisering. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Hämta objekt från Metadata Signature Text vid deserialisering. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Åsidosätter GetHashCode-metoden |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konverterar till boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Konverterar till DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konverterar till DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Konverterar till Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konverterar till Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Konverterar till Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Konverterar till Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Konverterar till integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Konverterar till float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konverterar till float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Konverterar till String med överskuggad ToString()-metod |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Konverterar till String med angivet format |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konverterar till String med angivet format |

### Se även

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
