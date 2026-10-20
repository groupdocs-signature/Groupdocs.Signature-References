---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar sökalternativ för bildsignaturer."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Representerar sökalternativ för bildsignaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Initierar en ny instans av klassen ImageSearchOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Hämtar eller anger flagga för att fånga bildinnehållet i signaturen på dokumentsidan. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Hämtar eller anger flagga för att fånga bildinnehållet i signaturen på dokumentsidan. |
|
|  | [getMinContentSize()](#getMinContentSize--) | För ett icke‑nollvärde anger denna flagga minimal storlek på bilder för sökkriterier. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | För ett icke‑nollvärde anger denna flagga minimal storlek på bilder för sökkriterier. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | För ett icke‑nollvärde anger denna flagga maximal storlek på bilder för sökkriterier. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | För ett icke‑nollvärde anger denna flagga maximal storlek på bilder för sökkriterier. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Anger filtypen för det returnerade innehållet i bildsignaturen när egenskapen ReturnContent är aktiverad. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtypen för det returnerade innehållet i bildsignaturen när egenskapen ReturnContent är aktiverad. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Initierar en ny instans av klassen ImageSearchOptions med standardvärden.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Hämtar eller anger flagga för att fånga bildinnehållet i signaturen på dokumentsidan.
Om denna flagga är satt till true behåller bildsignaturens innehåll rå bilddata i det önskade formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Hämtar eller anger flagga för att fånga bildinnehållet i signaturen på dokumentsidan.
Om denna flagga är satt till true behåller bildsignaturens innehåll rå bilddata i det önskade formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


För ett icke‑nollvärde anger denna flagga minimal storlek på bilder för sökkriterier.
Som standard är denna flagga satt till noll och påverkar inte sökresultatet.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


För ett icke‑nollvärde anger denna flagga minimal storlek på bilder för sökkriterier.
Som standard är denna flagga satt till noll och påverkar inte sökresultatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


För ett icke‑nollvärde anger denna flagga maximal storlek på bilder för sökkriterier.
Som standard är denna flagga satt till noll och påverkar inte sökresultatet.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


För ett icke‑nollvärde anger denna flagga maximal storlek på bilder för sökkriterier.
Som standard är denna flagga satt till noll och påverkar inte sökresultatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Anger filtypen för det returnerade innehållet i bildsignaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att bildinnehållet returneras i originalformat.
Detta bildformat anges på
ImageSignature.Format

Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer bildinnehållet att returneras i originalformat.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Anger filtypen för det returnerade innehållet i bildsignaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att bildinnehållet returneras i originalformat.
Detta bildformat anges på
ImageSignature.Format

Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer bildinnehållet att returneras i originalformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

