---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для DICOM‑изображений."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Параметры сохранения для DICOM‑изображений.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | Создаёт DicomSaveOptions со значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | Данные XMP для DICOM. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | Данные XMP для DICOM. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Создаёт DicomSaveOptions со значениями по умолчанию.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


Данные XMP для DICOM. Используйте их для установки метаданных изображения.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


Данные XMP для DICOM. Используйте их для установки метаданных изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

