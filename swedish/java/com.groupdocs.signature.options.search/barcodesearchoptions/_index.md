---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar abstrakta sökalternativ för streckkodssignaturer."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Representerar abstrakta sökalternativ för streckkodssignaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Initierar en ny instans av klassen SearchBarcodeOptions med standardvärden. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initierar en ny instans av klassen SearchBarcodeOptions med kodningstypvärde. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Initierar en ny instans av klassen SearchBarcodeOptions med kodningstyp- och textvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Anger egenskapen Encode Type för att söka streckkoder. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Anger egenskapen Encode Type för att söka streckkoder. |
|
|  | [getText()](#getText--) | Anger streckkodssignaturtext om den ska sökas och matchas. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Anger streckkodssignaturtext om den ska sökas och matchas. |
|
|  | [getMatchType()](#getMatchType--) | Hämtar eller anger sökning av Barcode-textens matchningstyp. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Hämtar eller anger sökning av Barcode-textens matchningstyp. |
|
|  | [getReturnContent()](#getReturnContent--) | Hämtar eller anger flagga för att hämta Barcode-bildinnehållet i signaturen på dokumentsidan. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Hämtar eller anger flagga för att hämta Barcode-bildinnehållet i signaturen på dokumentsidan. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Initierar en ny instans av klassen SearchBarcodeOptions med standardvärden.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Initierar en ny instans av klassen SearchBarcodeOptions med kodningstypvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Anger Barcode-kodningstyp. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Initierar en ny instans av klassen SearchBarcodeOptions med kodningstyp- och textvärden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Anger Barcode-kodningstyp. |
|
|  | text | java.lang.String | Ange text för Barcode-signatur. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Anger egenskapen Encode Type för att söka streckkoder.
Om detta värde inte är angivet, utförs sökningen för alla stödda Barcode-typer.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Anger egenskapen Encode Type för att söka streckkoder.
Om detta värde inte är angivet, utförs sökningen för alla stödda Barcode-typer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Anger streckkodssignaturtext om den ska sökas och matchas.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Anger streckkodssignaturtext om den ska sökas och matchas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Hämtar eller anger sökning av Barcode-textens matchningstyp. Den används endast när Text-egenskapen är angiven.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Hämtar eller anger sökning av Barcode-textens matchningstyp. Den används endast när Text-egenskapen är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Hämtar eller anger flagga för att hämta Barcode-bildinnehållet i signaturen på dokumentsidan.
Om denna flagga är satt till true kommer Barcode-signaturens bildinnehåll att behålla rå bilddata i det begärda formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Hämtar eller anger flagga för att hämta Barcode-bildinnehållet i signaturen på dokumentsidan.
Om denna flagga är satt till true kommer Barcode-signaturens bildinnehåll att behålla rå bilddata i det begärda formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att Barcode-bildinnehållet returneras i originalformat.
Detta bildformat anges på
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer Barcode‑bildinnehållet i .png‑format att returneras.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att Barcode-bildinnehållet returneras i originalformat.
Detta bildformat anges på
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer Barcode‑bildinnehållet i .png‑format att returneras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

