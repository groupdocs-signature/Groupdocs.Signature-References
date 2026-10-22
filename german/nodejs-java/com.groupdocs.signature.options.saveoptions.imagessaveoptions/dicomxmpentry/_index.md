---
title: "DicomXmpEntry"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Eintrag von XMP-Daten für DICOM-Bilder .dcm."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

Eintrag von XMP-Daten für DICOM-Bilder (.dcm).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Erstellt Xmp-Eintrag für DICOM-Bild. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Eintragstyp. |
| [getValue()](#getValue--) | Eintragswert. |
| [toString()](#toString--) | Erhalte die textuelle Darstellung des Xmp-Eintrags. |
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Erstellt Xmp-Eintrag für DICOM-Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Eintragstyp |
| Wert | java.lang.String | Eintragswert |

### getType() {#getType--}
```
public final int getType()
```


Eintragstyp.

**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Eintragswert.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Erhalte die textuelle Darstellung des Xmp-Eintrags.

**Returns:**
java.lang.String - Xmp-Eintrag textuelle Darstellung.
