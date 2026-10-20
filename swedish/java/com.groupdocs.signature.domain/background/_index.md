---
title: "Bakgrund"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar bakgrundsutseende"
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Representerar bakgrundsutseende

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Background()](#Background--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getColor()](#getColor--) | Hämtar eller anger bakgrundsfärgen för signaturen. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Hämtar eller anger bakgrundsfärgen för signaturen. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Hämtar eller anger bakgrundsfärgen för signaturen. |
|
|  | [getTransparency()](#getTransparency--) | Hämtar eller anger bakgrundens transparens (värde från 0.0 (opak) till 1.0 (klar)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Hämtar eller anger bakgrundens transparens (värde från 0.0 (opak) till 1.0 (klar)). |
|
|  | [getBrush()](#getBrush--) | Hämtar eller anger bakgrundspenseln. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Hämtar eller anger bakgrundspenseln. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger bakgrundsfärgen för signaturen.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger bakgrundsfärgen för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Hämtar eller anger bakgrundsfärgen för signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Hämtar eller anger bakgrundens transparens (värde från 0.0 (opak) till 1.0 (klar)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Hämtar eller anger bakgrundens transparens (värde från 0.0 (opak) till 1.0 (klar)).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Hämtar eller anger bakgrundspenseln. Standardvärdet är null.
Denna egenskap förväntar sig en instans av Brush-objektimplementationer.
Se olika Brush-klasser.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Hämtar eller anger bakgrundspenseln. Standardvärdet är null.
Denna egenskap förväntar sig en instans av Brush-objektimplementationer.
Se olika Brush-klasser.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

