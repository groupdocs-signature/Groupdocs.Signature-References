---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Bildsignaturoptionen dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Stellt die Bildsignaturoptionen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit Standardwerten. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit einer Bilddatei. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit einem Bild-Stream. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Liest oder setzt den Dateipfad des Signaturbildes. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Liest oder setzt den Dateipfad des Signaturbildes. |
|
|  | [getImageStream()](#getImageStream--) | Liest oder setzt den Signaturbild-Stream. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Liest oder setzt den Signaturbild-Stream. |
|
|  | [getLeft()](#getLeft--) | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Breite der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozent oder Millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Breite der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozent oder Millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Höhe der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozent oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Höhe der Signatur auf der Dokumentseite in Messwerten |
(Pixel, Prozent oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Left und Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Left und Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Width und Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Width und Height. |
|
|  | [getStretch()](#getStretch--) | Dehnungsmodus auf der Dokumentseite. |
|
|  | [setStretch(int value)](#setStretch-int-) | Dehnungsmodus auf der Dokumentseite. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
|
|  | [getMargin()](#getMargin--) | Liest oder setzt den Abstand zwischen Signatur- und Dokumentkanten. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Liest oder setzt den Abstand zwischen Signatur- und Dokumentkanten. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Liest oder setzt die Messart (Pixel, Prozent oder Millimeter) für den Rand. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Liest oder setzt die Messart (Pixel, Prozent oder Millimeter) für den Rand. |
|
|  | [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). |
|
|  | [getShapePosition()](#getShapePosition--) | Definiert, wo die Form im Dokumentlayout dargestellt werden soll |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definiert, wo die Form im Dokumentlayout dargestellt werden soll |
|
|  | [getRectangle()](#getRectangle--) | Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. |
|
|  | [getBorder()](#getBorder--) | Grenzeneinstellungen festlegen |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Grenzeneinstellungen festlegen |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Erstellt eine neue Instanz der Klasse ImageSignOptions mit vordefiniertem Bild aus Base64. |
|
|  | [dispose()](#dispose--) | Löscht interne Ressourcen |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit Standardwerten.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit einer Bilddatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Bilddateipfad |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Initialisiert eine neue Instanz der ImageSignOptions-Klasse mit einem Bild-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Bildstrom |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Liest oder setzt den Dateipfad des Signaturbildes.
Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Liest oder setzt den Dateipfad des Signaturbildes.
Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Liest oder setzt den Signaturbild-Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageGuid verwendet.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Liest oder setzt den Signaturbild-Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageGuid verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Linke X‑Position der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funktioniert, wenn die horizontale Ausrichtung nicht angegeben ist).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Linke X‑Position der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funktioniert, wenn die horizontale Ausrichtung nicht angegeben ist).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozente oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Breite der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozent oder Millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Breite der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozent oder Millimeter [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höhe der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozent oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höhe der Signatur auf der Dokumentseite in Messwerten
(Pixel, Prozent oder Millimeter siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Left und Top.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Left und Top.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Width und Height.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Messart (Pixel, Prozent oder Millimeter) für die Eigenschaften Width und Height.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Dehnungsmodus auf der Dokumentseite.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Dehnungsmodus auf der Dokumentseite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Horizontale Ausrichtung der Signatur auf der Dokumentseite.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Horizontale Ausrichtung der Signatur auf der Dokumentseite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Vertikale Ausrichtung der Signatur auf der Dokumentseite.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Vertikale Ausrichtung der Signatur auf der Dokumentseite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Liest oder setzt den Abstand zwischen Signatur- und Dokumentkanten.
(funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben sind).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Liest oder setzt den Abstand zwischen Signatur- und Dokumentkanten.
(funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben sind).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Liest oder setzt die Messart (Pixel, Prozent oder Millimeter) für den Rand.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Liest oder setzt die Messart (Pixel, Prozent oder Millimeter) für den Rand.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). Standardwert ist 0 (undurchsichtig).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). Standardwert ist 0 (undurchsichtig).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definiert, wo die Form im Dokumentlayout dargestellt werden soll


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definiert, wo die Form im Dokumentlayout dargestellt werden soll


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rechteck des Bereichs, in dem das Bild im Dokument platziert wird.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Grenzeneinstellungen festlegen


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Grenzeneinstellungen festlegen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Erstellt eine neue Instanz der Klasse ImageSignOptions mit vordefiniertem Bild aus Base64.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | base64Content | java.lang.String | Bildinhalt im Base64-String-Format |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Löscht interne Ressourcen


