---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält QR‑Code‑Signatur‑Eigenschaften."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Enthält QR‑Code‑Signatur‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Initialisieren Sie das QrCodeSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gibt den QR-Code-Kodierungstyp an. |
| [getText()](#getText--) | Gibt den Text des QR-Codes an. |
| [getFormat()](#getFormat--) | Gibt das Format des QR-Code-Signaturbildes an. |
| [getContent()](#getContent--) | Gibt den Binärdatenbildinhalt des QR-Codes vom Typ Format an (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Erhalten Sie das Objekt aus dem QR-Code-Signaturtext durch Deserialisierung. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Erhalten Sie das Objekt aus dem QR-Code-Signaturtext durch Deserialisierung. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klone die QR-Code-Signaturinstanz. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Initialisieren Sie das QrCodeSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. Dieser eindeutige Identifikator wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Signatur-Informationsschicht des Dokuments zu finden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | java.lang.String | Eindeutiger Signatur-Identifikator, der durch Signatur- oder Suchmethode erhalten wurde. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Gibt den QR-Code-Kodierungstyp an.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Gibt den Text des QR-Codes an.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Gibt das Format des QR-Code-Signaturbildes an.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Gibt den Binärdatenbildinhalt des QR-Codes vom Typ Format an (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Standardmäßig wird diese Eigenschaft nicht gesetzt. Verwenden Sie die Eigenschaft QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)), um diese Funktion zu aktivieren.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Erhalten Sie das Objekt aus dem QR-Code-Signaturtext durch Deserialisierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | java.lang.Class<T> |  |

**Returns:**
T -  T : Typ des Objekts, das aus dem QR-Code-Text deserialisiert werden soll
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Erhalten Sie das Objekt aus dem QR-Code-Signaturtext durch Deserialisierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Setzen Sie die benutzerdefinierte Datenverschlüsselungs-Implementierung |

T : Typ des Objekts, das aus dem QR-Code-Text deserialisiert werden soll |
| Typ | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | java.lang.Object | Signatur-Objekt zum Vergleichen. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signatur-Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode

**Returns:**
int - Signatur-Hashcode
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klone die QR-Code-Signaturinstanz.

**Returns:**
java.lang.Object - Gibt die geklonte QR-Code-Signaturinstanz zurück.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| Bild | java.awt.image.BufferedImage |  |

