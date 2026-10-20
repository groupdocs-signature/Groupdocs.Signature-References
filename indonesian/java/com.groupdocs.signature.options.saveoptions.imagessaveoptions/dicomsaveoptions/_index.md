---
title: "DicomSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan untuk dokumen gambar DICOM."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Opsi penyimpanan untuk dokumen gambar DICOM.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | Membuat DicomSaveOptions dengan nilai default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | Data XMP untuk DICOM. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | Data XMP untuk DICOM. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Membuat DicomSaveOptions dengan nilai default.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


Data XMP untuk DICOM. Gunakan untuk mengatur metadata gambar.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


Data XMP untuk DICOM. Gunakan untuk mengatur metadata gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

