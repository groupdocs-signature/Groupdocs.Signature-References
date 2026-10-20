---
title: "PngFilterType"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar PNG-bildfiltertyp."
type: docs
weight: 21
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Representerar PNG-bildfiltertyp.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [None](#None) | Null-filtret betyder ingen filtrering för bilddatas rader. |
|
|  | [Sub](#Sub) | Sub-filtret betyder att subtraktiv filtrering kommer att tillämpas på bilddata. |
|
|  | [Up](#Up) | Upp-filtret betyder att rad-för-rad subtraktionsfilter kommer att tillämpas. |
|
|  | [Avg](#Avg) | Avg-filtret betyder att medelvärdesfilter kommer att tillämpas på bilddata. |
|
|  | [Paeth](#Paeth) | Sökvägsförutsägelsefiltret. |
|
|  | [Adaptive](#Adaptive) | Adaptiv filtrering, innebär att sparprocessen kommer att välja det mest lämpliga filtret |
för varje datarad.
|
### None {#None}
```
public static final int None
```


Null-filtret betyder ingen filtrering för bilddatas rader.


### Sub {#Sub}
```
public static final int Sub
```


Sub-filtret betyder att subtraktiv filtrering kommer att tillämpas på bilddata.


### Up {#Up}
```
public static final int Up
```


Upp-filtret betyder att rad-för-rad subtraktionsfilter kommer att tillämpas.


### Avg {#Avg}
```
public static final int Avg
```


Avg-filtret betyder att medelvärdesfilter kommer att tillämpas på bilddata.


### Paeth {#Paeth}
```
public static final int Paeth
```


Sökvägsförutsägelsefiltret.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Adaptiv filtrering, innebär att sparprocessen kommer att välja det mest lämpliga filtret
för varje datarad. Bästa kompression, långsammast exekveringstid.


