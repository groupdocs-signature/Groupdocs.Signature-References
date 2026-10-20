---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van QR-code handtekening."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Bevat eigenschappen van QR-code handtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Initialiseer QrCodeSignature-object met handtekeningidentificatie die is verkregen na het zoekproces. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Specificeert het QR-code Encode Type. |
|
|  | [getText()](#getText--) | Specificeert de tekst van QR-code. |
|
|  | [getFormat()](#getFormat--) | Specificeert het formaat van de QR-code handtekeningafbeelding. |
|
|  | [getContent()](#getContent--) | Specificeert QR-code binaire data afbeeldinginhoud van type |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Verkrijg object van QR-Code Handtekeningtekst via deserialisatie. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Verkrijg object van QR-Code Handtekeningtekst via deserialisatie. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon QR-Code Handtekeninginstantie. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Initialiseer QrCodeSignature-object met handtekeningidentificatie die is verkregen na het zoekproces.
Deze unieke identificatie wordt gebruikt om extra eigenschappen voor deze handtekening te vinden vanuit de documenthandtekening‑informatielaag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unieke handtekening‑identificatie verkregen via ondertekenings‑ of zoekmethode. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specificeert het QR-code Encode Type.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specificeert de tekst van QR-code.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specificeert het formaat van de QR-code handtekeningafbeelding.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specificeert QR-code binaire data afbeeldinginhoud van type
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Standaard wordt deze eigenschap niet ingesteld.
Gebruik eigenschap
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) om deze functie in te schakelen.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Verkrijg object van QR-Code Handtekeningtekst via deserialisatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | java.lang.Class<T> |  |

**Returns:**
T -
T
: Type van object om te deserialiseren van QR-Code Tekst

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Verkrijg object van QR-Code Handtekeningtekst via deserialisatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Stel aangepaste gegevensversleutelingimplementatie in |


T
: Type van object om te deserialiseren van QR-Code Tekst
|
| type | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon QR-Code Handtekeninginstantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde QR-code Handtekeninginstantie.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| afbeelding | java.awt.image.BufferedImage |  |

