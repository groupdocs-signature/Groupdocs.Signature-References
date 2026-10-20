---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för QR‑kodsignatur."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Innehåller egenskaper för QR‑kodsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Initiera QrCodeSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Anger QR-kodens kodningstyp. |
|
|  | [getText()](#getText--) | Anger texten för QR-kod. |
|
|  | [getFormat()](#getFormat--) | Anger formatet för QR-kodsignaturens bild. |
|
|  | [getContent()](#getContent--) | Anger QR-kodens binära data bildinnehåll av typen |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Hämta objekt från QR-Code Signature Text via deserialisering. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Hämta objekt från QR-Code Signature Text via deserialisering. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona QR-Code Signature-instansen. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Initiera QrCodeSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen.
Denna unika identifierare används för att hitta ytterligare egenskaper för denna signatur från dokumentets signaturinformationslager.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unik signaturidentifierare erhållen via signerings- eller sökmetod. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Anger QR-kodens kodningstyp.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Anger texten för QR-kod.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Anger formatet för QR-kodsignaturens bild.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Anger QR-kodens binära data bildinnehåll av typen
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Som standard kommer denna egenskap inte att sättas.
Använd egenskap
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) för att aktivera denna funktion.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Hämta objekt från QR-Code Signature Text via deserialisering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | java.lang.Class<T> |  |

**Returns:**
T -
T
: Typ av objekt att deserialisera från QR-Code Text

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Hämta objekt från QR-Code Signature Text via deserialisering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Ange anpassad implementation för datakryptering |


T
: Typ av objekt att deserialisera från QR-Code Text
|
| typ | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona QR-Code Signature-instansen.


**Returns:**
java.lang.Object - Returnerar klonad QR-code Signature-instans.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| bild | java.awt.image.BufferedImage |  |

