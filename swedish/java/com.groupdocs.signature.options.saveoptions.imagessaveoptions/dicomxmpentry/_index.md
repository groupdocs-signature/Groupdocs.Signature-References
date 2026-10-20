---
title: "DicomXmpEntry"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Post för XMP-data för DICOM-bilder .dcm."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

Inmatning av XMP-data för DICOM-bilder (.dcm).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Skapar XMP-post för DICOM-bild. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getType()](#getType--) | Posttyp. |
|
|  | [getValue()](#getValue--) | Postvärde. |
|
|  | [toString()](#toString--) | Hämta Xmp‑postens textrepresentation. |
|
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Skapar XMP-post för DICOM-bild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | typ | int | Posttyp |
|
|  | värde | java.lang.String | Postvärde |
|

### getType() {#getType--}
```
public final int getType()
```


Posttyp.


**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Postvärde.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Hämta Xmp‑postens textrepresentation.


**Returns:**
java.lang.String - Xmp‑postens textrepresentation.

