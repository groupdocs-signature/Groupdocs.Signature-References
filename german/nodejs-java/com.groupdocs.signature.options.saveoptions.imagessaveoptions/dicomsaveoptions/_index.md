---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Speicheroptionen für DICOM-Bilddokumente."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Speicheroptionen für DICOM-Bilddokumente.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DicomSaveOptions()](#DicomSaveOptions--) | Erstellt DicomSaveOptions mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmpEntries()](#getXmpEntries--) | XMP-Daten für DICOM. |
| [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | XMP-Daten für DICOM. |
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Erstellt DicomSaveOptions mit Standardwerten.

### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


XMP-Daten für DICOM. Verwenden Sie sie zum Festlegen von Bildmetadaten.

**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


XMP-Daten für DICOM. Verwenden Sie sie zum Festlegen von Bildmetadaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

