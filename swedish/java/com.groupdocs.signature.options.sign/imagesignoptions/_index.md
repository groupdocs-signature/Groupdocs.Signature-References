---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Bild‑signaturalternativen."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Representerar Bild‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Initierar en ny instans av ImageSignOptions-klassen med standardvärden. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Initierar en ny instans av ImageSignOptions-klassen med bildfil. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Initierar en ny instans av ImageSignOptions-klassen med bildström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Hämtar eller anger sökvägen till signaturens bildfil. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Hämtar eller anger sökvägen till signaturens bildfil. |
|
|  | [getImageStream()](#getImageStream--) | Hämtar eller anger signaturens bildström. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Hämtar eller anger signaturens bildström. |
|
|  | [getLeft()](#getLeft--) | Vänster X-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Vänster X-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Övre Y-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Övre Y-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Bredd för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Bredd för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Höjd på signatur på dokumentsida i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Höjd på signatur på dokumentsida i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Måtttyp (pixlar, procent eller millimeter) för vänster- och topp‑egenskaper. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Måtttyp (pixlar, procent eller millimeter) för vänster- och topp‑egenskaper. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Måtttyp (pixlar, procent eller millimeter) för bredd‑ och höjd‑egenskaper. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Måtttyp (pixlar, procent eller millimeter) för bredd‑ och höjd‑egenskaper. |
|
|  | [getStretch()](#getStretch--) | Sträckningsläge på dokumentsida. |
|
|  | [setStretch(int value)](#setStretch-int-) | Sträckningsläge på dokumentsida. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Rotationsvinkel för signatur på dokumentsida (medurs). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Rotationsvinkel för signatur på dokumentsida (medurs). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Horisontell justering av signatur på dokumentsida. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horisontell justering av signatur på dokumentsida. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Vertikal justering av signatur på dokumentsida. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Vertikal justering av signatur på dokumentsida. |
|
|  | [getMargin()](#getMargin--) | Hämtar eller anger avståndet mellan Sign och dokumentkanter. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Hämtar eller anger avståndet mellan Sign och dokumentkanter. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Hämtar eller anger måtttyp (pixlar, procent eller millimeter) för marginal. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Hämtar eller anger måtttyp (pixlar, procent eller millimeter) för marginal. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (klar)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (klar)). |
|
|  | [getShapePosition()](#getShapePosition--) | Definierar var formen ska presenteras i dokumentlayouten. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definierar var formen ska presenteras i dokumentlayouten. |
|
|  | [getRectangle()](#getRectangle--) | Rektangel för område där bilden ska placeras i dokumentet. |
|
|  | [getBorder()](#getBorder--) | Ange kantinställningar. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Ange kantinställningar. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Skapar en ny instans av klassen ImageSignOptions med fördefinierad bild från Base64. |
|
|  | [dispose()](#dispose--) | Rensar interna resurser |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Initierar en ny instans av ImageSignOptions-klassen med standardvärden.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Initierar en ny instans av ImageSignOptions-klassen med bildfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Sökväg till bildfil |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Initierar en ny instans av ImageSignOptions-klassen med bildström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Bildström |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Hämtar eller anger sökvägen till signaturens bildfil.
Denna egenskap används endast om ImageStream inte är angiven.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Hämtar eller anger sökvägen till signaturens bildfil.
Denna egenskap används endast om ImageStream inte är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Hämtar eller anger signaturens bildström.
Om denna egenskap är specificerad används den alltid istället för ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Hämtar eller anger signaturens bildström.
Om denna egenskap är specificerad används den alltid istället för ImageGuid.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Vänster X-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(fungerar om horisontell justering inte är specificerad).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Vänster X-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(fungerar om horisontell justering inte är specificerad).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Övre Y-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(fungerar om vertikal justering inte är specificerad).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Övre Y-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(fungerar om vertikal justering inte är specificerad).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bredd för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredd för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjd på signatur på dokumentsida i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjd på signatur på dokumentsida i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Måtttyp (pixlar, procent eller millimeter) för vänster- och topp‑egenskaper.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Måtttyp (pixlar, procent eller millimeter) för vänster- och topp‑egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Måtttyp (pixlar, procent eller millimeter) för bredd‑ och höjd‑egenskaper.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Måtttyp (pixlar, procent eller millimeter) för bredd‑ och höjd‑egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Sträckningsläge på dokumentsida.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Sträckningsläge på dokumentsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Rotationsvinkel för signatur på dokumentsida (medurs).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Rotationsvinkel för signatur på dokumentsida (medurs).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Horisontell justering av signatur på dokumentsida.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Horisontell justering av signatur på dokumentsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Vertikal justering av signatur på dokumentsida.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Vertikal justering av signatur på dokumentsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Hämtar eller anger avståndet mellan Sign och dokumentkanter.
(fungerar ENDAST om horisontell eller vertikal justering är specificerade).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Hämtar eller anger avståndet mellan Sign och dokumentkanter.
(fungerar ENDAST om horisontell eller vertikal justering är specificerade).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Hämtar eller anger måtttyp (pixlar, procent eller millimeter) för marginal.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Hämtar eller anger måtttyp (pixlar, procent eller millimeter) för marginal.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (klar)). Standardvärdet är 0 (opak).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (klar)). Standardvärdet är 0 (opak).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definierar var formen ska presenteras i dokumentlayouten.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definierar var formen ska presenteras i dokumentlayouten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rektangel för område där bilden ska placeras i dokumentet.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Ange kantinställningar.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Ange kantinställningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Skapar en ny instans av klassen ImageSignOptions med fördefinierad bild från Base64.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | base64Content | java.lang.String | Bildinnehåll i Base64-strängformat |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Rensar interna resurser


