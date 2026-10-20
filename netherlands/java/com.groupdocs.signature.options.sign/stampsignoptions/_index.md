---
title: "StampSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de stempel-handtekeningopties."
type: docs
weight: 17
url: /nl/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Vertegenwoordigt de stempel-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Initialiseert een nieuw exemplaar van de StampSignOptions‑klasse met standaardwaarden. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Initialiseert een nieuw exemplaar van de StampSignOptions‑klasse met uitlijningsopties. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getStampType()](#getStampType--) | Haalt het stempeltype op of stelt dit in. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Haalt het stempeltype op of stelt dit in. |
|
|  | [getOuterLines()](#getOuterLines--) | Lijst van buitenste lijnen weergegeven als concentrische cirkels. |
|
|  | [getInnerLines()](#getInnerLines--) | Lijst van binnenste lijnen weergegeven als een reeks rechthoeken. |
|
|  | [getBackground()](#getBackground--) | Haalt de achtergrond van de stempel op of stelt deze in. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Haalt de achtergrond van de stempel op of stelt deze in. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt de achtergrondkleur van de handtekening in. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Haalt op of stelt de achtergrondkleur van de handtekening in. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Haalt de achtergrondkwast van de handtekening op of stelt deze in. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Haalt de achtergrondkwast van de handtekening op of stelt deze in. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Haalt op of stelt het bijsnijdtype van de achtergrondkleur van de handtekening in. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Haalt op of stelt het bijsnijdtype van de achtergrondkleur van de handtekening in. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Haalt op of stelt het bijsnijdtype van de achtergrondafbeelding van de handtekening in. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Haalt op of stelt het bijsnijdtype van de achtergrondafbeelding van de handtekening in. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Initialiseert een nieuw exemplaar van de StampSignOptions‑klasse met standaardwaarden.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Initialiseert een nieuw exemplaar van de StampSignOptions‑klasse met uitlijningsopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | links | int | De x-coördinaat van de linkerbovenrand van de Stempelhandtekening |
|
|  | boven | int | De y-coördinaat van de linkerbovenrand van de Stempelhandtekening |
|
|  | breedte | int | De breedte van de Stempelhandtekening |
|
|  | hoogte | int | De hoogte van de Stempelhandtekening |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Haalt het stempeltype op of stelt dit in.
Standaardwaarde is Rond.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Haalt het stempeltype op of stelt dit in.
Standaardwaarde is Rond.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Lijst van buitenste lijnen weergegeven als concentrische cirkels.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Lijst van binnenste lijnen weergegeven als een reeks rechthoeken.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Haalt de achtergrond van de stempel op of stelt deze in.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Haalt de achtergrond van de stempel op of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Haalt op of stelt de achtergrondkleur van de handtekening in.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Haalt op of stelt de achtergrondkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Haalt op of stelt de achtergrondkwast van de handtekening in. Standaardwaarde is null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Haalt op of stelt de achtergrondkwast van de handtekening in. Standaardwaarde is null.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Haalt op of stelt het bijsnijdtype van de achtergrondkleur van de handtekening in.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Haalt op of stelt het bijsnijdtype van de achtergrondkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Haalt op of stelt het bijsnijdtype van de achtergrondafbeelding van de handtekening in.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Haalt op of stelt het bijsnijdtype van de achtergrondafbeelding van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie


**Returns:**
java.lang.String -
