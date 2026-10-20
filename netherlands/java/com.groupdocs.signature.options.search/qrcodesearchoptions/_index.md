---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer abstracte zoekopties voor QR-codehandtekeningen."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Geeft weer abstracte zoekopties voor QR-codehandtekeningen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met standaardwaarden. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met een encode-typwaarde. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met encode-typ- en tekstwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Specificeert de Encode Type-eigenschap om QR-codes te zoeken. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Specificeert de Encode Type-eigenschap om QR-codes te zoeken. |
|
|  | [getText()](#getText--) | Specificeert de QR-code-handtekeningtekst als deze moet worden gezocht en overeenkomen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Specificeert de QR-code-handtekeningtekst als deze moet worden gezocht en overeenkomen. |
|
|  | [getMatchType()](#getMatchType--) | Haalt op of stelt de QR-code-tekst Match Type-zoekopdracht in. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Haalt op of stelt de QR-code-tekst Match Type-zoekopdracht in. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [getReturnContent()](#getReturnContent--) | Haalt op of stelt de vlag in om de QR-code-afbeeldingsinhoud van de handtekening op de documentpagina te pakken. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Haalt op of stelt de vlag in om de QR-code-afbeeldingsinhoud van de handtekening op de documentpagina te pakken. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met standaardwaarden.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met een encode-typwaarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specificeert het QR-code-encode type. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initialiseert een nieuw exemplaar van de QRCodeSearchOptions-klasse met encode-typ- en tekstwaarden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specificeert het QR-code-encode type. |
|
|  | tekst | java.lang.String | Stel de tekst van de QR-code-handtekening in. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specificeert de Encode Type-eigenschap om QR-codes te zoeken.
Als deze waarde niet is ingesteld, wordt de zoekopdracht uitgevoerd voor alle ondersteunde QR-code-typen.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Specificeert de Encode Type-eigenschap om QR-codes te zoeken.
Als deze waarde niet is ingesteld, wordt de zoekopdracht uitgevoerd voor alle ondersteunde QR-code-typen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specificeert de QR-code-handtekeningtekst als deze moet worden gezocht en overeenkomen.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specificeert de QR-code-handtekeningtekst als deze moet worden gezocht en overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Haalt op of stelt de QR-code-tekst Match Type-zoekopdracht in. Wordt alleen gebruikt wanneer de eigenschap Text is ingesteld.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Haalt op of stelt de QR-code-tekst Match Type-zoekopdracht in. Wordt alleen gebruikt wanneer de eigenschap Text is ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


Haalt op of stelt de vlag in om de QR-code-afbeeldingsinhoud van de handtekening op de documentpagina te pakken.
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


Haalt op of stelt de vlag in om de QR-code-afbeeldingsinhoud van de handtekening op de documentpagina te pakken.
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
()
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de QR-code-afbeeldingsinhoud in de oorspronkelijke .png geretourneerd.


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
()
Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP.
Als het opgegeven formaat niet wordt ondersteund, wordt de QR-code-afbeeldingsinhoud in de oorspronkelijke .png geretourneerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

