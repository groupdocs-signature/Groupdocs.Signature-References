---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt abstracte zoekopties voor barcodehandtekeningen voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Stelt abstracte zoekopties voor barcodehandtekeningen voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met standaardwaarden. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met een encode-typwaarde. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met encode-typ- en tekstwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Specificeert de Encode Type-eigenschap om barcodes te zoeken. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Specificeert de Encode Type-eigenschap om barcodes te zoeken. |
|
|  | [getText()](#getText--) | Specificeert de barcode-handtekeningtekst als deze moet worden gezocht en overeenkomen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Specificeert de barcode-handtekeningtekst als deze moet worden gezocht en overeenkomen. |
|
|  | [getMatchType()](#getMatchType--) | Haalt op of stelt de barcode-tekst Match Type-zoekopdracht in. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Haalt op of stelt de barcode-tekst Match Type-zoekopdracht in. |
|
|  | [getReturnContent()](#getReturnContent--) | Haalt op of stelt de vlag in om de barcode-afbeeldingsinhoud van de handtekening op de documentpagina te pakken. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Haalt op of stelt de vlag in om de barcode-afbeeldingsinhoud van de handtekening op de documentpagina te pakken. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met standaardwaarden.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met een encode-typwaarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specificeert het barcode-encode type. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Initialiseert een nieuw exemplaar van de SearchBarcodeOptions-klasse met encode-typ- en tekstwaarden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specificeert het barcode-encode type. |
|
|  | tekst | java.lang.String | Stel de tekst van de barcodehandtekening in. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specificeert de Encode Type-eigenschap om barcodes te zoeken.
Als deze waarde niet is ingesteld, wordt gezocht naar alle ondersteunde barcode-typen.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Specificeert de Encode Type-eigenschap om barcodes te zoeken.
Als deze waarde niet is ingesteld, wordt gezocht naar alle ondersteunde barcode-typen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specificeert de barcode-handtekeningtekst als deze moet worden gezocht en overeenkomen.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specificeert de barcode-handtekeningtekst als deze moet worden gezocht en overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Haalt op of stelt de zoekopdracht voor barcode-tekst-matchtype in. Deze wordt alleen gebruikt wanneer de eigenschap Text is ingesteld.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Haalt op of stelt de zoekopdracht voor barcode-tekst-matchtype in. Deze wordt alleen gebruikt wanneer de eigenschap Text is ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Haalt op of stelt de vlag in om de barcode-afbeeldingsinhoud van de handtekening op de documentpagina te pakken.
Als deze vlag op true wordt gezet, behoudt de Barcode-handtekeningafbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Haalt op of stelt de vlag in om de barcode-afbeeldingsinhoud van de handtekening op de documentpagina te pakken.
Als deze vlag op true wordt gezet, behoudt de Barcode-handtekeningafbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld.
Standaard is het ingesteld op Null. Dat betekent dat de Barcode-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de Barcode-afbeeldingsinhoud in .png-formaat geretourneerd.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld.
Standaard is het ingesteld op Null. Dat betekent dat de Barcode-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de Barcode-afbeeldingsinhoud in .png-formaat geretourneerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

