---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslaanopties voor het exporteren van documenten naar afbeelding."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Opslaanopties voor het exporteren van documenten naar afbeelding.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initialiseert een nieuw exemplaar van de ExportAsImageSaveOptions-klasse met standaardwaarden. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initialiseert een nieuw exemplaar van de ExportAsImageSaveOptions-klasse met het opgegeven bestandsformaat. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Haalt op of stelt het paginanummer van het document in voor export. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Haalt op of stelt het paginanummer van het document in voor export. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Vlag om elke pagina te exporteren. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Vlag om elke pagina te exporteren. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opties om de te ondertekenen pagina's op te geven. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opties om de te ondertekenen pagina's op te geven. |
|
|  | [getPageColumns()](#getPageColumns--) | Haalt op of stelt het aantal kolommen in voor geëxporteerde afbeeldingen. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Haalt op of stelt het aantal kolommen in voor geëxporteerde afbeeldingen. |
|
|  | [getBorder()](#getBorder--) | Haalt op of stelt de instellingen voor de afbeeldingsrand in. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Haalt op of stelt de instellingen voor de afbeeldingsrand in. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Plaats documentpagina's op verschillende frames in een Tiff-afbeelding. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Plaats documentpagina's op verschillende frames in een Tiff-afbeelding. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initialiseert een nieuw exemplaar van de ExportAsImageSaveOptions-klasse met standaardwaarden.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initialiseert een nieuw exemplaar van de ExportAsImageSaveOptions-klasse met het opgegeven bestandsformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoer afbeeldingsbestandformaat. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Haalt op of stelt het paginanummer van het document in voor export.
Minimale waarde is 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Haalt op of stelt het paginanummer van het document in voor export.
Minimale waarde is 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Vlag om elke pagina te exporteren.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Vlag om elke pagina te exporteren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opties om de te ondertekenen pagina's op te geven.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opties om de te ondertekenen pagina's op te geven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Haalt op of stelt het aantal kolommen in voor geëxporteerde afbeeldingen.
Gebruik deze eigenschap als u afbeeldingen in een rij wilt plaatsen.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Haalt op of stelt het aantal kolommen in voor geëxporteerde afbeeldingen.
Gebruik deze eigenschap als u afbeeldingen in een rij wilt plaatsen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Haalt of stelt de instellingen voor de afbeeldingsrand in. Standaard is deze waarde niet ingesteld.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Haalt of stelt de instellingen voor de afbeeldingsrand in. Standaard is deze waarde niet ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Plaats documentpagina's op verschillende frames in een Tiff-afbeelding.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Plaats documentpagina's op verschillende frames in een Tiff-afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
