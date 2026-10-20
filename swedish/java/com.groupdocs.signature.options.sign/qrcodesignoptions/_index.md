---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar QR‑Code‑signaturalternativen."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Representerar QR‑Code‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Initierar en ny instans av QRCodeSignOptions‑klassen med standardvärden. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Initierar en ny instans av QRCodeSignOptions‑klassen med text. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initierar en ny instans av klassen BarcodeSignOptions med text. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Hämtar eller anger QR‑kod‑typ. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Hämtar eller anger QR‑kod‑typ. |
|
|  | [getForeColor()](#getForeColor--) | Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [getInnerMargins()](#getInnerMargins--) | Hämtar eller anger avståndet mellan QR‑kod‑element och resultatbildens kanter. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Hämtar eller anger avståndet mellan QR‑kod‑element och resultatbildens kanter. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Hämtar eller anger justeringen av text i den resulterande QR‑kod‑bilden. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Hämtar eller anger justeringen av text i den resulterande QR‑kod‑bilden. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Hämtar eller anger filnamnet för QR‑kod‑logobilden. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Hämtar eller anger filnamnet för QR‑kod‑logobilden. |
|
|  | [getLogoStream()](#getLogoStream--) | Hämtar eller anger strömmen för QR‑kod‑logobilden. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Hämtar eller anger strömmen för QR‑kod‑logobilden. |
|
|  | [getData()](#getData--) | Hämtar eller anger anpassat objekt för att serialisera till QR‑Kod‑innehåll. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Hämtar eller anger anpassat objekt för att serialisera till QR‑Kod‑innehåll. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [getReturnContent()](#getReturnContent--) | Hämtar eller anger flagga för att hämta QR‑Code‑bildinnehåll för en signatur som placerats på dokumentsidan. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Hämtar eller anger flagga för att hämta QR‑Code‑bildinnehåll för en signatur som placerats på dokumentsidan. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtyp för återlämnat bildinnehåll för QR‑Code‑signaturen när ReturnContent‑egenskapen är aktiverad. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Initierar en ny instans av QRCodeSignOptions‑klassen med standardvärden.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Initierar en ny instans av QRCodeSignOptions‑klassen med text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Signaturtext. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Initierar en ny instans av klassen BarcodeSignOptions med text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | QRCode‑text |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode‑kodningstyp se [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Hämtar eller anger QR‑kod‑typ.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Hämtar eller anger QR‑kod‑typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Hämtar eller anger förgrundsfärgen för QR‑kod‑staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Hämtar eller anger avståndet mellan QR‑kod‑element och resultatbildens kanter.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Hämtar eller anger avståndet mellan QR‑kod‑element och resultatbildens kanter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Hämtar eller anger justeringen av text i den resulterande QR‑kod‑bilden.
Standardvärdet är None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Hämtar eller anger justeringen av text i den resulterande QR‑kod‑bilden.
Standardvärdet är None.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Hämtar eller anger filnamnet för QR‑kod‑logobilden.
Denna egenskap används endast om LogoStream inte är angiven.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Hämtar eller anger filnamnet för QR‑kod‑logobilden.
Denna egenskap används endast om LogoStream inte är angiven.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Hämtar eller anger strömmen för QR‑kod‑logobilden.
Om denna egenskap anges används den alltid istället för LogoGuid.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Hämtar eller anger strömmen för QR‑kod‑logobilden.
Om denna egenskap anges används den alltid istället för LogoGuid.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Hämtar eller anger anpassat objekt för att serialisera till QR‑Kod‑innehåll.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Hämtar eller anger anpassat objekt för att serialisera till QR‑Kod‑innehåll.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

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


Hämtar eller anger flagga för att hämta QR‑Code‑bildinnehåll för en signatur som placerats på dokumentsidan.
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


Hämtar eller anger flagga för att hämta QR‑Code‑bildinnehåll för en signatur som placerats på dokumentsidan.
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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om angivet format inte stöds kommer QR‑Code‑bildinnehållet i .png‑format att returneras.


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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om angivet format inte stöds kommer QR‑Code‑bildinnehållet i .png‑format att returneras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
