---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar abstrakta sökalternativ för QR‑kodsignaturer."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Representerar abstrakta sökalternativ för QR‑kodsignaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initierar en ny instans av klassen QRCodeSearchOptions med standardvärden. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initierar en ny instans av klassen QRCodeSearchOptions med kodningstypvärde. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initierar en ny instans av klassen QRCodeSearchOptions med kodningstyp- och textvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Anger egenskapen Encode Type för att söka QR-koder. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Anger egenskapen Encode Type för att söka QR-koder. |
|
|  | [getText()](#getText--) | Anger QR-Code-signaturtext om den ska sökas och matchas. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Anger QR-Code-signaturtext om den ska sökas och matchas. |
|
|  | [getMatchType()](#getMatchType--) | Hämtar eller anger söktyp för matchning av QR-Code-text. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Hämtar eller anger söktyp för matchning av QR-Code-text. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [getReturnContent()](#getReturnContent--) | Hämtar eller anger flagga för att hämta QR-Code-bildinnehåll för signaturen på dokumentsidan. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Hämtar eller anger flagga för att hämta QR-Code-bildinnehåll för signaturen på dokumentsidan. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initierar en ny instans av klassen QRCodeSearchOptions med standardvärden.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initierar en ny instans av klassen QRCodeSearchOptions med kodningstypvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Anger QR-Code-kodningstyp. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initierar en ny instans av klassen QRCodeSearchOptions med kodningstyp- och textvärden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Anger QR-Code-kodningstyp. |
|
|  | text | java.lang.String | Ange text för QR-Code-signatur. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Anger egenskapen Encode Type för att söka QR-koder.
Om detta värde inte är angivet, utförs sökningen för alla stödjade QR-Code-typer.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Anger egenskapen Encode Type för att söka QR-koder.
Om detta värde inte är angivet, utförs sökningen för alla stödjade QR-Code-typer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Anger QR-Code-signaturtext om den ska sökas och matchas.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Anger QR-Code-signaturtext om den ska sökas och matchas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Hämtar eller anger söktyp för matchning av QR-Code-text. Den används endast när egenskapen Text är angiven.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Hämtar eller anger söktyp för matchning av QR-Code-text. Den används endast när egenskapen Text är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Hämtar eller anger flagga för att hämta QR-Code-bildinnehåll för signaturen på dokumentsidan.
Om denna flagga sätts till true behåller QR‑Code‑signaturens bildinnehåll rå bilddata i det begärda formatet
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Hämtar eller anger flagga för att hämta QR-Code-bildinnehåll för signaturen på dokumentsidan.
Om denna flagga sätts till true behåller QR‑Code‑signaturens bildinnehåll rå bilddata i det begärda formatet
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad.
Som standard är den satt till Null. Det betyder att QR‑Code‑bildinnehållet returneras i originalformat.
Detta bildformat anges på
QrCodeSignature.Format
()
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds returneras QR-Code-bildinnehållet i original-.png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad.
Som standard är den satt till Null. Det betyder att QR‑Code‑bildinnehållet returneras i originalformat.
Detta bildformat anges på
QrCodeSignature.Format
()
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds returneras QR-Code-bildinnehållet i original-.png.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

