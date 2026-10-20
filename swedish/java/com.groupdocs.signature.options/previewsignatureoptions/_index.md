---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar alternativ för signaturförhandsgranskning."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Representerar alternativ för signaturförhandsgranskning.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Initierar PreviewSignatureOptions-objektet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Unikt värde för att särskilja signaturen. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Unikt värde för att särskilja signaturen. |
|
|  | [getSignOptions()](#getSignOptions--) | Signaturalternativ för att generera förhandsgranskning. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Signaturalternativ för att generera förhandsgranskning. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Hämtar eller anger format för förhandsgranskningsbilder. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Hämtar eller anger format för förhandsgranskningsbilder. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Initierar PreviewSignatureOptions-objektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Signaturalternativen för att generera en förhandsgranskning för. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Gränssnitt som definierar en metod för att skapa en förhandsgranskningsström för utskriftsidan. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unikt värde för att särskilja signaturen.
Använd SignatureId för att identifiera förhandsgranskningsalternativen.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Unikt värde för att särskilja signaturen.
Använd SignatureId för att identifiera förhandsgranskningsalternativen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Signaturalternativ för att generera förhandsgranskning.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Signaturalternativ för att generera förhandsgranskning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Hämtar eller anger format för förhandsgranskningsbilder.
Standardvärdet är PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Hämtar eller anger format för förhandsgranskningsbilder.
Standardvärdet är PNG


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

