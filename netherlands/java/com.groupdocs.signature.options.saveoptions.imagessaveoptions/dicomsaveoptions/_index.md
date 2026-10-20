---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslagopties voor DICOM-afbeeldingsdocumenten."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Opslagopties voor DICOM-afbeeldingsdocumenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | Maakt DicomSaveOptions met standaardwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | XMP-gegevens voor DICOM. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | XMP-gegevens voor DICOM. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Maakt DicomSaveOptions met standaardwaarden.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


XMP-gegevens voor DICOM. Gebruik het om afbeeldingsmetadata in te stellen.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


XMP-gegevens voor DICOM. Gebruik het om afbeeldingsmetadata in te stellen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

