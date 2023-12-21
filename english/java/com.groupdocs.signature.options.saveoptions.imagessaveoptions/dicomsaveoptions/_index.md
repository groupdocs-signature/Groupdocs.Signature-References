---
title: DicomSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Save options for DICOM image documents.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Save options for DICOM image documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [DicomSaveOptions()](#DicomSaveOptions--) | Creates DicomSaveOptions with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getXmpEntries()](#getXmpEntries--) | XMP data for DICOM. |
| [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | XMP data for DICOM. |
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Creates DicomSaveOptions with default values.

### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


XMP data for DICOM. Use it for setting image metadata.

**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


XMP data for DICOM. Use it for setting image metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

