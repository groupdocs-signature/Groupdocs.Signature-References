---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer zoekopties voor afbeeldinghandtekeningen."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Geeft weer zoekopties voor afbeeldinghandtekeningen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Initialiseert een nieuw exemplaar van de ImageSearchOptions‑klasse met standaardwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Haalt op of stelt de vlag in om de afbeeldingsinhoud van de handtekening op de documentpagina te verkrijgen. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Haalt op of stelt de vlag in om de afbeeldingsinhoud van de handtekening op de documentpagina te verkrijgen. |
|
|  | [getMinContentSize()](#getMinContentSize--) | Voor een niet‑nulwaarde geeft deze vlag de minimale grootte van afbeeldingen voor zoekcriteria op. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | Voor een niet‑nulwaarde geeft deze vlag de minimale grootte van afbeeldingen voor zoekcriteria op. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | Voor een niet‑nulwaarde geeft deze vlag de maximale grootte van afbeeldingen voor zoekcriteria op. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | Voor een niet‑nulwaarde geeft deze vlag de maximale grootte van afbeeldingen voor zoekcriteria op. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specificeert het bestandstype van de geretourneerde inhoud van de afbeeldinghandtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specificeert het bestandstype van de geretourneerde inhoud van de afbeeldinghandtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Initialiseert een nieuw exemplaar van de ImageSearchOptions‑klasse met standaardwaarden.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Haalt op of stelt de vlag in om de afbeeldingsinhoud van de handtekening op de documentpagina te verkrijgen.
Als deze vlag op true wordt gezet, behoudt de inhoud van de afbeeldinghandtekening de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Haalt op of stelt de vlag in om de afbeeldingsinhoud van de handtekening op de documentpagina te verkrijgen.
Als deze vlag op true wordt gezet, behoudt de inhoud van de afbeeldinghandtekening de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Voor een niet‑nulwaarde geeft deze vlag de minimale grootte van afbeeldingen voor zoekcriteria op.
Standaard is deze vlag ingesteld op nul en heeft geen invloed op het zoekresultaat.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Voor een niet‑nulwaarde geeft deze vlag de minimale grootte van afbeeldingen voor zoekcriteria op.
Standaard is deze vlag ingesteld op nul en heeft geen invloed op het zoekresultaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Voor een niet‑nulwaarde geeft deze vlag de maximale grootte van afbeeldingen voor zoekcriteria op.
Standaard is deze vlag ingesteld op nul en heeft geen invloed op het zoekresultaat.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Voor een niet‑nulwaarde geeft deze vlag de maximale grootte van afbeeldingen voor zoekcriteria op.
Standaard is deze vlag ingesteld op nul en heeft geen invloed op het zoekresultaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specificeert het bestandstype van de geretourneerde inhoud van de afbeeldinghandtekening wanneer de ReturnContent‑eigenschap is ingeschakeld.
Standaard is deze ingesteld op Null. Dat betekent dat de afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
ImageSignature.Format

Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de afbeeldingsinhoud in het oorspronkelijke formaat geretourneerd.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specificeert het bestandstype van de geretourneerde inhoud van de afbeeldinghandtekening wanneer de ReturnContent‑eigenschap is ingeschakeld.
Standaard is deze ingesteld op Null. Dat betekent dat de afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
ImageSignature.Format

Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de afbeeldingsinhoud in het oorspronkelijke formaat geretourneerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

