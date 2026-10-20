---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de Barcode-handtekeningopties."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Vertegenwoordigt de Barcode-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met standaardwaarden. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Haalt op of stelt het Barcode-type in. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Haalt op of stelt het Barcode-type in. |
|
|  | [getForeColor()](#getForeColor--) | Haalt op of stelt de voorgrondkleur van Barcode-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Haalt op of stelt de voorgrondkleur van Barcode-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Haalt op of stelt de voorgrondkleur van Barcode-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [getInnerMargins()](#getInnerMargins--) | Haalt op of stelt de ruimte tussen Barcode-elementen en de randen van de resulterende afbeelding in. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Haalt op of stelt de ruimte tussen Barcode-elementen en de randen van de resulterende afbeelding in. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Haalt op of stelt de uitlijning van tekst in de resulterende Barcode-afbeelding in. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Haalt op of stelt de uitlijning van tekst in de resulterende Barcode-afbeelding in. |
|
|  | [getReturnContent()](#getReturnContent--) | Haalt op of stelt de vlag in om de Barcode-afbeeldingsinhoud van een handtekening die op een documentpagina is geplaatst op te halen. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Haalt op of stelt de vlag in om de Barcode-afbeeldingsinhoud van een handtekening die op een documentpagina is geplaatst op te halen. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld. |
|
|  | [validate()](#validate--) | Interne methode om de parameters van de Barcode-opties te valideren. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met standaardwaarden.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Barcode-tekst |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Barcode-tekst |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode-coderingstype zie [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Haalt op of stelt het Barcode-type in.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Haalt op of stelt het Barcode-type in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Haalt op of stelt de voorgrondkleur van Barcode-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Haalt op of stelt de voorgrondkleur van Barcode-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Haalt op of stelt de voorgrondkleur van Barcode-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Haalt op of stelt de ruimte tussen Barcode-elementen en de randen van de resulterende afbeelding in.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Haalt op of stelt de ruimte tussen Barcode-elementen en de randen van de resulterende afbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Haalt op of stelt de uitlijning van tekst in de resulterende Barcode-afbeelding in.
Standaardwaarde is None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Haalt op of stelt de uitlijning van tekst in de resulterende Barcode-afbeelding in.
Standaardwaarde is None.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Haalt op of stelt de vlag in om de Barcode-afbeeldingsinhoud van een handtekening die op een documentpagina is geplaatst op te halen.
Als deze vlag op true wordt gezet, behoudt de Barcode-handtekeningafbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Haalt op of stelt de vlag in om de Barcode-afbeeldingsinhoud van een handtekening die op een documentpagina is geplaatst op te halen.
Als deze vlag op true wordt gezet, behoudt de Barcode-handtekeningafbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld.
Standaard is het ingesteld op Null. Dat betekent dat de Barcode-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de Barcode-afbeeldingsinhoud in .png-formaat geretourneerd.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode-handtekening wanneer de ReturnContent-eigenschap is ingeschakeld.
Standaard is het ingesteld op Null. Dat betekent dat de Barcode-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de Barcode-afbeeldingsinhoud in .png-formaat geretourneerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Interne methode om de parameters van de Barcode-opties te valideren.


### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
