---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Spara alternativ för att exportera dokument till bild."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Spara alternativ för att exportera dokument till bild.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initierar en ny instans av ExportAsImageSaveOptions-klassen med standardvärden. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initierar en ny instans av ExportAsImageSaveOptions-klassen med specificerat filformat. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Hämtar eller anger dokumentsidnummer för export. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Hämtar eller anger dokumentsidnummer för export. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Flagga för att exportera varje sida. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flagga för att exportera varje sida. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Alternativ för att ange vilka sidor som ska signeras. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Alternativ för att ange vilka sidor som ska signeras. |
|
|  | [getPageColumns()](#getPageColumns--) | Hämtar eller anger antal kolumner för exporterade bilder. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Hämtar eller anger antal kolumner för exporterade bilder. |
|
|  | [getBorder()](#getBorder--) | Hämtar eller anger bildramens inställningar. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Hämtar eller anger bildramens inställningar. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Placera dokumentsidor på olika ramar i en Tiff-bild. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Placera dokumentsidor på olika ramar i en Tiff-bild. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initierar en ny instans av ExportAsImageSaveOptions-klassen med standardvärden.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initierar en ny instans av ExportAsImageSaveOptions-klassen med specificerat filformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafilformat för bild. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Hämtar eller anger dokumentsidnummer för export.
Minimalt värde är 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Hämtar eller anger dokumentsidnummer för export.
Minimalt värde är 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flagga för att exportera varje sida.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flagga för att exportera varje sida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Alternativ för att ange vilka sidor som ska signeras.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Alternativ för att ange vilka sidor som ska signeras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Hämtar eller anger antal kolumner för exporterade bilder.
Använd den här egenskapen om du behöver placera bilder i rad.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Hämtar eller anger antal kolumner för exporterade bilder.
Använd den här egenskapen om du behöver placera bilder i rad.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Hämtar eller anger bildraminställningarna. Som standard är detta värde inte angivet.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Hämtar eller anger bildraminställningarna. Som standard är detta värde inte angivet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Placera dokumentsidor på olika ramar i en Tiff-bild.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Placera dokumentsidor på olika ramar i en Tiff-bild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
