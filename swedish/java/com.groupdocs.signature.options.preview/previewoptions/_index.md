---
title: "PreviewOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar alternativ för dokumentförhandsgranskning."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Representerar alternativ för dokumentförhandsgranskning.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initierar PreviewOptions-objektet. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initierar PreviewOptions-objektet. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initierar PreviewOptions-objektet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar eller anger bredd på förhandsgranskningsbilder. |
|
|  | [setWidth(int value)](#setWidth-int-) | Hämtar eller anger bredd på förhandsgranskningsbilder. |
|
|  | [getHeight()](#getHeight--) | Hämtar eller anger höjd på förhandsgranskningsbilder. |
|
|  | [setHeight(int value)](#setHeight-int-) | Hämtar eller anger höjd på förhandsgranskningsbilder. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Hämtar eller anger sidnummer för förhandsgranskningsbilder. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Hämtar eller anger sidnummer för förhandsgranskningsbilder. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Hämtar eller anger format för förhandsgranskningsbilder. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Hämtar eller anger format för förhandsgranskningsbilder. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Hämtar eller anger flagga för att dölja signaturer från förhandsgranskningsbild av sidan. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Hämtar eller anger flagga för att dölja signaturer från förhandsgranskningsbild av sidan. |
|
|  | [getResolution()](#getResolution--) | Hämtar upplösningen för förhandsgranskningsbilder i DPI (punkter per tum). |
|
|  | [setResolution(int value)](#setResolution-int-) | Anger upplösningen för förhandsgranskningsbilder i DPI (punkter per tum). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initierar PreviewOptions-objektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Gränssnitt som definierar en metod för att skapa en förhandsgranskningsström för utskriftsidan. |
|
|  | sidnummer | int[] | Önskade sidnummer |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initierar PreviewOptions-objektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Gränssnitt som definierar en metod för att skapa en förhandsgranskningsström för utskriftsidan. |
|
| sidnummer | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initierar PreviewOptions-objektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filSökvägsformat | java.lang.String | Sökväg till utdatafil. |
|
|  | sidnummer | int[] | Önskade sidnummer |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar eller anger bredd på förhandsgranskningsbilder.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Hämtar eller anger bredd på förhandsgranskningsbilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar eller anger höjd på förhandsgranskningsbilder.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hämtar eller anger höjd på förhandsgranskningsbilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Hämtar eller anger sidnummer för förhandsgranskningsbilder.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Hämtar eller anger sidnummer för förhandsgranskningsbilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Hämtar eller anger format för förhandsgranskningsbilder.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Hämtar eller anger format för förhandsgranskningsbilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Hämtar eller anger flagga för att dölja signaturer från förhandsgranskningsbild av sidan.
Endast signaturer som är markerade som IsSignature kommer att döljas från den genererade dokumentets sidavbild.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Hämtar eller anger flagga för att dölja signaturer från förhandsgranskningsbild av sidan.
Endast signaturer som är markerade som IsSignature kommer att döljas från den genererade dokumentets sidavbild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Hämtar upplösningen för förhandsgranskningsbilder i DPI (punkter per tum).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Anger upplösningen för förhandsgranskningsbilder i DPI (punkter per tum).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

