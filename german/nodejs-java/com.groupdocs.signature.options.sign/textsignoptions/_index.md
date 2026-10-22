---
title: "TextSignOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Optionen für Textsignaturen dar."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Stellt die Optionen für Textsignaturen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Initialisiert eine neue Instanz der Klasse SignTextOptions mit Standardwerten. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse SignTextOptions mit Text. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeft()](#getLeft--) | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType‑Eigenschaft). |
| [setLeft(int value)](#setLeft-int-) | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType‑Eigenschaft). |
| [getTop()](#getTop--) | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType‑Eigenschaft). |
| [setTop(int value)](#setTop-int-) | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType‑Eigenschaft). |
| [getWidth()](#getWidth--) | Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft). |
| [setWidth(int value)](#setWidth-int-) | Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft). |
| [getHeight()](#getHeight--) | Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft). |
| [setHeight(int value)](#setHeight-int-) | Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [getStretch()](#getStretch--) | Dehnungsmodus auf der Dokumentseite. |
| [setStretch(int value)](#setStretch-int-) | Dehnungsmodus auf der Dokumentseite. |
| [getRotationAngle()](#getRotationAngle--) | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
| [getMargin()](#getMargin--) | Liest oder setzt den Abstand zwischen Signatur und Dokumentkanten. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Liest oder setzt den Abstand zwischen Signatur und Dokumentkanten. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Liest oder setzt die Messart (Pixel, Prozente oder Millimeter) für den Rand. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Liest oder setzt die Messart (Pixel, Prozente oder Millimeter) für den Rand. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Signatur (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [setTransparency(double value)](#setTransparency-double-) | Liest oder setzt die Transparenz der Signatur (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). |
| [getText()](#getText--) | Ruft den Text der Signatur ab oder legt ihn fest. |
| [setText(String value)](#setText-java.lang.String-) | Ruft den Text der Signatur ab oder legt ihn fest. |
| [getFont()](#getFont--) | Ruft die Schriftart der Signatur ab oder legt sie fest. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Ruft die Schriftart der Signatur ab oder legt sie fest. |
| [getForeColor()](#getForeColor--) | Liest oder setzt die Vordergrundfarbe der Signatur. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Liest oder setzt die Vordergrundfarbe der Signatur. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Liest oder setzt den Typ der Textsignatur-Implementierung. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Liest oder setzt den Typ der Textsignatur-Implementierung. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Horizontale Ausrichtung des Textes innerhalb einer Signatur. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Horizontale Ausrichtung des Textes innerhalb einer Signatur. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Vertikale Ausrichtung des Textes innerhalb einer Signatur. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Vertikale Ausrichtung des Textes innerhalb einer Signatur. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Liest oder setzt den Titel des Textformularfeldes, in das die Textsignatur eingefügt wird. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Liest oder setzt den Titel des Textformularfeldes, in das die Textsignatur eingefügt wird. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Liest oder setzt den Typ des Formularfeldes, in das die Textsignatur eingefügt wird. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Liest oder setzt den Typ des Formularfeldes, in das die Textsignatur eingefügt wird. |
| [getShapeType()](#getShapeType--) | Liest oder setzt den Typ der Form, in die der Text eingefügt wird. |
| [setShapeType(int value)](#setShapeType-int-) | Liest oder setzt den Typ der Form, in die der Text eingefügt wird. |
| [getSignatureID()](#getSignatureID--) | Liest oder setzt die eindeutige ID der Signatur. |
| [setSignatureID(int value)](#setSignatureID-int-) | Liest oder setzt die eindeutige ID der Signatur. |
| [getBorder()](#getBorder--) | Geben Sie die Rahmeneinstellungen an. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Geben Sie die Rahmeneinstellungen an. |
| [getBackground()](#getBackground--) | Liest oder setzt die Hintergrund-Einstellungen der Signatur. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Liest oder setzt die Hintergrund-Einstellungen der Signatur. |
| [getNative()](#getNative--) | Liest oder setzt das native Attribut. |
| [setNative(boolean value)](#setNative-boolean-) | Liest oder setzt das native Attribut. |
| [getShapePosition()](#getShapePosition--) | Definiert, wo die Form im Dokumentlayout dargestellt werden soll. |
| [setShapePosition(int value)](#setShapePosition-int-) | Definiert, wo die Form im Dokumentlayout dargestellt werden soll. |
| [validate()](#validate--) | Interne Methode zur Validierung der Optionsparameter. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Initialisiert eine neue Instanz der Klasse SignTextOptions mit Standardwerten.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Initialisiert eine neue Instanz der Klasse SignTextOptions mit Text.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Signaturtext. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Linke X-Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType-Eigenschaft). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Linke X-Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType-Eigenschaft). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Obere Y-Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType-Eigenschaft). (funktioniert, wenn keine vertikale Ausrichtung angegeben ist).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obere Y-Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType-Eigenschaft). (funktioniert, wenn keine vertikale Ausrichtung angegeben ist).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType‑Eigenschaft).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Messart (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height.

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


Liest oder setzt den Abstand zwischen Signatur und Dokumentkanten. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Liest oder setzt den Abstand zwischen Signatur und Dokumentkanten. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Liest oder setzt die Messart (Pixel, Prozente oder Millimeter) für den Rand.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Liest oder setzt die Messart (Pixel, Prozente oder Millimeter) für den Rand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Liest oder setzt die Transparenz der Signatur (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). Standardwert ist 0 (undurchsichtig).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Liest oder setzt die Transparenz der Signatur (Wert von 0.0 (undurchsichtig) bis 1.0 (transparent)). Standardwert ist 0 (undurchsichtig).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getText() {#getText--}
```
public final String getText()
```


Ruft den Text der Signatur ab oder legt ihn fest.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ruft den Text der Signatur ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Ruft die Schriftart der Signatur ab oder legt sie fest.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Ruft die Schriftart der Signatur ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Liest oder setzt die Vordergrundfarbe der Signatur.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Liest oder setzt die Vordergrundfarbe der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Liest oder setzt den Typ der Textsignatur-Implementierung.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Liest oder setzt den Typ der Textsignatur-Implementierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Horizontale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild- und Anmerkungs‑Signatur‑Implementierungen unterstützt (siehe [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑Eigenschaft).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Horizontale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild- und Anmerkungs‑Signatur‑Implementierungen unterstützt (siehe [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑Eigenschaft).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Vertikale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild‑Signatur‑Implementierungen unterstützt (siehe [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑Eigenschaft).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Vertikale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild‑Signatur‑Implementierungen unterstützt (siehe [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑Eigenschaft).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Liest oder setzt den Titel des Textformularfeldes, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Liest oder setzt den Titel des Textformularfeldes, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Liest oder setzt den Typ des Formularfeldes, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden. Der Standardwert ist AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Liest oder setzt den Typ des Formularfeldes, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden. Der Standardwert ist AllTextTypes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Liest oder setzt den Typ der Form, in die der Text eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextStamp verwendet werden. Der Standardwert ist Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Liest oder setzt den Typ der Form, in die der Text eingefügt wird. Diese Eigenschaft kann nur mit SignatureImplementation = TextStamp verwendet werden. Der Standardwert ist Rectangle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Liest oder setzt die eindeutige ID der Signatur. Sie kann in den Optionen zur Signaturverifizierung verwendet werden. Die Eigenschaft wird nur für PDF‑Dokumente unterstützt.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Liest oder setzt die eindeutige ID der Signatur. Sie kann in den Optionen zur Signaturverifizierung verwendet werden. Die Eigenschaft wird nur für PDF‑Dokumente unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Geben Sie die Rahmeneinstellungen an.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Geben Sie die Rahmeneinstellungen an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Liest oder setzt die Hintergrund-Einstellungen der Signatur.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Liest oder setzt die Hintergrund-Einstellungen der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Liest oder setzt das native Attribut. Wenn es gesetzt ist, können dokumentspezifische Signaturen verwendet werden. Das native Textwasserzeichen für Word‑Verarbeitungs‑Dokumente unterscheidet sich beispielsweise vom regulären.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Liest oder setzt das native Attribut. Wenn es gesetzt ist, können dokumentspezifische Signaturen verwendet werden. Das native Textwasserzeichen für Word‑Verarbeitungs‑Dokumente unterscheidet sich beispielsweise vom regulären.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definiert, wo die Form im Dokumentlayout dargestellt werden soll.

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definiert, wo die Form im Dokumentlayout dargestellt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### validate() {#validate--}
```
public void validate()
```


Interne Methode zur Validierung der Optionsparameter.

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.

**Returns:**
java.lang.String -
