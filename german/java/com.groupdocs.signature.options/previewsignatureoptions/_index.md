---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Optionen für die Signaturvorschau dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Stellt Optionen für die Signaturvorschau dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Initialisiert das PreviewSignatureOptions-Objekt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Eindeutiger Wert, um die Signatur zu unterscheiden. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Eindeutiger Wert, um die Signatur zu unterscheiden. |
|
|  | [getSignOptions()](#getSignOptions--) | Signaturoptionen zum Erzeugen einer Vorschau. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Signaturoptionen zum Erzeugen einer Vorschau. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Ruft das Format der Vorschaubilder ab oder legt es fest. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ruft das Format der Vorschaubilder ab oder legt es fest. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Initialisiert das PreviewSignatureOptions-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen, für die eine Vorschau erzeugt werden soll. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Schnittstelle, die die Methode zum Erstellen eines Ausgabeseiten-Vorschau-Streams definiert. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Eindeutiger Wert, um die Signatur zu unterscheiden.
Verwenden Sie SignatureId, um die Vorschauoptionen zu identifizieren.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Eindeutiger Wert, um die Signatur zu unterscheiden.
Verwenden Sie SignatureId, um die Vorschauoptionen zu identifizieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Signaturoptionen zum Erzeugen einer Vorschau.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Signaturoptionen zum Erzeugen einer Vorschau.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Ruft das Format der Vorschaubilder ab oder legt es fest.
Standardwert ist PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ruft das Format der Vorschaubilder ab oder legt es fest.
Standardwert ist PNG


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

