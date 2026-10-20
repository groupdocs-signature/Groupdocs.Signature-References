---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de afbeelding-handtekeningopties."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Vertegenwoordigt de afbeelding-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met standaardwaarden. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingsbestand. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingsstroom. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Haalt op of stelt het bestandspad van de handtekeningafbeelding in. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Haalt op of stelt het bestandspad van de handtekeningafbeelding in. |
|
|  | [getImageStream()](#getImageStream--) | Haalt op of stelt de handtekeningafbeeldingsstroom in. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Haalt op of stelt de handtekeningafbeeldingsstroom in. |
|
|  | [getLeft()](#getLeft--) | Linker X-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Linker X-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Breedte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Breedte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Hoogte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Hoogte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Meettype (pixels, procenten of millimeters) voor de eigenschappen Left en Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Meettype (pixels, procenten of millimeters) voor de eigenschappen Left en Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
|
|  | [getStretch()](#getStretch--) | Rekmodus op Document Page. |
|
|  | [setStretch(int value)](#setStretch-int-) | Rekmodus op Document Page. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Rotatiehoek van handtekening op documentpagina (met de klok mee). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Rotatiehoek van handtekening op documentpagina (met de klok mee). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Horizontale uitlijning van handtekening op documentpagina. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horizontale uitlijning van handtekening op documentpagina. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Verticale uitlijning van handtekening op documentpagina. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Verticale uitlijning van handtekening op documentpagina. |
|
|  | [getMargin()](#getMargin--) | Haalt op of stelt de ruimte tussen Sign en Document randen in. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Haalt op of stelt de ruimte tussen Sign en Document randen in. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Haalt op of stelt het meettype (pixels, procenten of millimeters) voor Margin in. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Haalt op of stelt het meettype (pixels, procenten of millimeters) voor Margin in. |
|
|  | [getTransparency()](#getTransparency--) | Haalt op of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Haalt op of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). |
|
|  | [getShapePosition()](#getShapePosition--) | Definieert waar de vorm moet worden weergegeven in de documentlay-out. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definieert waar de vorm moet worden weergegeven in de documentlay-out. |
|
|  | [getRectangle()](#getRectangle--) | Rechthoek van het gebied om de afbeelding op het document te plaatsen. |
|
|  | [getBorder()](#getBorder--) | Specificeer randinstellingen |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specificeer randinstellingen |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Maakt een nieuw exemplaar van de **ImageSignOptions** klasse met een vooraf gedefinieerde afbeelding uit Base64. |
|
|  | [dispose()](#dispose--) | Verwijdert interne bronnen |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met standaardwaarden.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingsbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Afbeeldingsbestandspad |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingsstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Afbeeldingsstroom |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Haalt op of stelt het bestandspad van de handtekeningafbeelding in.
Deze eigenschap wordt alleen gebruikt als ImageStream niet is opgegeven.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Haalt op of stelt het bestandspad van de handtekeningafbeelding in.
Deze eigenschap wordt alleen gebruikt als ImageStream niet is opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Haalt op of stelt de handtekeningafbeeldingsstroom in.
Als deze eigenschap is gespecificeerd, wordt deze altijd gebruikt in plaats van ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Haalt op of stelt de handtekeningafbeeldingsstroom in.
Als deze eigenschap is gespecificeerd, wordt deze altijd gebruikt in plaats van ImageGuid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Linker X-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(werkt als horizontale uitlijning niet is gespecificeerd).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Linker X-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(werkt als horizontale uitlijning niet is gespecificeerd).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(werkt als verticale uitlijning niet is gespecificeerd).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(werkt als verticale uitlijning niet is gespecificeerd).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Breedte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Breedte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hoogte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hoogte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Meettype (pixels, procenten of millimeters) voor de eigenschappen Left en Top.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Meettype (pixels, procenten of millimeters) voor de eigenschappen Left en Top.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Rekmodus op Document Page.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Rekmodus op Document Page.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Rotatiehoek van handtekening op documentpagina (met de klok mee).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Rotatiehoek van handtekening op documentpagina (met de klok mee).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Horizontale uitlijning van handtekening op documentpagina.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Horizontale uitlijning van handtekening op documentpagina.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Verticale uitlijning van handtekening op documentpagina.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Verticale uitlijning van handtekening op documentpagina.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Haalt op of stelt de ruimte tussen Sign en Document randen in.
(werkt ENKEL als horizontale of verticale uitlijning is gespecificeerd).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Haalt op of stelt de ruimte tussen Sign en Document randen in.
(werkt ENKEL als horizontale of verticale uitlijning is gespecificeerd).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Haalt op of stelt het meettype (pixels, procenten of millimeters) voor Margin in.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Haalt op of stelt het meettype (pixels, procenten of millimeters) voor Margin in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Haalt op of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). Standaardwaarde is 0 (ondoorzichtig).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Haalt op of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). Standaardwaarde is 0 (ondoorzichtig).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definieert waar de vorm moet worden weergegeven in de documentlay-out.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definieert waar de vorm moet worden weergegeven in de documentlay-out.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rechthoek van het gebied om de afbeelding op het document te plaatsen.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Specificeer randinstellingen


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Specificeer randinstellingen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Maakt een nieuw exemplaar van de **ImageSignOptions** klasse met een vooraf gedefinieerde afbeelding uit Base64.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | base64Content | java.lang.String | Afbeeldingsinhoud in Base64 tekenreeksformaat |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert interne bronnen


