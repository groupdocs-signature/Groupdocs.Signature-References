---
title: "StampSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Stämpel‑signaturalternativen."
type: docs
weight: 17
url: /sv/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Representerar Stämpel‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Initierar en ny instans av klassen StampSignOptions med standardvärden. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Initierar en ny instans av klassen StampSignOptions med justeringsalternativ. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStampType()](#getStampType--) | Hämtar eller anger stämpeltyp. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Hämtar eller anger stämpeltyp. |
|
|  | [getOuterLines()](#getOuterLines--) | Lista över yttre linjer som renderas som koncentriska cirklar. |
|
|  | [getInnerLines()](#getInnerLines--) | Lista över inre linjer renderade som en uppsättning rektanglar. |
|
|  | [getBackground()](#getBackground--) | Hämtar eller anger Stamp‑bakgrunden. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Hämtar eller anger Stamp‑bakgrunden. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger bakgrundsfärgen för signaturen. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Hämtar eller anger bakgrundsfärgen för signaturen. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Hämtar eller anger signaturens bakgrundsborste. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Hämtar eller anger signaturens bakgrundsborste. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Hämtar eller anger beskärningstyp för bakgrundsfärg för signaturen. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Hämtar eller anger beskärningstyp för bakgrundsfärg för signaturen. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Hämtar eller anger beskärningstyp för bakgrundsbild för signaturen. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Hämtar eller anger beskärningstyp för bakgrundsbild för signaturen. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Initierar en ny instans av klassen StampSignOptions med standardvärden.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Initierar en ny instans av klassen StampSignOptions med justeringsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | vänster | int | X‑koordinaten för den vänstra övre kanten av Stamp‑signaturen |
|
|  | övre | int | Y‑koordinaten för den vänstra övre kanten av Stamp‑signaturen |
|
|  | bredd | int | Bredden på Stamp‑signaturen |
|
|  | höjd | int | Höjden på Stamp‑signaturen |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Hämtar eller anger stämpeltyp.
Värdet är som standard Round.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Hämtar eller anger stämpeltyp.
Värdet är som standard Round.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Lista över yttre linjer som renderas som koncentriska cirklar.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Lista över inre linjer renderade som en uppsättning rektanglar.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Hämtar eller anger Stamp‑bakgrunden.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Hämtar eller anger Stamp‑bakgrunden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Hämtar eller anger bakgrundsfärgen för signaturen.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Hämtar eller anger bakgrundsfärgen för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Hämtar eller anger signaturens bakgrundsborste. Värdet är som standard null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Hämtar eller anger signaturens bakgrundsborste. Värdet är som standard null.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Hämtar eller anger beskärningstyp för bakgrundsfärg för signaturen.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Hämtar eller anger beskärningstyp för bakgrundsfärg för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Hämtar eller anger beskärningstyp för bakgrundsbild för signaturen.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Hämtar eller anger beskärningstyp för bakgrundsbild för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering


**Returns:**
java.lang.String -
