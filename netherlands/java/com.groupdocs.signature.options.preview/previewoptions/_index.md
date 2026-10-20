---
title: "PreviewOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt documentvoorvertoningsopties voor."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Stelt documentvoorvertoningsopties voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initialiseert PreviewOptions-object. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initialiseert PreviewOptions-object. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initialiseert PreviewOptions-object. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Haalt op of stelt de breedte van preview-afbeeldingen in. |
|
|  | [setWidth(int value)](#setWidth-int-) | Haalt op of stelt de breedte van preview-afbeeldingen in. |
|
|  | [getHeight()](#getHeight--) | Haalt op of stelt de hoogte van preview-afbeeldingen in. |
|
|  | [setHeight(int value)](#setHeight-int-) | Haalt op of stelt de hoogte van preview-afbeeldingen in. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Haalt op of stelt de paginanummers van preview-afbeeldingen in. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Haalt op of stelt de paginanummers van preview-afbeeldingen in. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Haalt op of stelt het formaat van voorbeeldafbeeldingen in. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Haalt op of stelt het formaat van voorbeeldafbeeldingen in. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Haalt op of stelt de vlag in om handtekeningen te verbergen op preview-afbeeldingen van pagina's. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Haalt op of stelt de vlag in om handtekeningen te verbergen op preview-afbeeldingen van pagina's. |
|
|  | [getResolution()](#getResolution--) | Haalt de resolutie van de preview-afbeeldingen op in DPI (dots per inch). |
|
|  | [setResolution(int value)](#setResolution-int-) | Stelt de resolutie van de preview-afbeeldingen in in DPI (dots per inch). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initialiseert PreviewOptions-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Interface die de methode definieert om een uitvoer-pagina-voorbeeld-stream te maken. |
|
|  | pageNumbers | int[] | Gewenste paginanummers |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initialiseert PreviewOptions-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Interface die de methode definieert om een uitvoer-pagina-voorbeeld-stream te maken. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initialiseert PreviewOptions-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Pad naar uitvoerbestand. |
|
|  | pageNumbers | int[] | Gewenste paginanummers |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt op of stelt de breedte van preview-afbeeldingen in.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Haalt op of stelt de breedte van preview-afbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt op of stelt de hoogte van preview-afbeeldingen in.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Haalt op of stelt de hoogte van preview-afbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Haalt op of stelt de paginanummers van preview-afbeeldingen in.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Haalt op of stelt de paginanummers van preview-afbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Haalt op of stelt het formaat van voorbeeldafbeeldingen in.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Haalt op of stelt het formaat van voorbeeldafbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Haalt op of stelt de vlag in om handtekeningen te verbergen op preview-afbeeldingen van pagina's.
Alleen handtekeningen die gemarkeerd zijn als IsSignature worden verborgen in de gegenereerde documentpagina-afbeelding.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Haalt op of stelt de vlag in om handtekeningen te verbergen op preview-afbeeldingen van pagina's.
Alleen handtekeningen die gemarkeerd zijn als IsSignature worden verborgen in de gegenereerde documentpagina-afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Haalt de resolutie van de preview-afbeeldingen op in DPI (dots per inch).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Stelt de resolutie van de preview-afbeeldingen in in DPI (dots per inch).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

