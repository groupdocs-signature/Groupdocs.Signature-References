---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de QR-Code-handtekeningopties."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Vertegenwoordigt de QR-Code-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met standaardwaarden. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met tekst. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Haalt op of stelt het QRCode-type in. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Haalt op of stelt het QRCode-type in. |
|
|  | [getForeColor()](#getForeColor--) | Haalt op of stelt de voorgrondkleur van QR-Code-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Haalt op of stelt de voorgrondkleur van QR-Code-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Haalt op of stelt de voorgrondkleur van QR-Code-balken in. |
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie.
|
|  | [getInnerMargins()](#getInnerMargins--) | Haalt op of stelt de ruimte tussen QRCode-elementen en de randen van de resulterende afbeelding in. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Haalt op of stelt de ruimte tussen QRCode-elementen en de randen van de resulterende afbeelding in. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Haalt op of stelt de uitlijning van tekst in de resulterende QR-code-afbeelding in. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Haalt op of stelt de uitlijning van tekst in de resulterende QR-code-afbeelding in. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Haalt op of stelt de bestandsnaam van de QR-code-logo-afbeelding in. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Haalt op of stelt de bestandsnaam van de QR-code-logo-afbeelding in. |
|
|  | [getLogoStream()](#getLogoStream--) | Haalt op of stelt de QR-code-logo-afbeeldingsstroom in. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Haalt op of stelt de QR-code-logo-afbeeldingsstroom in. |
|
|  | [getData()](#getData--) | Haalt op of stelt een aangepast object in om te serialiseren naar QR-Code-inhoud. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Haalt op of stelt een aangepast object in om te serialiseren naar QR-Code-inhoud. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [getReturnContent()](#getReturnContent--) | Haalt op of stelt de vlag in om QR-Code-afbeeldingsinhoud van een handtekening op te halen die op een documentpagina is geplaatst. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Haalt op of stelt de vlag in om QR-Code-afbeeldingsinhoud van een handtekening op te halen die op een documentpagina is geplaatst. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met standaardwaarden.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met tekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Handtekeningtekst. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | QRCode-tekst |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode-coderingstype zie [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Haalt op of stelt het QRCode-type in.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Haalt op of stelt het QRCode-type in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Haalt op of stelt de voorgrondkleur van QR-Code-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Haalt op of stelt de voorgrondkleur van QR-Code-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Haalt op of stelt de voorgrondkleur van QR-Code-balken in.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Haalt op of stelt de ruimte tussen QRCode-elementen en de randen van de resulterende afbeelding in.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Haalt op of stelt de ruimte tussen QRCode-elementen en de randen van de resulterende afbeelding in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Haalt op of stelt de uitlijning van tekst in de resulterende QR-code-afbeelding in.
Standaardwaarde is None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Haalt op of stelt de uitlijning van tekst in de resulterende QR-code-afbeelding in.
Standaardwaarde is None.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Haalt op of stelt de bestandsnaam van de QR-code-logo-afbeelding in.
Deze eigenschap wordt alleen gebruikt als LogoStream niet is opgegeven.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Haalt op of stelt de bestandsnaam van de QR-code-logo-afbeelding in.
Deze eigenschap wordt alleen gebruikt als LogoStream niet is opgegeven.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Haalt op of stelt de QR-code-logo-afbeeldingsstroom in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van LogoGuid.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Haalt op of stelt de QR-code-logo-afbeeldingsstroom in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van LogoGuid.
Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik het voorzichtig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Haalt op of stelt een aangepast object in om te serialiseren naar QR-Code-inhoud.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Haalt op of stelt een aangepast object in om te serialiseren naar QR-Code-inhoud.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Haalt op of stelt de vlag in om QR-Code-afbeeldingsinhoud van een handtekening op te halen die op een documentpagina is geplaatst.
Als deze vlag op true is ingesteld, behoudt de QR-Code-handtekening afbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standaard is deze optie uitgeschakeld.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Haalt op of stelt de vlag in om QR-Code-afbeeldingsinhoud van een handtekening op te halen die op een documentpagina is geplaatst.
Als deze vlag op true is ingesteld, behoudt de QR-Code-handtekening afbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat.
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


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld.
Standaard is deze ingesteld op Null. Dat betekent dat de QR-Code-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de QR-Code-afbeeldingsinhoud in .png-formaat geretourneerd.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld.
Standaard is deze ingesteld op Null. Dat betekent dat de QR-Code-afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd.
Dit afbeeldingsformaat wordt gespecificeerd op
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de QR-Code-afbeeldingsinhoud in .png-formaat geretourneerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
