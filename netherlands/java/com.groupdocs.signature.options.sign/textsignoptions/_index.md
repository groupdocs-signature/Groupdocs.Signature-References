---
title: "TextSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de tekst-handtekeningopties."
type: docs
weight: 18
url: /nl/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Vertegenwoordigt de tekst-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | Initialiseert een nieuw exemplaar van de SignTextOptions-klasse met standaardwaarden. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de SignTextOptions-klasse met tekst. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLeft()](#getLeft--) | Linker X-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
|
|  | [setLeft(int value)](#setLeft-int-) | Linker X-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
|
|  | [getTop()](#getTop--) | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
|
|  | [setTop(int value)](#setTop-int-) | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
|
|  | [getWidth()](#getWidth--) | Breedte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).
|
|  | [setWidth(int value)](#setWidth-int-) | Breedte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).
|
|  | [getHeight()](#getHeight--) | Hoogte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).
|
|  | [setHeight(int value)](#setHeight-int-) | Hoogte van de handtekening op de documentpagina in meetwaarden |
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).
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
|  | [getText()](#getText--) | Haalt op of stelt de tekst van de handtekening in. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de tekst van de handtekening in. |
|
|  | [getFont()](#getFont--) | Haalt op of stelt het lettertype van de handtekening in. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Haalt op of stelt het lettertype van de handtekening in. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | Intern: het lettertype dat deze instantie had bij creatie, of het standaardlettertype. |
|
|  | [getForeColor()](#getForeColor--) | Haalt op of stelt de voorgrondkleur van de handtekening in. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Haalt op of stelt de voorgrondkleur van de handtekening in. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Haalt op of stelt het type van de teksthandtekeningimplementatie in. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Haalt op of stelt het type van de teksthandtekeningimplementatie in. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Horizontale uitlijning van tekst binnen een handtekening. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Horizontale uitlijning van tekst binnen een handtekening. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Verticale uitlijning van tekst binnen een handtekening. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Verticale uitlijning van tekst binnen een handtekening. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Haalt het type formulierveld op of stelt het in om er een tekensignatuur in te plaatsen. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Haalt het type formulierveld op of stelt het in om er een tekensignatuur in te plaatsen. |
|
|  | [getShapeType()](#getShapeType--) | Haalt het type vorm op of stelt het in om tekst te plaatsen. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | Haalt het type vorm op of stelt het in om tekst te plaatsen. |
|
|  | [getSignatureID()](#getSignatureID--) | Haalt de unieke ID van de handtekening op of stelt deze in. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Haalt de unieke ID van de handtekening op of stelt deze in. |
|
|  | [getBorder()](#getBorder--) | Specificeer randinstellingen |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specificeer randinstellingen |
|
|  | [getBackground()](#getBackground--) | Haalt de achtergrondinstellingen van de handtekening op of stelt deze in. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Haalt de achtergrondinstellingen van de handtekening op of stelt deze in. |
|
|  | [getNative()](#getNative--) | Haalt het native attribuut op of stelt dit in. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Haalt het native attribuut op of stelt dit in. |
|
|  | [getShapePosition()](#getShapePosition--) | Definieert waar de vorm moet worden weergegeven in de documentlay-out. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definieert waar de vorm moet worden weergegeven in de documentlay-out. |
|
|  | [validate()](#validate--) | Interne methode om de optieregels te valideren. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Initialiseert een nieuw exemplaar van de SignTextOptions-klasse met standaardwaarden.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Initialiseert een nieuw exemplaar van de SignTextOptions-klasse met tekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Handtekeningtekst. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Linker X-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
(werkt als horizontale uitlijning niet is gespecificeerd).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Linker X-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
(werkt als horizontale uitlijning niet is gespecificeerd).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
(werkt als verticale uitlijning niet is gespecificeerd).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType eigenschap).
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
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Breedte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hoogte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hoogte van de handtekening op de documentpagina in meetwaarden
(pixels, procenten of millimeters zie [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType eigenschap).


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

### getText() {#getText--}
```
public final String getText()
```


Haalt op of stelt de tekst van de handtekening in.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Haalt op of stelt de tekst van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Haalt op of stelt het lettertype van de handtekening in.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Haalt op of stelt het lettertype van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


Intern: het lettertype dat deze instantie had bij creatie, of het standaardlettertype.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Haalt op of stelt de voorgrondkleur van de handtekening in.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Haalt op of stelt de voorgrondkleur van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Haalt op of stelt het type van de teksthandtekeningimplementatie in.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Haalt op of stelt het type van de teksthandtekeningimplementatie in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Horizontale uitlijning van tekst binnen een handtekening.
Deze functie wordt alleen ondersteund voor afbeelding- en annotatie-handtekeningimplementaties.
(zie [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation eigenschap).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Horizontale uitlijning van tekst binnen een handtekening.
Deze functie wordt alleen ondersteund voor afbeelding- en annotatie-handtekeningimplementaties.
(zie [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation eigenschap).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Verticale uitlijning van tekst binnen een handtekening.
Deze functie wordt alleen ondersteund voor afbeelding-handtekeningimplementatie.
(zie [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation eigenschap).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Verticale uitlijning van tekst binnen een handtekening.
Deze functie wordt alleen ondersteund voor afbeelding-handtekeningimplementatie.
(zie [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation eigenschap).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Haalt het type formulierveld op of stelt het in om er een tekensignatuur in te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField.
Standaardwaarde is AllTextTypes.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Haalt het type formulierveld op of stelt het in om er een tekensignatuur in te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField.
Standaardwaarde is AllTextTypes.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Haalt het type vorm op of stelt het in om tekst te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextStamp.
Standaardwaarde is Rectangle.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Haalt het type vorm op of stelt het in om tekst te plaatsen.
Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextStamp.
Standaardwaarde is Rectangle.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Haalt de unieke ID van de handtekening op of stelt deze in. Deze kan worden gebruikt in verificatie‑opties voor handtekeningen. Eigenschap wordt alleen ondersteund voor PDF‑documenten.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Haalt de unieke ID van de handtekening op of stelt deze in. Deze kan worden gebruikt in verificatie‑opties voor handtekeningen. Eigenschap wordt alleen ondersteund voor PDF‑documenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Haalt de achtergrondinstellingen van de handtekening op of stelt deze in.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Haalt de achtergrondinstellingen van de handtekening op of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Haalt het native attribuut op of stelt dit in. Indien ingesteld kunnen documentspecifieke handtekeningen worden gebruikt.
Native tekstwatermerk voor WordProcessing‑documenten verschilt bijvoorbeeld van het reguliere.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Haalt het native attribuut op of stelt dit in. Indien ingesteld kunnen documentspecifieke handtekeningen worden gebruikt.
Native tekstwatermerk voor WordProcessing‑documenten verschilt bijvoorbeeld van het reguliere.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

### validate() {#validate--}
```
public void validate()
```


Interne methode om de optieregels te valideren.


### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
