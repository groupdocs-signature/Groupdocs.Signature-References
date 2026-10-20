---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Sparalternativ för DICOM-bilddokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Sparalternativ för DICOM-bilddokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | Skapar DicomSaveOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | XMP-data för DICOM. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | XMP-data för DICOM. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Skapar DicomSaveOptions med standardvärden.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


XMP-data för DICOM. Använd den för att ange bildmetadata.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


XMP-data för DICOM. Använd den för att ange bildmetadata.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

