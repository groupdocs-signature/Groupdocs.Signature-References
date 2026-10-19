---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "DICOM 图像文档的保存选项。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

DICOM 图像文档的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | 使用默认值创建 DicomSaveOptions。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | DICOM 的 XMP 数据。 |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | DICOM 的 XMP 数据。 |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


使用默认值创建 DicomSaveOptions。


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


DICOM 的 XMP 数据。用于设置图像元数据。


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


DICOM 的 XMP 数据。用于设置图像元数据。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

