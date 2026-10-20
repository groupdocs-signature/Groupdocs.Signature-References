---
title: "TextSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Text‑signaturalternativen."
type: docs
weight: 18
url: /sv/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Representerar Text‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | Initierar en ny instans av klassen SignTextOptions med standardvärden. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Initierar en ny instans av klassen SignTextOptions med text. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLeft()](#getLeft--) | Vänster X-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
|
|  | [setLeft(int value)](#setLeft-int-) | Vänster X-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
|
|  | [getTop()](#getTop--) | Övre Y-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
|
|  | [setTop(int value)](#setTop-int-) | Övre Y-position för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
|
|  | [getWidth()](#getWidth--) | Bredd för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).
|
|  | [setWidth(int value)](#setWidth-int-) | Bredd för signaturen på dokumentsidan i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).
|
|  | [getHeight()](#getHeight--) | Höjd på signatur på dokumentsida i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).
|
|  | [setHeight(int value)](#setHeight-int-) | Höjd på signatur på dokumentsida i måttenheter |
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).
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
|  | [getText()](#getText--) | Hämtar eller anger signaturens text. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger signaturens text. |
|
|  | [getFont()](#getFont--) | Hämtar eller anger signaturens teckensnitt. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Hämtar eller anger signaturens teckensnitt. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | Intern: teckensnittet som denna instans hade när den skapades, eller standardteckensnittet. |
|
|  | [getForeColor()](#getForeColor--) | Hämtar eller anger förgrundsfärgen för signaturen. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Hämtar eller anger förgrundsfärgen för signaturen. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Hämtar eller anger typen av textsignaturimplementation. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Hämtar eller anger typen av textsignaturimplementation. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Horisontell justering av text i en signatur. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Horisontell justering av text i en signatur. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Vertikal justering av text i en signatur. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Vertikal justering av text i en signatur. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Hämtar eller anger typen av formulärfält för att placera textsignatur i det. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Hämtar eller anger typen av formulärfält för att placera textsignatur i det. |
|
|  | [getShapeType()](#getShapeType--) | Hämtar eller anger typen av form för att placera text. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | Hämtar eller anger typen av form för att placera text. |
|
|  | [getSignatureID()](#getSignatureID--) | Hämtar eller anger det unika ID:t för signaturen. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Hämtar eller anger det unika ID:t för signaturen. |
|
|  | [getBorder()](#getBorder--) | Ange kantinställningar. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Ange kantinställningar. |
|
|  | [getBackground()](#getBackground--) | Hämtar eller anger signaturens bakgrundsinställningar. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Hämtar eller anger signaturens bakgrundsinställningar. |
|
|  | [getNative()](#getNative--) | Hämtar eller anger det inbyggda attributet. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Hämtar eller anger det inbyggda attributet. |
|
|  | [getShapePosition()](#getShapePosition--) | Definierar var formen ska presenteras i dokumentlayouten. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definierar var formen ska presenteras i dokumentlayouten. |
|
|  | [validate()](#validate--) | Intern metod för att validera alternativens parametrar. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Initierar en ny instans av klassen SignTextOptions med standardvärden.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Initierar en ny instans av klassen SignTextOptions med text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Signaturtext. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Vänster X-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
(fungerar om horisontell justering inte är specificerad).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Vänster X-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
(fungerar om horisontell justering inte är specificerad).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Övre Y-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
(fungerar om vertikal justering inte är specificerad).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Övre Y-position för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType property).
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
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredd för signaturen på dokumentsidan i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjd på signatur på dokumentsida i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjd på signatur på dokumentsida i måttenheter
(pixlar, procent eller millimeter se [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType property).


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

### getText() {#getText--}
```
public final String getText()
```


Hämtar eller anger signaturens text.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Hämtar eller anger signaturens text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Hämtar eller anger signaturens teckensnitt.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Hämtar eller anger signaturens teckensnitt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


Intern: teckensnittet som denna instans hade när den skapades, eller standardteckensnittet.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Hämtar eller anger förgrundsfärgen för signaturen.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Hämtar eller anger förgrundsfärgen för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Hämtar eller anger typen av textsignaturimplementation.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Hämtar eller anger typen av textsignaturimplementation.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Horisontell justering av text i en signatur.
Denna funktion stöds endast för bild- och annoteringssignaturimplementationer
(se [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑egenskapen).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Horisontell justering av text i en signatur.
Denna funktion stöds endast för bild- och annoteringssignaturimplementationer
(se [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑egenskapen).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Vertikal justering av text i en signatur.
Denna funktion stöds endast för bildsignaturimplementation
(se [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑egenskapen).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Vertikal justering av text i en signatur.
Denna funktion stöds endast för bildsignaturimplementation
(se [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation‑egenskapen).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det.
Denna egenskap kan endast användas med SignatureImplementation = TextToFormField.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det.
Denna egenskap kan endast användas med SignatureImplementation = TextToFormField.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Hämtar eller anger typen av formulärfält för att placera textsignatur i det.
Denna egenskap kan endast användas med SignatureImplementation = TextToFormField.
Standardvärdet är AllTextTypes.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Hämtar eller anger typen av formulärfält för att placera textsignatur i det.
Denna egenskap kan endast användas med SignatureImplementation = TextToFormField.
Standardvärdet är AllTextTypes.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Hämtar eller anger typen av form för att placera text.
Denna egenskap kan endast användas med SignatureImplementation = TextStamp.
Standardvärdet är Rectangle.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Hämtar eller anger typen av form för att placera text.
Denna egenskap kan endast användas med SignatureImplementation = TextStamp.
Standardvärdet är Rectangle.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Hämtar eller anger det unika ID:t för signaturen. Det kan användas i alternativ för signaturverifiering. Egenskapen stöds endast för Pdf-dokument


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Hämtar eller anger det unika ID:t för signaturen. Det kan användas i alternativ för signaturverifiering. Egenskapen stöds endast för Pdf-dokument


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Hämtar eller anger signaturens bakgrundsinställningar.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Hämtar eller anger signaturens bakgrundsinställningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Hämtar eller anger det inbyggda attributet. Om det är angivet kan dokumentspecifika signaturer användas.
Inbyggt textvattenmärke för WordProcessing-dokument skiljer sig från vanliga, till exempel.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Hämtar eller anger det inbyggda attributet. Om det är angivet kan dokumentspecifika signaturer användas.
Inbyggt textvattenmärke för WordProcessing-dokument skiljer sig från vanliga, till exempel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### validate() {#validate--}
```
public void validate()
```


Intern metod för att validera alternativens parametrar.


### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
